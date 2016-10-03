IPerf Tests without encryption (`weave launch`):

```bash
/ # iperf -c 10.0.1.1
------------------------------------------------------------
Client connecting to 10.0.1.1, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.0.1.2 port 52698 connected with 10.0.1.1 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0-10.0 sec   647 MBytes   542 Mbits/sec
```

With encryption (`weave launch --password mypass`):

```bash
/ # iperf -c 10.0.1.1
------------------------------------------------------------
Client connecting to 10.0.1.1, TCP port 5001
TCP window size: 45.0 KByte (default)
------------------------------------------------------------
[  3] local 10.0.1.2 port 52634 connected with 10.0.1.1 port 5001
[ ID] Interval       Transfer     Bandwidth
[  3]  0.0-10.1 sec  49.6 MBytes  41.4 Mbits/sec
```

**I'll abstain from testing Weave further for now.**
