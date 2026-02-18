Botnet PCAP Traffic Analysis
Project Overview

The repository contains network traffic analysis which uses a publicly available PCAP file as its source. The research used packet inspection together with statistical methods to determine whether an internal host showed signs of automated behavior or botnet activity.

The analysis focuses on identifying abnormal traffic patterns, dominant hosts, protocol distribution, and communication behavior.

Dataset

Analyzed file: botnet-capture-20110816-sogou.pcap

Format: PCAP (Ethernet)

Duration: 15 minutes 46 seconds

Total packets: 20,663

Total data size: 18.5 MB

Source

The CTU-13 botnet traffic dataset originates from the database developed by:

Czech Technical University in Prague

Stratosphere Laboratory

Official Dataset Reference:

CTU-13 Dataset

The repository does not include the PCAP file as a downloadable file. Please obtain it directly from the official source.

Tools & Techniques

The following tools and techniques were used:
1. Wireshark packet inspection
2. Protocol hierarchy analysis
3. IPv4 conversation statistics
4. TCP stream analysis
5. Traffic asymmetry evaluation
6. HTTP request inspection

Analysis Focus

The investigation evaluated:
1. Dominant internal hosts
2. External communication patterns
3. Protocol usage distribution
4. HTTP request behavior
5. Traffic concentration and asymmetry
6. Indicators of automated activity

Key Observations :
1. The majority of outbound traffic originated from a single internal host.
2. The primary method of communication used HTTP over TCP.
3. Multiple external endpoints were targeted through repeated HTTP GET requests.
4. The traffic distribution showed an extreme preference for one specific external IP address.
5. Automated communication patterns were indicated through the observed behavioral indicators.
