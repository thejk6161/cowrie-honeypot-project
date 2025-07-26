 Cowrie Honeypot Project

This is my cybersecurity honeypot setup using **Cowrie**, an SSH and Telnet honeypot, running on Kali Linux.

# Features
- Logs brute-force login attempts
- Records attacker input (commands)
- Captures file downloads and malware samples
- Simulates a vulnerable shell environment

# Tools Used
- Kali Linux
- VirtualBox
- Cowrie
- Git
- (Future: Snort/Suricata for IDS/IPS integration)

## How to Run

```bash
git clone https://github.com/thejk6161/cowrie-honeypot-project
cd cowrie
sudo ./start.sh
