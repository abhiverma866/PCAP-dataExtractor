# PCAP-dataExtractor
Python code to parse JSON network traffic data to CSV file. 

Note: The script is written for Python 3.6.7. Probably ok with all other versions.
Steps for PCAP -> JSON -> Parsed data file.

Step 1: Export pcap data to JSON file.

Wireshark has a feature to export it's capture files to JSON.
File->Export Packet Dissections->As JSON

Step 2: Make required changes in json2csv.py file.

Step 3: Execute json2pcap.py 
