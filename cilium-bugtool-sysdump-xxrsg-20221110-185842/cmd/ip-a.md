1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP group default qlen 1000
    link/ether 52:55:55:d4:b2:33 brd ff:ff:ff:ff:ff:ff
    inet 192.168.5.15/24 scope global eth0
       valid_lft forever preferred_lft forever
    inet6 fec0::5055:55ff:fed4:b233/64 scope site dynamic mngtmpaddr 
       valid_lft 86316sec preferred_lft 14316sec
    inet6 fe80::5055:55ff:fed4:b233/64 scope link 
       valid_lft forever preferred_lft forever
