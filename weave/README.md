IPerf Tests without encryption (`weave launch`):

```bash
/ # iperf -c 10.0.1.3 -i 1
------------------------------------------------------------
Client connecting to 10.0.1.3, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.0.1.2 port 35516 connected with 10.0.1.3 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0- 1.0 sec  75.9 MBytes   636 Mbits/sec
[  3]  1.0- 2.0 sec  86.4 MBytes   725 Mbits/sec
[  3]  2.0- 3.0 sec  86.6 MBytes   727 Mbits/sec
[  3]  3.0- 4.0 sec  88.8 MBytes   744 Mbits/sec
[  3]  4.0- 5.0 sec  94.8 MBytes   795 Mbits/sec
[  3]  5.0- 6.0 sec  91.6 MBytes   769 Mbits/sec
[  3]  6.0- 7.0 sec  86.4 MBytes   725 Mbits/sec
[  3]  7.0- 8.0 sec  77.5 MBytes   650 Mbits/sec
[  3]  8.0- 9.0 sec  69.5 MBytes   583 Mbits/sec
[  3]  9.0-10.0 sec  64.2 MBytes   539 Mbits/sec
[  3]  0.0-10.0 sec   822 MBytes   689 Mbits/sec
```

With encryption (`weave launch --password mypass`):

```bash
/ # iperf -c 10.0.2.30 -i 1
------------------------------------------------------------
Client connecting to 10.0.2.30, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.0.2.20 port 56496 connected with 10.0.2.30 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0- 1.0 sec  5.62 MBytes  47.2 Mbits/sec
[  3]  1.0- 2.0 sec  4.50 MBytes  37.7 Mbits/sec
[  3]  2.0- 3.0 sec  5.12 MBytes  43.0 Mbits/sec
[  3]  3.0- 4.0 sec  5.00 MBytes  41.9 Mbits/sec
[  3]  4.0- 5.0 sec  5.50 MBytes  46.1 Mbits/sec
[  3]  5.0- 6.0 sec  5.00 MBytes  41.9 Mbits/sec
[  3]  6.0- 7.0 sec  5.50 MBytes  46.1 Mbits/sec
[  3]  7.0- 8.0 sec  5.00 MBytes  41.9 Mbits/sec
[  3]  8.0- 9.0 sec  5.00 MBytes  41.9 Mbits/sec
[  3]  9.0-10.0 sec  5.88 MBytes  49.3 Mbits/sec
[  3]  0.0-10.1 sec  52.2 MBytes  43.5 Mbits/sec
```

**I'll abstain from testing Weave further for now.**
