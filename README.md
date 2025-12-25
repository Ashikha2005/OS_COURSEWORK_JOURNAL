\# OS Coursework Journal



NAME : ASHIKHA AMBALATHUVEETTIL ASHRAF

MODULE : OPERATING SYSTEMS

VIRTUALISATION PLATFORM: VIRTUALBOX  

GUEST OS: Ubuntu Server 24.04 LTS  



---



WEEK 1: VIRTUAL MACHINE SETUP

OBJECTIVE:



To install and configure an Ubuntu Server virtual machine using VirtualBox.



TASKS COMPLETED:



\- Installed VirtualBox on host system

\- Downloaded Ubuntu Server 24.04 LTS ISO

\- Created a new virtual machine

\- Allocated CPU, RAM, and storage

\- Installed Ubuntu Server successfully



EVIDENCE:



!\[Screenshot of VirtualBox VM settings](Screenshots/week-1%20VM%20Settings.png)



OUTCOME:



Ubuntu Server was installed and booted successfully.



---



WEEK 2: NETWORK CONFIGURATION

OBJECTIVE:



To configure and verify network connectivity.



TASKS COMPLETED:



\- Configured Host-Only and NAT adapters

\- Verified IP addresses using `ip addr`

\- Tested connectivity using `ping`

\- Verified SSH access from host machine



EVIDENCE:



!\[Screenshot of `ip addr`](Screenshots/week%20-%202%20ip%20addr.jpeg)

!\[Screenshot of successful ping](Screenshots/week%20-%202%20ping.jpeg)

!\[Screenshot of SSH connection](Screenshots/week%20-%202%20SSH%20connection.png)



OUTCOME:



Network connectivity was successfully established.

---



WEEK 3: SSH AND SECURITY CONFIGURATION

OBJECTIVE:



To configure secure remote access to the Ubuntu Server using SSH.



TASKS COMPLETED:



\- Installed and enabled OpenSSH server

\- Verified SSH service status

\- Connected to server using SSH from host machine

\- Configured key-based authentication

\- Tested password-based authentication



EVIDENCE:



!\[Screenshot of `systemctl status ssh`](Screenshots/week%20-%203%20systemctl%20status%20ssh.jpeg)

!\[Screenshot of successful SSH login](Screenshots/week%20-%203%20successful%20SSH.png)

!\[Screenshot of SSH key authentication 1](Screenshots/week%20-%203%20SSH%20key.png)

!\[Screenshot of SSH key authentication 2](Screenshots/week%20-%203%20ssh%20copy%20id.png)



OUTCOME:



Secure remote access to the server was successfully configured.



---



WEEK 4: FIREWALL CONFIGURATION

OBJECTIVE:



To configure a firewall to protect the server.



TASKS COMPLETED:



\- Enabled UFW firewall

\- Allowed SSH traffic through firewall

\- Verified firewall status



EVIDENCE:



!\[Screenshot of `ufw status`](Screenshots/week%20-%204%20ufw%20status%20and%20ssh%20allowed.jpeg)



OUTCOME:



Firewall rules were successfully applied to secure the server.



---



WEEK 5: PERFORMANCE TESTING

OBJECTIVE:



To evaluate system and network performance.



TASKS COMPLETED:



\- Installed performance tools (iperf3, fio, memtester)

\- Conducted CPU and memory tests

\- Conducted disk I/O tests

\- Conducted network performance tests



EVIDENCE:



!\[Screenshot of memtester output](Screenshots/week%20-%205%20memtester%20output.jpeg)

!\[Screenshot of fio results](Screenshots/week%20-%205%20fio%20results.jpeg)

!\[Screenshot of iperf3 test 1](Screenshots/week%20-%205%20iperf3%20test.jpeg)

!\[Screenshot of iperf3 test 2](Screenshots/week%20-%205%20iperf3.png)

!\[Screenshot of iperf3 test 3](Screenshots/week%20-%205%20iperf3%202.jpeg)



OUTCOME:



System performance was tested and results were recorded.



---



WEEK 6: SYSTEM MONITORING

OBJECTIVE:



To monitor system resource usage.



TASKS COMPLETED:



\- Used monitoring tools (top, htop, iostat)

\- Observed CPU, memory, and disk usage during tests



EVIDENCE:



!\[Screenshot of top output](Screenshots/week%20-%206%20top.jpeg)

!\[Screenshot of htop output](Screenshots/week%20-%206%20htop.jpeg)

!\[Screenshot of iostat output](Screenshots/week%20-%206%20iostat output.jpeg)



OUTCOME:



System performance was successfully monitored in real time.



WEEK 7: SECURITY AUDIT AND SYSTEM EVALUATION

OBJECTIVE:



To perform a comprehensive security audit of the Ubuntu Server system, evaluate its overall security posture, and verify that all previously implemented security controls are functioning as intended.



TASKS COMPLETED:



\-Installed and executed Lynis to conduct a full system security audit

\-Analysed the Lynis hardening index, warnings, and security recommendations

\-Performed a network security scan using nmap within the isolated VirtualBox environment

\-Reviewed all running system services to ensure only essential services were enabled

\-Verified firewall rules and SSH access restrictions



EVIDENCE:



!\[Screenshot of Lynis security audit results and hardening index 1](Screenshots/week%20-%207%20lynis%201.jpeg)

!\[Screenshot of Lynis security audit results and hardening index 2](Screenshots/week%20-%207%20lynis%202.jpeg)

!\[Screenshot of Lynis security audit results and hardening index 3](Screenshots/week%20-%207%20lynis%203.jpeg)

!\[Screenshot of Lynis security audit results and hardening index 4](Screenshots/week%20-%207%20lynis%204.jpeg)

!\[Screenshot of Lynis security audit results and hardening index 5](Screenshots/week%20-%207%20lynis%205.jpeg)

!\[Screenshot of nmap scan showing open and closed ports](Screenshots/week%20-%207%20nmap.png)



OUTCOME:



The security audit confirmed that the Ubuntu Server system is well-hardened and securely configured. The Lynis audit demonstrated a strong security posture with most recommended controls already implemented. The nmap scan verified that only SSH (port 22) was accessible, significantly reducing the attack surface. The service audit confirmed that only essential services were running, minimising unnecessary security risks. Overall, the system meets best-practice standards for secure remote server administration.

