# Generated by iptables-save v1.8.4 on Thu Nov 10 18:59:25 2022
*filter
:INPUT ACCEPT [222337:304355917]
:FORWARD ACCEPT [0:0]
:OUTPUT ACCEPT [180389:68900977]
:KUBE-FIREWALL - [0:0]
:KUBE-KUBELET-CANARY - [0:0]
[222346:304356942] -A INPUT -j KUBE-FIREWALL
[180399:68902032] -A OUTPUT -j KUBE-FIREWALL
[0:0] -A KUBE-FIREWALL ! -s 127.0.0.0/8 -d 127.0.0.0/8 -m comment --comment "block incoming localnet connections" -m conntrack ! --ctstate RELATED,ESTABLISHED,DNAT -j DROP
[0:0] -A KUBE-FIREWALL -m comment --comment "kubernetes firewall for dropping marked packets" -m mark --mark 0x8000/0x8000 -j DROP
COMMIT
# Completed on Thu Nov 10 18:59:25 2022
# Generated by iptables-save v1.8.4 on Thu Nov 10 18:59:25 2022
*mangle
:PREROUTING ACCEPT [222337:304355917]
:INPUT ACCEPT [222337:304355917]
:FORWARD ACCEPT [0:0]
:OUTPUT ACCEPT [180389:68900977]
:POSTROUTING ACCEPT [180389:68900977]
:KUBE-IPTABLES-HINT - [0:0]
:KUBE-KUBELET-CANARY - [0:0]
COMMIT
# Completed on Thu Nov 10 18:59:25 2022
# Generated by iptables-save v1.8.4 on Thu Nov 10 18:59:25 2022
*nat
:PREROUTING ACCEPT [0:0]
:INPUT ACCEPT [0:0]
:OUTPUT ACCEPT [221:13260]
:POSTROUTING ACCEPT [293:18021]
:KUBE-KUBELET-CANARY - [0:0]
:KUBE-MARK-DROP - [0:0]
:KUBE-MARK-MASQ - [0:0]
:KUBE-POSTROUTING - [0:0]
[0:0] -A PREROUTING -d 192.168.5.3/32 -p udp -m udp --dport 53 -j DNAT --to-destination 192.168.5.2:49336
[0:0] -A PREROUTING -d 192.168.5.3/32 -p tcp -m tcp --dport 53 -j DNAT --to-destination 192.168.5.2:56161
[82:5374] -A OUTPUT -d 192.168.5.3/32 -p udp -m udp --dport 53 -j DNAT --to-destination 192.168.5.2:49336
[0:0] -A OUTPUT -d 192.168.5.3/32 -p tcp -m tcp --dport 53 -j DNAT --to-destination 192.168.5.2:56161
[293:18021] -A POSTROUTING -m comment --comment "kubernetes postrouting rules" -j KUBE-POSTROUTING
[0:0] -A KUBE-MARK-DROP -j MARK --set-xmark 0x8000/0x8000
[0:0] -A KUBE-MARK-MASQ -j MARK --set-xmark 0x4000/0x4000
[293:18021] -A KUBE-POSTROUTING -m mark ! --mark 0x4000/0x4000 -j RETURN
[0:0] -A KUBE-POSTROUTING -j MARK --set-xmark 0x4000/0x0
[0:0] -A KUBE-POSTROUTING -m comment --comment "kubernetes service traffic requiring SNAT" -j MASQUERADE --random-fully
COMMIT
# Completed on Thu Nov 10 18:59:25 2022