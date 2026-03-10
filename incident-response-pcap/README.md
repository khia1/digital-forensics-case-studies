# Incident Response Investigation

## Scenario
A network intrusion was suspected after unusual FTP activity was detected in network traffic.

## Tools
Wireshark
NetWitness

## Investigation
A PCAP file was analyzed to identify suspicious connections and reconstruct the attack timeline.

## Findings
The investigation revealed that stolen credentials were used to transfer files over FTP between two systems. The timeline analysis showed how the credentials were leaked and later used for data exfiltration.
