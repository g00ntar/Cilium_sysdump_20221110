Module                  Size  Used by
xfrm_user              45056  0
ip_set                 53248  0
xfrm_algo              16384  1 xfrm_user
tcp_diag               16384  0
udp_diag               20480  0
inet_diag              28672  2 tcp_diag,udp_diag
ip6table_mangle        16384  1
iptable_mangle         16384  1
br_netfilter           32768  0
binfmt_misc            24576  1
ext4                  905216  1
crc16                  16384  1 ext4
mbcache                24576  1 ext4
jbd2                  184320  1 ext4
overlay               131072  5
xt_tcpudp              16384  4
xt_nat                 16384  4
xt_multiport           16384  0
xt_mark                16384  10
xt_conntrack           16384  1
xt_comment             16384  7
xt_addrtype            16384  0
xt_MASQUERADE          16384  2
nf_tables             229376  0
nfnetlink              20480  2 nf_tables,ip_set
ip6table_filter        16384  1
iptable_filter         16384  1
ip6table_nat           16384  1
iptable_nat            16384  1
nf_nat                 53248  4 ip6table_nat,xt_nat,iptable_nat,xt_MASQUERADE
nf_conntrack          163840  4 xt_conntrack,nf_nat,xt_nat,xt_MASQUERADE
nf_defrag_ipv6         24576  1 nf_conntrack
nf_defrag_ipv4         16384  1 nf_conntrack
crc32c_generic         16384  3
libcrc32c              16384  3 nf_conntrack,nf_nat,nf_tables
ip6_tables             32768  3 ip6table_filter,ip6table_nat,ip6table_mangle
ip_tables              32768  3 iptable_filter,iptable_nat,iptable_mangle
x_tables               45056  16 ip6table_filter,xt_conntrack,iptable_filter,ip6table_nat,xt_multiport,xt_tcpudp,xt_addrtype,xt_nat,xt_comment,ip6_tables,ip_tables,iptable_nat,ip6table_mangle,xt_MASQUERADE,iptable_mangle,xt_mark
veth                   32768  0
bridge                278528  1 br_netfilter
stp                    20480  1 bridge
llc                    20480  2 bridge,stp
tap                    32768  0
tun                    61440  0
fuse                  167936  4
hid_generic            16384  0
usbkbd                 20480  0
usbmouse               16384  0
usbhid                 36864  0
hid                   135168  2 usbhid,hid_generic
ipv6                  593920  105 bridge,br_netfilter,udp_diag,ip6table_mangle
af_packet              61440  0
aes_ce_blk             36864  0
crypto_simd            24576  1 aes_ce_blk
cryptd                 32768  1 crypto_simd
aes_ce_cipher          20480  1 aes_ce_blk
crct10dif_ce           20480  1
evdev                  32768  3
ghash_ce               24576  0
sha3_ce                20480  0
sha3_generic           16384  1 sha3_ce
sha512_ce              24576  0
sha512_arm64           20480  1 sha512_ce
sha2_ce                24576  0
sha256_arm64           28672  1 sha2_ce
sha1_ce                20480  0
efi_pstore             16384  0
button                 16384  0
virtio_rng             16384  0
rng_core               24576  1 virtio_rng
qemu_fw_cfg            20480  0
efivarfs               20480  1
vfat                   28672  0
fat                    94208  1 vfat
isofs                  49152  2
cdrom                  49152  1 isofs
virtio_net             53248  0
net_failover           24576  1 virtio_net
failover               20480  1 net_failover
virtio_blk             24576  3
xhci_pci               24576  0
xhci_hcd              253952  1 xhci_pci
virtio_mmio            24576  0
simpledrm              16384  0
drm_kms_helper        299008  3 simpledrm
cfbfillrect            16384  1 drm_kms_helper
syscopyarea            16384  1 drm_kms_helper
cfbimgblt              16384  1 drm_kms_helper
sysfillrect            16384  1 drm_kms_helper
sysimgblt              16384  1 drm_kms_helper
fb_sys_fops            16384  1 drm_kms_helper
cfbcopyarea            16384  1 drm_kms_helper
drm                   618496  3 drm_kms_helper,simpledrm
fb                    114688  72 drm_kms_helper,drm
i2c_core               98304  2 drm_kms_helper,drm
drm_panel_orientation_quirks    24576  1 drm
backlight              24576  2 drm_kms_helper,drm
firmware_class         32768  1 drm
usb_storage            81920  0
usbcore               294912  6 xhci_hcd,usbhid,usb_storage,usbkbd,usbmouse,xhci_pci
usb_common             20480  2 xhci_hcd,usbcore
sd_mod                 53248  0
t10_pi                 16384  1 sd_mod
scsi_mod              217088  2 sd_mod,usb_storage
squashfs               53248  1
loop                   45056  2
