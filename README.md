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

Wireshark packet inspection

Protocol hierarchy analysis

IPv4 conversation statistics

TCP stream analysis

Traffic asymmetry evaluation

HTTP request inspection

Analysis Focus

The investigation evaluated:

Dominant internal hosts

External communication patterns

Protocol usage distribution

HTTP request behavior

Traffic concentration and asymmetry

Indicators of automated activity

Key Observations

The majority of outbound traffic originated from a single internal host.

The primary method of communication used HTTP over TCP.

Multiple external endpoints were targeted through repeated HTTP GET requests.

The traffic distribution showed an extreme preference for one specific external IP address.

Automated communication patterns were indicated through the observed behavioral indicators.
