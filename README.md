# Cisco-Packet-Tracer-project-18-ECMP-Lab-Equal-Cost-Multi-Path-Routing-Simulation-with-0.5-Link-Metrics-
I’m excited to share a focused networking project – ECMP‑Lab – built in Cisco Packet Tracer. The simulation uses uniform link metrics of 0.5 across a small topology (6 links on one segment, 5 on another) to explore Equal‑Cost Multi‑Path (ECMP) routing.

![image alt](https://github.com/Sameera54321/ECMP-Lab-Equal-Cost-Multi-Path-Routing-Simulation-with-0.5-Link-Metrics-/blob/main/6.jpg?raw=true)

## 📌 Summary

### ECMP‑Lab is a minimalist Cisco Packet Tracer simulation that demonstrates Equal‑Cost Multi‑Path (ECMP) routing using identical link metrics (0.5). The topology consists of multiple interconnected routers or switches where every link has the same cost, forcing the routing protocol to install multiple equal paths to destinations.

### The project explores:

    OSPF cost configuration (or EIGRP metric) – setting all links to 0.5

    Verification of ECMP via show ip route (multiple next‑hops)

    Load balancing behaviour (per‑packet or per‑destination)

    Impact of changing a single link’s metric to break ECMP

### This is a lightweight, easy‑to‑understand lab for CCNA candidates and instructors.

## ✨ Features

    ✅ Uniform link metric – 0.5 on all connections (OSPF cost or EIGRP metric)

    ✅ ECMP demonstration – multiple equal‑cost routes to the same destination

    ✅ Routing protocol – OSPF (or EIGRP) configured on all routers

    ✅ Traffic analysis – use traceroute and debug commands to see load balancing

    ✅ Full Packet Tracer file (.pkt) – ready to open and test

    ✅ Documentation – link metric table, routing tables before/after ECMP

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router configurations (OSPF cost / EIGRP metric)

    Wireshark (optional) – for traffic capture analysis

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more routers or links to create larger ECMP scenarios.

    Experiment with different metric values to see how routing changes.

    Include packet capture files showing load balancing.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
