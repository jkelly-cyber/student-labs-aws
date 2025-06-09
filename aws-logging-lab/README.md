## AWS Logging & SIEM Lab
This lab was completed as part of the Diploma of Information Technology, Cyber Security and Advanced Networking -Swinburne

### 🔧 What I Built

- Created a custom VPC with:
  - 2 public subnets
  - 2 private subnets
- Deployed EC2 instances for:
  - Web server
  - Bastion host (jump server)
  - SIEM server (central logging)
- Connected to instances using SSH via `.pem` key and PuTTY
- Opened **UDP port 514** for syslog on the SIEM server
- Edited `/etc/rsyslog.conf` to enable log collection
- Restarted `rsyslog` service
- Used the `logger` command from web servers to send test logs
- Verified log entries on SIEM using `journalctl`
- Used `ping` to test connections from webserver to SIEM
- Troubleshooted network routes and firewall settings
- Confirmed successful end-to-end log delivery

### ✅ Skills Used
- AWS VPC/Subnets/Security Groups
- EC2 configuration
- SSH & PuTTY connections
- Rsyslog configuration
- Linux troubleshooting
