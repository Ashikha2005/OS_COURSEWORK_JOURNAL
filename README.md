# OS Coursework Journal



NAME : ASHIKHA AMBALATHUVEETTIL ASHRAF

MODULE : OPERATING SYSTEMS

VIRTUALISATION PLATFORM: VIRTUALBOX  

GUEST OS: Ubuntu Server 24.04 LTS  


---


WEEK 1: VIRTUAL MACHINE SETUP

OBJECTIVE:

To install and configure an Ubuntu Server virtual machine using VirtualBox.

TASKS COMPLETED:

- Installed VirtualBox on host system
- Downloaded Ubuntu Server 24.04 LTS ISO
- Created a new virtual machine
- Allocated CPU, RAM, and storage
- Installed Ubuntu Server successfully



EVIDENCE:



![VirtualBox VM settings](screenshots/week_1_vm_settings.png.png)



OUTCOME:

Ubuntu Server was installed and booted successfully.

---

WEEK 2: NETWORK CONFIGURATION

OBJECTIVE:

To configure and verify network connectivity.

TASKS COMPLETED:

- Configured Host-Only and NAT adapters
- Verified IP addresses using `ip addr`
- Tested connectivity using `ping`
- Verified SSH access from host machine

EVIDENCE:

![`ip addr`](screenshots/week _2_ip_addr.jpeg.jpeg)
![successful ping](screenshots/week_2_ping.jpeg.jpeg)
![SSH connection](screenshots/week _2_ssh_connection.png.png)

OUTCOME:

Network connectivity was successfully established.

---



WEEK 3: SSH AND SECURITY CONFIGURATION

OBJECTIVE:

To configure secure remote access to the Ubuntu Server using SSH.

TASKS COMPLETED:

- Installed and enabled OpenSSH server
- Verified SSH service status
- Connected to server using SSH from host machine
- Configured key-based authentication
- Tested password-based authentication


EVIDENCE:

![systemctl status](screenshots/week_3_systemctl_status_ssh.jpeg.jpeg)
![successful SSH login](screenshots/week_3_successfull_ssh.png.png)
![SSH key authentication 1](screenshots/week_3_ssh_key.png.png)
![SSH key authentication 2](screenshots/week _3_ssh_copy_id.png.png)

OUTCOME:

Secure remote access to the server was successfully configured.

---

WEEK 4: FIREWALL CONFIGURATION

OBJECTIVE:

To configure a firewall to protect the server.

TASKS COMPLETED:

- Enabled UFW firewall
- Allowed SSH traffic through firewall
- Verified firewall status

EVIDENCE:

![`ufw status`](screenshots/week_4_ufw_status_and_ssh_allowed.jpeg.jpeg)

OUTCOME:

Firewall rules were successfully applied to secure the server.

---

WEEK 5: PERFORMANCE TESTING

OBJECTIVE:

To evaluate system and network performance.

TASKS COMPLETED:

- Installed performance tools (iperf3, fio, memtester)
- Conducted CPU and memory tests
- Conducted disk I/O tests
- Conducted network performance tests

EVIDENCE:

![memtester output](screenshots/week_5_memtester_output.jpeg.jpeg)
![fio results](screenshots/week_5_fio_results.jpeg.jpeg)
![iperf3 test 1](screenshots/week_5_iperf3_test.jpeg)
![iperf3 test 2](screenshots/week_5_iperf3.png.png)
![iperf3 test 3](screenshots/week_5_iperf3_2.jpeg.jpeg)


OUTCOME:

System performance was tested and results were recorded.


---

WEEK 6: SYSTEM MONITORING

OBJECTIVE:

To monitor system resource usage.


TASKS COMPLETED:


- Used monitoring tools (top, htop, iostat)
- Observed CPU, memory, and disk usage during tests

EVIDENCE:

![top output](screenshots/week_6_top.jpeg.jpeg)
![htop output](screenshots/week_6_htop.jpeg.jpeg)
![iostat output](screenshots/week_6_iostat_output.jpeg.jpeg)

OUTCOME:

System performance was successfully monitored in real time.

---

WEEK 7: SECURITY AUDIT AND SYSTEM EVALUATION

OBJECTIVE:

To perform a comprehensive security audit of the Ubuntu Server system, evaluate its overall security posture, and verify that all previously implemented security controls are functioning as intended.

TASKS COMPLETED:

-Installed and executed Lynis to conduct a full system security audit
-Analysed the Lynis hardening index, warnings, and security recommendations
-Performed a network security scan using nmap within the isolated VirtualBox environment
-Reviewed all running system services to ensure only essential services were enabled
-Verified firewall rules and SSH access restrictions

EVIDENCE:

![Lynis security audit results and hardening index 1](screenshots/week_7_lynis_1.jpeg.jpeg)
![Lynis security audit results and hardening index 2](screenshots/week_7_lynis_2.jpeg.jpeg)
![Lynis security audit results and hardening index 3](screenshots/week_7_lynis_3.jpeg.jpeg)
![Lynis security audit results and hardening index 4](screenshots/week_7_lynis_4.jpeg.jpeg)
![Lynis security audit results and hardening index 5](screenshots/week_7_lynis_5.jpeg.jpeg)
![nmap scan showing open and closed ports](screenshots/week_7_nmap.png.png)

OUTCOME:

The security audit confirmed that the Ubuntu Server system is well-hardened and securely configured. The Lynis audit demonstrated a strong security posture with most recommended controls already implemented. The nmap scan verified that only SSH (port 22) was accessible, significantly reducing the attack surface. The service audit confirmed that only essential services were running, minimising unnecessary security risks. Overall, the system meets best-practice standards for secure remote server administration.

