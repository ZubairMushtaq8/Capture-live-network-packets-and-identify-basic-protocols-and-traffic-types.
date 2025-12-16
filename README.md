# Capture-live-network-packets-and-identify-basic-protocols-and-traffic-types.
This work demonstrates the use of Wireshark for capturing and analyzing live network traffic. It helps in understanding how different network protocols operate during routine network activities.

**Objective**

Capture live network packets and identify basic network protocols and traffic types using Wireshark.

**Tools Used**

Wireshark (Free network protocol analyzer)

Operating System: Windows

**Deliverables**

Packet capture file (.pcap)

Short report summarizing identified protocols and packet details

**🔹 Steps Performed
1️⃣ Start Packet Capture**

Opened Wireshark.
Selected the active network interface (Wi-Fi/Ethernet).
Started live packet capture.

**2️⃣ Generate Network Traffic**
Visited a website using a web browser

**3️⃣ Stop Capture**
Allowed capture to run for about 1 minute.
Stopped packet capture using the stop button.

**4️⃣ Apply Protocol Filters**
Wireshark Packet Capture And Protocol Analysis
Packet Capture and Protocol Analysis using Wireshark

Used Wireshark display filters to analyze traffic:
dns – Domain Name System traffic
tcp – Transmission Control Protocol
http – Web traffic
icmp – Ping requests and replies

**5️⃣ Identify Protocols**
At least three different protocols were identified:
DNS – Resolves domain names to IP 
TCP – Reliable data transmission protocol
HTTP– Web communication
ICMP – Network diagnostic messages

**Observations & Summary**
The captured network traffic shows normal communication between client and server systems. DNS packets were observed during domain name resolution, TCP packets handled reliable data transmission, and HTTP/HTTPS packets indicated web browsing activity. ICMP packets were captured during ping operations, showing echo request and reply messages.

**6️⃣ Export Packet Capture**

Saved the capture file as .pcap using File → Save As.

