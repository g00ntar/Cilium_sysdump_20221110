Total: 245
TCP:   65 (estab 43, closed 7, orphaned 0, timewait 7)

Transport Total     IP        IPv6
RAW	  0         0         0        
UDP	  0         0         0        
TCP	  58        43        15       
INET	  58        43        15       
FRAG	  0         0         0        

State      Recv-Q Send-Q         Local Address:Port                 Peer Address:Port       Process                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
LISTEN     0      4096               127.0.0.1:10257                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:9234                      0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:10258                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:10259                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      128                  0.0.0.0:ssh                       0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:10010                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:9891                      0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:35493                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:10248                     0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096               127.0.0.1:sge-qmaster               0.0.0.0:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
ESTAB      0      0                  127.0.0.1:49294                   127.0.0.1:10250      
	 cubic wscale:7,7 rto:210 rtt:0.511/0.226 ato:40 mss:32768 pmtu:65535 rcvmss:1332 advmss:65483 cwnd:10 bytes_sent:5335 bytes_acked:5336 bytes_received:208601 segs_out:852 segs_in:1636 data_segs_out:18 data_segs_in:1619 send 5.13Gbps lastsnd:38620 lastrcv:38620 lastack:7880 pacing_rate 10.2Gbps delivery_rate 20.2Gbps delivered:19 app_limited busy:20ms rcv_rtt:1195.27 rcv_space:66193 rcv_ssthresh:1179043 minrtt:0.013                                                                       
ESTAB      0      0                  127.0.0.1:47452                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.179/0.134 ato:40 mss:32768 pmtu:65535 rcvmss:1378 advmss:65483 cwnd:18 bytes_sent:2354 bytes_acked:2355 bytes_received:1838 segs_out:32 segs_in:13 data_segs_out:27 data_segs_in:6 send 26.4Gbps lastsnd:100 lastrcv:10 lastack:10 pacing_rate 52.5Gbps delivery_rate 16.6Gbps delivered:28 app_limited rcv_space:65495 rcv_ssthresh:65495 minrtt:0.015                                                                                                                  
ESTAB      0      0                  127.0.0.1:42216                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:210 rtt:3.188/3.501 ato:40 mss:65483 pmtu:65535 rcvmss:65483 advmss:65483 cwnd:10 bytes_sent:176679 bytes_acked:176680 bytes_received:4670305 segs_out:1604 segs_in:1976 data_segs_out:688 data_segs_in:1772 send 1.64Gbps lastsnd:30140 lastrcv:1440 lastack:1440 pacing_rate 3.29Gbps delivery_rate 175Gbps delivered:689 app_limited busy:1670ms rcv_rtt:3.955 rcv_space:256124 rcv_ssthresh:3145015 minrtt:0.013                                                               
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:37044      
	 cubic wscale:7,7 rto:210 rtt:8.185/14.388 ato:40 mss:32768 pmtu:65535 rcvmss:980 advmss:65483 cwnd:10 bytes_sent:29753 bytes_acked:29753 bytes_received:9502 segs_out:211 segs_in:322 data_segs_out:207 data_segs_in:120 send 320Mbps lastsnd:13430 lastrcv:13430 lastack:13430 pacing_rate 641Mbps delivery_rate 52.4Gbps delivered:208 app_limited busy:1240ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.005                                                                                        
ESTAB      0      0                  127.0.0.1:37044                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:210 rtt:0.698/0.741 ato:40 mss:32768 pmtu:65535 rcvmss:2155 advmss:65483 cwnd:10 bytes_sent:9502 bytes_acked:9503 bytes_received:29753 segs_out:322 segs_in:212 data_segs_out:120 data_segs_in:207 send 3.76Gbps lastsnd:13430 lastrcv:13430 lastack:13430 pacing_rate 7.51Gbps delivery_rate 52.4Gbps delivered:121 app_limited busy:40ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.005                                                                                         
ESTAB      0      0                  127.0.0.1:42260                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:220 rtt:16.565/21.624 ato:40 mss:65483 pmtu:65535 rcvmss:16406 advmss:65483 cwnd:10 ssthresh:32 bytes_sent:98599 bytes_acked:98600 bytes_received:6755752 segs_out:3391 segs_in:3625 data_segs_out:1177 data_segs_in:3246 send 316Mbps lastsnd:1440 lastrcv:1440 lastack:1440 pacing_rate 632Mbps delivery_rate 262Gbps delivered:1178 app_limited busy:6770ms rcv_rtt:1036.78 rcv_space:635931 rcv_ssthresh:3145022 minrtt:0.003                                                  
ESTAB      0      0                  127.0.0.1:52796                   127.0.0.1:10010      
	 cubic wscale:7,7 rto:210 rtt:0.069/0.054 ato:40 mss:32768 pmtu:65535 rcvmss:536 advmss:65483 cwnd:18 bytes_sent:476 bytes_acked:477 bytes_received:350 segs_out:32 segs_in:24 data_segs_out:25 data_segs_in:19 send 68.4Gbps lastsnd:100 lastrcv:10 lastack:10 pacing_rate 136Gbps delivery_rate 20Gbps delivered:26 app_limited rcv_space:65495 rcv_ssthresh:65495 minrtt:0.031                                                                                                                        
ESTAB      0      0                  127.0.0.1:10010                   127.0.0.1:52796      
	 cubic wscale:7,7 rto:210 rtt:0.066/0.059 ato:40 mss:32768 pmtu:65535 rcvmss:536 advmss:65483 cwnd:10 bytes_sent:350 bytes_acked:350 bytes_received:476 segs_out:23 segs_in:32 data_segs_out:19 data_segs_in:25 send 39.7Gbps lastsnd:10 lastrcv:100 lastack:10 pacing_rate 78.7Gbps delivery_rate 11.4Gbps delivered:20 app_limited rcv_space:65483 rcv_ssthresh:65483 minrtt:0.013                                                                                                                     
ESTAB      0      0                  127.0.0.1:37048                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:220 rtt:10.599/16.045 ato:40 mss:32768 pmtu:65535 rcvmss:2624 advmss:65483 cwnd:10 bytes_sent:33747 bytes_acked:33748 bytes_received:3093675 segs_out:1429 segs_in:1652 data_segs_out:637 data_segs_in:1356 send 247Mbps lastsnd:3830 lastrcv:1440 lastack:1440 pacing_rate 495Mbps delivery_rate 131Gbps delivered:638 app_limited busy:2890ms rcv_rtt:2634.33 rcv_space:172946 rcv_ssthresh:3145021 minrtt:0.004                                                                 
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:42246      
	 cubic wscale:7,7 rto:210 rtt:3.371/6.344 ato:40 mss:32768 pmtu:65535 rcvmss:983 advmss:65483 cwnd:10 bytes_sent:29374 bytes_acked:29374 bytes_received:9431 segs_out:211 segs_in:319 data_segs_out:207 data_segs_in:118 send 778Mbps lastsnd:19060 lastrcv:19060 lastack:19060 pacing_rate 1.55Gbps delivery_rate 52.4Gbps delivered:208 app_limited busy:1170ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.005                                                                                        
ESTAB      0      0                  127.0.0.1:50668                   127.0.0.1:10250      
	 cubic wscale:7,7 rto:210 rtt:0.069/0.035 ato:40 mss:32768 pmtu:65535 rcvmss:1310 advmss:65483 cwnd:18 bytes_sent:2360 bytes_acked:2361 bytes_received:1770 segs_out:32 segs_in:12 data_segs_out:27 data_segs_in:6 send 68.4Gbps lastsnd:100 lastrcv:10 lastack:10 pacing_rate 136Gbps delivery_rate 52.4Gbps delivered:28 app_limited rcv_space:65495 rcv_ssthresh:65495 minrtt:0.009                                                                                                                   
SYN-SENT   0      1               192.168.5.15:56592                   10.43.0.1:https      
	 cubic rto:16000 backoff:4 mss:524 pmtu:1500 rcvmss:88 advmss:1460 cwnd:1 ssthresh:7 segs_out:5 lastsnd:3924040 lastrcv:3924040 lastack:3924040 unacked:1 retrans:1/4 lost:1 rcv_ssthresh:64240                                                                                                                                                                                                                                                                                                          
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:37048      
	 cubic wscale:7,7 rto:210 rtt:1.733/2.315 ato:40 mss:65483 pmtu:65535 rcvmss:3067 advmss:65483 cwnd:10 bytes_sent:3093675 bytes_acked:3093675 bytes_received:33747 segs_out:1651 segs_in:1429 data_segs_out:1356 data_segs_in:637 send 3.02Gbps lastsnd:1440 lastrcv:3830 lastack:1440 pacing_rate 6.04Gbps delivery_rate 262Gbps delivered:1357 app_limited busy:6550ms rcv_rtt:1 rcv_space:65483 rcv_ssthresh:65483 minrtt:0.003                                                                       
ESTAB      0      0                  127.0.0.1:52532                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:8.193/13.823 ato:40 mss:65483 pmtu:65535 rcvmss:16406 advmss:65483 cwnd:10 bytes_sent:814735 bytes_acked:814736 bytes_received:7791169 segs_out:6259 segs_in:6492 data_segs_out:3098 data_segs_in:5253 send 639Mbps lastsnd:1440 lastrcv:1440 lastack:1440 pacing_rate 1.28Gbps delivery_rate 262Gbps delivered:3099 app_limited busy:6810ms rcv_rtt:1 rcv_space:65495 rcv_ssthresh:65495 minrtt:0.002                                                                     
ESTAB      0      0                  127.0.0.1:44518                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.715/0.267 ato:40 mss:32768 pmtu:65535 rcvmss:3232 advmss:65483 cwnd:10 bytes_sent:7044 bytes_acked:7045 bytes_received:227596 segs_out:268 segs_in:791 data_segs_out:21 data_segs_in:780 send 3.67Gbps lastsnd:38620 lastrcv:38620 lastack:7880 pacing_rate 7.33Gbps delivery_rate 7.6Gbps delivered:22 app_limited busy:20ms rcv_rtt:1004.07 rcv_space:65495 rcv_ssthresh:65495 minrtt:0.029                                                                            
ESTAB      0      0                  127.0.0.1:52542                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.335/0.123 ato:40 mss:32768 pmtu:65535 rcvmss:4111 advmss:65483 cwnd:10 bytes_sent:6934 bytes_acked:6935 bytes_received:18411 segs_out:273 segs_in:163 data_segs_out:122 data_segs_in:160 send 7.83Gbps lastsnd:18080 lastrcv:18080 lastack:18080 pacing_rate 15.7Gbps delivery_rate 21.8Gbps delivered:123 app_limited busy:60ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.012                                                                                         
ESTAB      0      0                  127.0.0.1:42038                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:220 rtt:12.444/19.087 ato:40 mss:32768 pmtu:65535 rcvmss:16406 advmss:65483 cwnd:10 ssthresh:20 bytes_sent:225145 bytes_acked:225146 bytes_received:6981312 segs_out:6023 segs_in:6524 data_segs_out:2749 data_segs_in:6031 send 211Mbps lastsnd:3830 lastrcv:1440 lastack:1440 pacing_rate 253Mbps delivery_rate 87.4Gbps delivered:2750 app_limited busy:9070ms rcv_rtt:5.422 rcv_space:488201 rcv_ssthresh:3145022 minrtt:0.013                                                 
ESTAB      0      0                  127.0.0.1:37054                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:210 rtt:0.684/0.604 ato:40 mss:32768 pmtu:65535 rcvmss:2155 advmss:65483 cwnd:10 bytes_sent:9460 bytes_acked:9461 bytes_received:30163 segs_out:322 segs_in:215 data_segs_out:119 data_segs_in:210 send 3.83Gbps lastsnd:17180 lastrcv:17180 lastack:17180 pacing_rate 7.66Gbps delivery_rate 20.2Gbps delivered:120 app_limited busy:70ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.007                                                                                         
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:37064      
	 cubic wscale:7,7 rto:220 rtt:11.543/18.112 ato:40 mss:32768 pmtu:65535 rcvmss:973 advmss:65483 cwnd:10 bytes_sent:2693942 bytes_acked:2693942 bytes_received:49911 segs_out:1259 segs_in:1158 data_segs_out:1027 data_segs_in:482 send 227Mbps lastsnd:1440 lastrcv:3830 lastack:1390 pacing_rate 454Mbps delivery_rate 87.4Gbps delivered:1028 app_limited busy:7310ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.007                                                                                 
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:42264      
	 cubic wscale:7,7 rto:210 rtt:0.122/0.082 ato:40 mss:65483 pmtu:65535 rcvmss:13008 advmss:65483 cwnd:20 ssthresh:19 bytes_sent:6859672 bytes_acked:6859672 bytes_received:1290990 segs_out:18020 segs_in:14965 data_segs_out:16696 data_segs_in:8685 send 85.9Gbps lastsnd:3300 lastrcv:3300 lastack:3300 pacing_rate 102Gbps delivery_rate 105Gbps delivered:16697 app_limited busy:3280ms rcv_rtt:348.668 rcv_space:97716 rcv_ssthresh:1899999 minrtt:0.005                                            
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:42216      
	 cubic wscale:7,7 rto:220 rtt:13.363/20.238 ato:40 mss:65483 pmtu:65535 rcvmss:4052 advmss:65483 cwnd:10 bytes_sent:4670305 bytes_acked:4670305 bytes_received:176679 segs_out:1975 segs_in:1604 data_segs_out:1772 data_segs_in:688 send 392Mbps lastsnd:1440 lastrcv:30140 lastack:1440 pacing_rate 784Mbps delivery_rate 30.8Gbps delivered:1773 app_limited busy:5010ms rcv_rtt:2359.86 rcv_space:66049 rcv_ssthresh:1179043 minrtt:0.011                                                            
ESTAB      0      0                  127.0.0.1:45698                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:8.104/13.102 ato:40 mss:32768 pmtu:65535 rcvmss:16406 advmss:65483 cwnd:10 bytes_sent:14196 bytes_acked:14197 bytes_received:603023 segs_out:196 segs_in:222 data_segs_out:137 data_segs_in:183 send 323Mbps lastsnd:140 lastrcv:140 lastack:140 pacing_rate 647Mbps delivery_rate 23.8Gbps delivered:138 app_limited busy:330ms rcv_rtt:12.119 rcv_space:148659 rcv_ssthresh:3144729 minrtt:0.011                                                                         
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:37054      
	 cubic wscale:7,7 rto:210 rtt:4.649/8.524 ato:40 mss:32768 pmtu:65535 rcvmss:974 advmss:65483 cwnd:10 bytes_sent:30163 bytes_acked:30163 bytes_received:9460 segs_out:214 segs_in:322 data_segs_out:210 data_segs_in:119 send 564Mbps lastsnd:17180 lastrcv:17180 lastack:17180 pacing_rate 1.13Gbps delivery_rate 131Gbps delivered:211 app_limited busy:1130ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.002                                                                                         
ESTAB      0      0                  127.0.0.1:52220                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.032/0.032 ato:40 mss:32768 pmtu:65535 rcvmss:691 advmss:65483 cwnd:10 bytes_sent:829 bytes_acked:830 bytes_received:4140 segs_out:253 segs_in:249 data_segs_out:6 data_segs_in:5 send 81.9Gbps lastsnd:3435950 lastrcv:3435950 lastack:10440 pacing_rate 160Gbps delivery_rate 13.1Gbps delivered:7 app_limited rcv_rtt:1 rcv_space:65495 rcv_ssthresh:65495 minrtt:0.008                                                                                                
CLOSE-WAIT 0      0                  127.0.0.1:45808                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.065/0.039 ato:40 mss:32768 pmtu:65535 rcvmss:1378 advmss:65483 cwnd:10 bytes_sent:1833 bytes_acked:1834 bytes_received:1861 segs_out:10 segs_in:17 data_segs_out:3 data_segs_in:12 send 40.3Gbps lastsnd:40410 lastrcv:40400 lastack:9800 pacing_rate 80.4Gbps delivery_rate 14.6Gbps delivered:4 app_limited rcv_space:65495 rcv_ssthresh:65495 minrtt:0.018                                                                                                            
ESTAB      0      0               192.168.5.15:56852                192.168.5.15:6443       
	 cubic wscale:7,7 rto:210 rtt:0.306/0.092 ato:40 mss:32768 pmtu:65535 rcvmss:1377 advmss:65483 cwnd:10 bytes_sent:20669 bytes_acked:20670 bytes_received:17992 segs_out:1379 segs_in:691 data_segs_out:689 data_segs_in:688 send 8.57Gbps lastsnd:1120 lastrcv:1120 lastack:1120 pacing_rate 17.1Gbps delivery_rate 13.8Gbps delivered:690 app_limited busy:120ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.012                                                                                        
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:42038      
	 cubic wscale:7,7 rto:210 rtt:7.108/12.83 ato:40 mss:65483 pmtu:65535 rcvmss:2629 advmss:65483 cwnd:10 ssthresh:63 bytes_sent:6981312 bytes_acked:6981312 bytes_received:225145 segs_out:6523 segs_in:6023 data_segs_out:6031 data_segs_in:2749 send 737Mbps lastsnd:1440 lastrcv:3830 lastack:1390 pacing_rate 1.47Gbps delivery_rate 262Gbps delivered:6032 app_limited busy:18930ms rcv_rtt:1 rcv_space:65483 rcv_ssthresh:65483 minrtt:0.01                                                          
ESTAB      0      0                  127.0.0.1:47458                   127.0.0.1:6443       
	 cubic wscale:7,7 rto:210 rtt:0.138/0.119 ato:40 mss:32768 pmtu:65535 rcvmss:1378 advmss:65483 cwnd:18 bytes_sent:4265 bytes_acked:4266 bytes_received:3386 segs_out:35 segs_in:15 data_segs_out:30 data_segs_in:8 send 34.2Gbps lastsnd:100 lastrcv:10 lastack:10 pacing_rate 68.2Gbps delivery_rate 38.1Gbps delivered:31 app_limited busy:10ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.011                                                                                                        
ESTAB      0      0                  127.0.0.1:42264                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:210 rtt:0.397/0.275 ato:40 mss:65483 pmtu:65535 rcvmss:4118 advmss:65483 cwnd:29 ssthresh:29 bytes_sent:1291484 bytes_retrans:494 bytes_acked:1290991 bytes_received:6859672 segs_out:14965 segs_in:18021 data_segs_out:8685 data_segs_in:16696 send 38.3Gbps lastsnd:3300 lastrcv:3300 lastack:3300 pacing_rate 45.9Gbps delivery_rate 28.3Gbps delivered:8686 app_limited busy:1410ms retrans:0/1 dsack_dups:1 rcv_rtt:296.303 rcv_space:149084 rcv_ssthresh:3145024 minrtt:0.005
ESTAB      0      0                  127.0.0.1:sge-qmaster             127.0.0.1:42260      
	 cubic wscale:7,7 rto:210 rtt:6.972/12.152 ato:40 mss:65483 pmtu:65535 rcvmss:983 advmss:65483 cwnd:10 ssthresh:20 bytes_sent:6755752 bytes_acked:6755752 bytes_received:98599 segs_out:3624 segs_in:3391 data_segs_out:3246 data_segs_in:1177 send 751Mbps lastsnd:1440 lastrcv:1440 lastack:1440 pacing_rate 902Mbps delivery_rate 524Gbps delivered:3247 app_limited busy:23710ms rcv_rtt:82958.1 rcv_space:65783 rcv_ssthresh:1179043 minrtt:0.003                                                   
ESTAB      0      0               192.168.5.15:ssh                   192.168.5.2:56165      
	 cubic rto:210 rtt:1.03/0.684 ato:40 mss:1460 pmtu:1500 rcvmss:1460 advmss:1460 cwnd:10 ssthresh:51 bytes_sent:6397377 bytes_acked:6397377 bytes_received:322141 segs_out:8882 segs_in:11322 data_segs_out:8276 data_segs_in:3632 send 113Mbps lastsnd:1440 lastrcv:1440 lastack:1440 pacing_rate 227Mbps delivery_rate 236Mbps delivered:8277 app_limited busy:6940ms rcv_rtt:306825 rcv_space:64341 rcv_ssthresh:540036 minrtt:0.074                                                                   
ESTAB      0      0                  127.0.0.1:42246                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:210 rtt:0.491/0.261 ato:40 mss:32768 pmtu:65535 rcvmss:2155 advmss:65483 cwnd:10 bytes_sent:9431 bytes_acked:9432 bytes_received:29374 segs_out:319 segs_in:212 data_segs_out:118 data_segs_in:207 send 5.34Gbps lastsnd:19060 lastrcv:19060 lastack:19060 pacing_rate 10.7Gbps delivery_rate 23.8Gbps delivered:119 app_limited busy:40ms rcv_space:65495 rcv_ssthresh:65495 minrtt:0.005                                                                                         
ESTAB      0      0                  127.0.0.1:37064                   127.0.0.1:sge-qmaster
	 cubic wscale:7,7 rto:220 rtt:13.55/20.027 ato:40 mss:32768 pmtu:65535 rcvmss:16406 advmss:65483 cwnd:10 ssthresh:20 bytes_sent:49911 bytes_acked:49912 bytes_received:2693942 segs_out:1158 segs_in:1260 data_segs_out:482 data_segs_in:1027 send 193Mbps lastsnd:3830 lastrcv:1440 lastack:1440 pacing_rate 232Mbps delivery_rate 87.4Gbps delivered:483 app_limited busy:3240ms rcv_rtt:1 rcv_space:65495 rcv_ssthresh:65495 minrtt:0.004                                                             
LISTEN     0      128                     [::]:ssh                          [::]:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096                       *:10250                           *:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
LISTEN     0      4096                       *:6443                            *:*          
	 cubic cwnd:10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:52532      
	 cubic wscale:7,7 rto:210 rtt:6.423/11.559 ato:40 mss:32768 pmtu:65535 rcvmss:5705 advmss:65483 cwnd:10 bytes_sent:7791169 bytes_acked:7791169 bytes_received:814735 segs_out:6491 segs_in:6259 data_segs_out:5253 data_segs_in:3098 send 408Mbps lastsnd:1440 lastrcv:1440 lastack:1390 pacing_rate 816Mbps delivery_rate 87.4Gbps delivered:5254 app_limited busy:10640ms rcv_rtt:56098.9 rcv_space:66842 rcv_ssthresh:1179042 minrtt:0.009                                                            
TIME-WAIT  0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45728      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:47452      
	 cubic wscale:7,7 rto:210 rtt:5.545/10.714 ato:40 mss:32768 pmtu:65535 rcvmss:991 advmss:65483 cwnd:10 bytes_sent:1838 bytes_acked:1838 bytes_received:2354 segs_out:12 segs_in:32 data_segs_out:6 data_segs_in:27 send 473Mbps lastsnd:10 lastrcv:100 lastack:10 pacing_rate 945Mbps delivery_rate 4.6Gbps delivered:7 app_limited busy:60ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.057                                                                                                            
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:47458      
	 cubic wscale:7,7 rto:210 rtt:5.664/10.907 ato:40 mss:32768 pmtu:65535 rcvmss:1016 advmss:65483 cwnd:10 bytes_sent:3386 bytes_acked:3386 bytes_received:4265 segs_out:14 segs_in:35 data_segs_out:8 data_segs_in:30 send 463Mbps lastsnd:10 lastrcv:100 lastack:10 pacing_rate 926Mbps delivery_rate 29.1Gbps delivered:9 app_limited busy:60ms rcv_rtt:1 rcv_space:65483 rcv_ssthresh:65483 minrtt:0.009                                                                                                
FIN-WAIT-2 0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45808      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
ESTAB      0      0      [::ffff:192.168.5.15]:6443        [::ffff:192.168.5.15]:56852      
	 cubic wscale:7,7 rto:210 rtt:0.069/0.031 ato:40 mss:32768 pmtu:65535 rcvmss:998 advmss:65483 cwnd:10 bytes_sent:17992 bytes_acked:17992 bytes_received:20669 segs_out:690 segs_in:1379 data_segs_out:688 data_segs_in:689 send 38Gbps lastsnd:1120 lastrcv:1120 lastack:1120 pacing_rate 75.6Gbps delivery_rate 37.4Gbps delivered:689 app_limited busy:90ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.007                                                                                            
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:44518      
	 cubic wscale:7,7 rto:210 rtt:0.04/0.035 ato:40 mss:32768 pmtu:65535 rcvmss:1016 advmss:65483 cwnd:46 ssthresh:99 bytes_sent:227596 bytes_acked:227596 bytes_received:7044 segs_out:790 segs_in:268 data_segs_out:780 data_segs_in:21 send 301Gbps lastsnd:38620 lastrcv:38620 lastack:38620 pacing_rate 592Gbps delivery_rate 87.4Gbps delivered:781 app_limited busy:60ms rcv_rtt:1 rcv_space:65483 rcv_ssthresh:65483 minrtt:0.003                                                                    
ESTAB      0      0                      [::1]:45152                       [::1]:6443       
	 cubic wscale:7,7 rto:220 rtt:10.078/15.189 ato:40 mss:65464 pmtu:65536 rcvmss:16406 advmss:65464 cwnd:10 bytes_sent:104332 bytes_acked:104333 bytes_received:3270767 segs_out:4191 segs_in:4497 data_segs_out:1915 data_segs_in:4325 send 520Mbps lastsnd:1440 lastrcv:1440 lastack:1390 pacing_rate 1.04Gbps delivery_rate 74.8Gbps delivered:1916 app_limited busy:4510ms rcv_rtt:857.719 rcv_space:109517 rcv_ssthresh:1963335 minrtt:0.008                                                          
ESTAB      0      0                      [::1]:6443                        [::1]:45152      
	 cubic wscale:7,7 rto:210 rtt:1.018/1.048 ato:40 mss:65464 pmtu:65536 rcvmss:1197 advmss:65464 cwnd:10 ssthresh:30 bytes_sent:3270767 bytes_acked:3270767 bytes_received:104332 segs_out:4496 segs_in:4191 data_segs_out:4325 data_segs_in:1915 send 5.14Gbps lastsnd:1440 lastrcv:1440 lastack:1440 pacing_rate 10.3Gbps delivery_rate 175Gbps delivered:4326 app_limited busy:3900ms rcv_rtt:517800 rcv_space:65743 rcv_ssthresh:1177719 minrtt:0.01                                                   
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45698      
	 cubic wscale:7,7 rto:210 rtt:1.042/1.37 ato:40 mss:65483 pmtu:65535 rcvmss:3849 advmss:65483 cwnd:10 ssthresh:34 bytes_sent:603023 bytes_acked:603023 bytes_received:14196 segs_out:221 segs_in:196 data_segs_out:183 data_segs_in:137 send 5.03Gbps lastsnd:140 lastrcv:140 lastack:140 pacing_rate 10Gbps delivery_rate 65.5Gbps delivered:184 app_limited busy:120ms rwnd_limited:10ms(8.3%) rcv_space:65483 rcv_ssthresh:65483 minrtt:0.002                                                         
TIME-WAIT  0      0         [::ffff:127.0.0.1]:10250          [::ffff:127.0.0.1]:58432      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
ESTAB      0      0         [::ffff:127.0.0.1]:10250          [::ffff:127.0.0.1]:50668      
	 cubic wscale:7,7 rto:210 rtt:5.593/10.867 ato:40 mss:32768 pmtu:65535 rcvmss:994 advmss:65483 cwnd:10 bytes_sent:1770 bytes_acked:1770 bytes_received:2360 segs_out:11 segs_in:32 data_segs_out:6 data_segs_in:27 send 469Mbps lastsnd:10 lastrcv:100 lastack:10 pacing_rate 937Mbps delivery_rate 21.8Gbps delivered:7 app_limited busy:60ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.012                                                                                                           
TIME-WAIT  0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45738      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
TIME-WAIT  0      0         [::ffff:127.0.0.1]:10250          [::ffff:127.0.0.1]:58472      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
TIME-WAIT  0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45712      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
ESTAB      0      0         [::ffff:127.0.0.1]:10250          [::ffff:127.0.0.1]:49294      
	 cubic wscale:7,7 rto:210 rtt:0.013/0.01 ato:40 mss:65483 pmtu:65535 rcvmss:994 advmss:65483 cwnd:27 ssthresh:27 bytes_sent:208601 bytes_acked:208601 bytes_received:5335 segs_out:1635 segs_in:852 data_segs_out:1619 data_segs_in:18 send 1.09Tbps lastsnd:38620 lastrcv:38620 lastack:7880 pacing_rate 1.22Tbps delivery_rate 262Gbps delivered:1620 app_limited busy:80ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.002                                                                            
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:52542      
	 cubic wscale:7,7 rto:210 rtt:1.141/2.174 ato:40 mss:32768 pmtu:65535 rcvmss:974 advmss:65483 cwnd:10 bytes_sent:18411 bytes_acked:18411 bytes_received:6934 segs_out:162 segs_in:273 data_segs_out:160 data_segs_in:122 send 2.3Gbps lastsnd:18080 lastrcv:18080 lastack:18080 pacing_rate 4.59Gbps delivery_rate 26.2Gbps delivered:161 app_limited busy:380ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.009                                                                                         
TIME-WAIT  0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:45754      
	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
ESTAB      0      0         [::ffff:127.0.0.1]:6443           [::ffff:127.0.0.1]:52220      
	 cubic wscale:7,7 rto:210 rtt:5.157/10.244 ato:40 mss:32768 pmtu:65535 rcvmss:536 advmss:65483 cwnd:10 bytes_sent:4140 bytes_acked:4140 bytes_received:829 segs_out:248 segs_in:253 data_segs_out:5 data_segs_in:6 send 508Mbps lastsnd:3435960 lastrcv:3435960 lastack:125010 pacing_rate 1.02Gbps delivery_rate 43.7Gbps delivered:6 app_limited busy:60ms rcv_space:65483 rcv_ssthresh:65483 minrtt:0.006                                                                                             