IPerf Tests with tinc:

```bash
/ # iperf -c 10.1.96.2 -i 1
------------------------------------------------------------
Client connecting to 10.1.96.2, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.1.81.2 port 54462 connected with 10.1.96.2 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0- 1.0 sec  22.0 MBytes   185 Mbits/sec
[  3]  1.0- 2.0 sec  18.9 MBytes   158 Mbits/sec
[  3]  2.0- 3.0 sec  18.5 MBytes   155 Mbits/sec
[  3]  3.0- 4.0 sec  18.0 MBytes   151 Mbits/sec
[  3]  4.0- 5.0 sec  14.1 MBytes   118 Mbits/sec
[  3]  5.0- 6.0 sec  15.2 MBytes   128 Mbits/sec
[  3]  6.0- 7.0 sec  16.4 MBytes   137 Mbits/sec
[  3]  7.0- 8.0 sec  20.2 MBytes   170 Mbits/sec
[  3]  8.0- 9.0 sec  19.8 MBytes   166 Mbits/sec
[  3]  9.0-10.0 sec  19.0 MBytes   159 Mbits/sec
[  3]  0.0-10.0 sec   182 MBytes   153 Mbits/sec
```
