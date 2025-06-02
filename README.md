# CCNA Lab 01 – Basic LAN and Static IP Addressing

## 🧠 Objective
Build a simple local area network using two PCs and one switch. Assign static IP addresses and verify basic connectivity using ping.

## 🧱 Topology
- 2x PCs (PC1 and PC2)
- 1x Switch
- Copper straight-through cables

## 🛠️ Configuration Steps
1. Connect both PCs to the switch
2. Assign static IP addresses:
   - PC1: 192.168.1.10 / 255.255.255.0
   - PC2: 192.168.1.20 / 255.255.255.0
3. Verify connectivity using the `ping` command

## ✅ Expected Result
- Successful ping from PC1 to PC2
- Both PCs are in the same subnet and can communicate via the switch

## 📸 Screenshot
![image](https://github.com/user-attachments/assets/35a846a5-b57e-4350-88b3-4e8b1cf6de66)

## 📂 Files
- `.pkt` file (Packet Tracer)
- Screenshot of the ping result
- This README

## 🧩 Optional Challenges
- Add a third PC and test communication
- Change the subnet to 255.255.255.128 and see if PCs can still communicate
