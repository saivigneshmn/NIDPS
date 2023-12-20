# NIDPS
Network Intrusion Detection and Prevention with Snort Tool


Network security is a time-consuming and systematic project. The first line of defence against network security is the intrusion detection system. In the world of open source software, Snort is a well-known intrusion detection system. It is widely used around the world in the intrusion prevention and detection domain. In this project we have basic architecture where the attacker tries to attack a victim machine. Snort will be installed on the victim machine which helps in detecting the attack launched on it by the attacker. Snort will be detecting the attacks based on the configuration and snort intrusion detection rules.


![image](https://github.com/saivigneshmn/NIDPS/assets/100284499/a694991c-2a30-4e51-95fe-8a823ec0838a)

Snort stands out as a robust, freely available open-source intrusion detection system, widely embraced by diverse individuals and organizations. Functioning primarily as a Signature-based Intrusion Detection and Prevention System, Snort's strength lies in its rule formation. Rules can be tailored to either block specific traffic or generate alerts, with the flexibility to log these alerts in files, display them on the console, or send them via email. The tool's versatility extends to logging alerts into databases as well.

Operating in three distinct modes, Snort serves as a packet sniffer in the command line, focusing on header information and displaying details on-screen. Alternatively, it functions as a packet logger, capturing and logging each packet in root directory files, enabling later review using tools like Snort or tcpdump. The Network Intrusion Detection System (NIDS) mode, the most crucial perspective, employs Snort's rules to identify potential intrusion activities on the network.

In NIDS mode, Snort utilizes network interface cards (NICs) in promiscuous mode, allowing real-time analysis and capture of raw packet data. This mode offers capabilities such as real-time packet logging, content searching and matching, and protocol analysis. Snort can detect various attacks with known vulnerabilities and goes beyond mere detection by implementing actions like rejection, dropping, and blocking to prevent potential intrusions.

The key distinction between NIDS mode and the other two Snort modes lies in the active application of different actions to packet content flowing across the network, aligning with the specified rule set.
