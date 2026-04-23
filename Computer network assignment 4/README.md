Experiment 4 :

Objective : Implement error detection and correction mechanisms using block coding and Cyclic Redundancy Check (CRC). Simulate a communication system in Cisco Packet Tracer to demonstrate how errors are detected and corrected during data transmission.

Components required : Hardware Components (in Cisco Packet Tracer): • 1 Switch • 2 PCs • Cables (Copper Straight Through)

Block Coding • Data is divided into blocks • Extra bits (parity bits) are added • Helps in: o Error detection o Single-bit error correction Example: Data: 1011 → Sent as 1011 + parity bit

CRC (Cyclic Redundancy Check) • Uses a generator polynomial • Sender adds CRC bits • Receiver recalculates and compares If mismatch → Error detected

Basic Setup Steps:

Build topology with: o 1 switch + 2 PCs
Assign IPs (same network)
Use Simulation Mode
Start pings: o PC0 → PC1
Introduce error
Correct error
Observe Observation in Simulation Mode
Watch:

Packet success → No error Packet drop → Error detected Expected Output Normal ping → success Error condition → packet drop Recovery after fixing link
