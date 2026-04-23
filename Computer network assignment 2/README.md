Experiment 2 :

Objective : Create a network simulation to demonstrate packet switching and circuit switching. Compare the performance and efficiency of both methods by simulating a series of data transmission scenarios

Components required : Hardware Components (in Cisco Packet Tracer): • 2 Switches • 1 Router (optional) • 4–6 PCs • Cables (Copper Straight Through)

Packet Switching • Data is broken into small packets • Each packet may take different paths • Packets are reassembled at destination • Used in modern networks (Internet) Efficient No dedicated path required Possible delay & packet loss

Circuit Switching • A dedicated path is established before communication • Resources are reserved for entire session • Example: Traditional telephone network Stable connection Wastes bandwidth (even when idle)

Basic Setup (TCP) Packet Switching Simulation Steps:

Build topology with: o 2 switches + 4 PCs
Assign IPs (same network)
Use Simulation Mode
Start multiple pings: o PC0 → PC3 o PC1 → PC2
Observation: • Packets move simultaneously • Share same links • Possible delay under load

Circuit Switching Simulation

Steps:

Allow only one ping at a time
Stop other traffic
Send:
Observation: • No interference • Smooth communication • No packet collision
