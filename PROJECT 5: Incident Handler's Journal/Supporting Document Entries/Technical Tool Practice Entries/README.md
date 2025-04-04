## 💻 Entry 2: Capturing Network Traffic with tcpdump

### 🔍 Activity Overview  
In this lab, I practiced using `tcpdump` on a Linux system to capture live network data. I learned how to identify network interfaces, apply filters, and save packet data for analysis.

### 🛠️ Steps Taken  
1. List available interfaces using `ifconfig` and `tcpdump -D`.  
2. Captured five packets with `tcpdump -i eth0 -v -c5`.  
3. Used `curl` to simulate HTTP traffic.  
4. Captured port 80 traffic and saved it to a file with `-w capture.pcap`.  
5. Read the file using `tcpdump -r` in normal and hex formats.  
6. Practiced filtering and interpreting network traffic.

## 🧪 Entry 3: Packet Analysis with Wireshark

### 🔍 Activity Overview  
I explored a packet capture file using Wireshark to understand how protocols work across different layers. I used filters to focus on specific traffic types and explored packet details like IPs, protocols, ports, and payloads.

### 🛠️ Steps Taken  
1. Opened a `.pcap` file in Wireshark and examined packet summaries.  
2. Applied filters like `ip.addr ==` and `tcp.port ==` to narrow results.  
3. Explored individual packets layer by layer: Frame → Ethernet → IP → TCP.  
4. Viewed and interpreted DNS lookups and HTTP request payloads.  
5. Used `tcp contains "curl"` to identify packets with specific content.  
6. Practiced reading TCP flags, TTL values, and sequence numbers.
