# Computer Networks Lab (CN)

**Name:** Arnav Band  
**PRN:** 24070521223

---

## Experiments

| # | Experiment | Source File(s) |
|---|---|---|
| 01 | Network Topology & File Sharing | [Experiment 1A](./Exp-01-Topology-File-Sharing/Experiment%20%201A/), [Experiment 1B](./Exp-01-Topology-File-Sharing/Experiment%20%201B/) |
| 02 | TCP Echo Server | [`server1223.c`](./Exp-02-TCP-Server/server1223.c) |
| 03 | TCP Echo Client | [`client1223.c`](./Exp-03-TCP-Client/client1223.c) |
| 04 | UDP Server | [`server_udp223.c`](./Exp-04-UDP-Server/server_udp223.c) |
| 05 | UDP Client | [`client_udp_223.c`](./Exp-05-UDP-Client/client_udp_223.c) |
| 06 | DNS Packet Analysis | [Exp-06](./Exp-06-DNS-Packet-Analysis/) |
| 07 | DNS & HTTP Packet Analysis | [Exp-07](./Exp-07-DNS-HTTP-Packet-Analysis/) |
| 08 | Sliding Window Protocol | [`sliding_window223.c`](./Exp-08-Sliding-Window-Protocol/sliding_window223.c) |
| 09 | Traffic Shaping (Leaky & Token Bucket) | [`exp9_223.c`](./Exp-09-Traffic-Shaping/exp9_223.c), [`exp9_2_223.c`](./Exp-09-Traffic-Shaping/exp9_2_223.c) |
| 10 | Distance Vector Routing | [`exp10_223.c`](./Exp-10-Distance-Vector-Routing/exp10_223.c) |

---

## How to Compile & Run

All programs are written in C and use Linux socket APIs.

```bash
# Example: TCP Server
gcc server1223.c -o server
./server

# Example: TCP Client (in a separate terminal)
gcc client1223.c -o client
./client
```

---

## Repository Structure

```
cn/
├── Exp-01-Topology-File-Sharing/
│   ├── Experiment 1A/
│   └── Experiment 1B/
├── Exp-02-TCP-Server/
│   └── server1223.c
├── Exp-03-TCP-Client/
│   └── client1223.c
├── Exp-04-UDP-Server/
│   └── server_udp223.c
├── Exp-05-UDP-Client/
│   └── client_udp_223.c
├── Exp-06-DNS-Packet-Analysis/
├── Exp-07-DNS-HTTP-Packet-Analysis/
├── Exp-08-Sliding-Window-Protocol/
│   └── sliding_window223.c
├── Exp-09-Traffic-Shaping/
│   ├── exp9_223.c
│   └── exp9_2_223.c
├── Exp-10-Distance-Vector-Routing/
│   └── exp10_223.c
└── README.md
```
