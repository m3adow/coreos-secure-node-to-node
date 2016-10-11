IPerf Tests without encryption (base flannel config):

```bash
/ # iperf -c 10.1.20.2 -i 1
------------------------------------------------------------
Client connecting to 10.1.20.2, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.1.61.2 port 36186 connected with 10.1.20.2 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0- 1.0 sec  62.9 MBytes   527 Mbits/sec
[  3]  1.0- 2.0 sec  82.5 MBytes   692 Mbits/sec
[  3]  2.0- 3.0 sec  84.6 MBytes   710 Mbits/sec
[  3]  3.0- 4.0 sec  85.4 MBytes   716 Mbits/sec
[  3]  4.0- 5.0 sec  83.8 MBytes   703 Mbits/sec
[  3]  5.0- 6.0 sec  80.8 MBytes   677 Mbits/sec
[  3]  6.0- 7.0 sec  80.6 MBytes   676 Mbits/sec
[  3]  7.0- 8.0 sec  79.1 MBytes   664 Mbits/sec
[  3]  8.0- 9.0 sec  81.8 MBytes   686 Mbits/sec
[  3]  9.0-10.0 sec  73.6 MBytes   618 Mbits/sec
[  3]  0.0-10.0 sec   795 MBytes   667 Mbits/sec
```
