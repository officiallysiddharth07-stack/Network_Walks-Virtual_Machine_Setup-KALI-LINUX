# Network_Walks-Virtual_Machine_Setup-KALI-LINUX - CYBERSECURITY LAB (B084C)
--Setting up an isolated virtual lab for ethical hacking and cybersecurity practice--

<b>* Project Overview:</b><br>
This project focuses on setting up a virtual cybersecurity lab where different projects related to ethical hacking and penetration testing can be done. KALI LINUX is set up and configured on a private network (10.0.0.0/24).
<br>Thus, the ultimate purpose of the lab is to create a controlled environment where cybersecurity concepts like network mapping, port scanning, recon and several others can be practically implied.<br><br>


<b>* Objectives:</b><br>
The main objectives of this project are to:
1. Install and configure VirtualBox.
2. Install/import Kali Linux as a virtual machine.
3. Create a private NAT Network for the cybersecurity lab.
4. Configure network connectivity for Kali Linux.
5. Assign a consistent IP address to the Kali VM.
6. Verify network connectivity and DNS resolution.
7. Take a clean VM snapshot for recovery.
8. Document the complete setup process and prepare the environment for future cybersecurity projects.<br><br>


<b>* Lab Setup Procedure:</b><br>
1. Install Virtual Box.
2. Install .iso of KALI LINUX.
3. Create the NAT Network(IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabled).
4. Import Kali Linux into the virtual box.
5.  Configure the Kali Linux Network.
            <br> For Example:
                    <br>IP Address: 10.0.0.2
                    <br>Subnet Mask: 255.255.255.0
                    <br>Gateway: 10.0.0.1
                    <br>DNS: 8.8.8.8
6. Create a Clean VM Snapshot. (The snapshot represents the clean baseline of the laboratory.If a future exercise changes or damages the VM configuration, the machine can be restored to this baseline.)<br><br>


<b>* Lab Verification:</b></br>
| Test                        |  Command                      | Expected Result               |
| ----------------------------| ------------------------------|-------------------------------|
| Check IP address            | ip z                          | Correct Kali IP displayed     |
| Test gateway                | ping 10.0.0.1                 | Successful replies            |
| Test Internet connectivity  | ping 8.8.8.8                  | Successful replies            |<br><br><br>

<b>What I Learned:</b><br>
Through this project, I learned how to set up and configure a virtual environment for cybersecurity practice using VirtualBox. 
I understood following things:
1. I understood the difference between NAT and NAT Network and how virtual machines communicate with each other.
2. I also gained practical experience configuring static IP addresses, subnet masks, gateways, and DNS settings in Kali Linux.
3. Additionally, I learned the importance of creating snapshots to restore the system if something goes wrong during testing.
4. Finally, I realized that keeping proper documentation of commands, configurations, screenshots, and troubleshooting steps is essential for managing a cybersecurity project effectively.<br><br>


<b>* Author:</b><br>
Waqas Karim
Cybersecurity Professional B082
LinkedIn: https://www.linkedin.com/in/waqaskarim/<br><br>

<b>* Project Information:</b><br>
Program Name: Cybersecurity at Networkwalks | Week: 01 | Project: Cybersecurity & Pentesting Lab Setup | Repository: GitHub<br><br>
