# Creating-Virtual-Machines-to-block-traffic
<p align="center">

![images](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/35091daf-99a2-4124-86e1-1c9a8fba7ceb)



This IT project involves the creation of resource groups for two virtual machines – one running Windows and the other running Linux. The objective is to establish remote desktop connectivity to the Windows virtual machine and install Wireshark on the Linux virtual machine for monitoring and analyzing network traffic. Additionally, network security groups will be implemented on the second virtual machine to regulate and restrict network traffic as required.




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark  

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Linux
- Powershell


<h2>Walk Through/Demonstration Steps</h2>

<p>

![Capture](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/0b1be1ae-7441-4874-83c2-346b4cc1f528)

</p>
<p>
In this IT demonstration, a resource group and two virtual machines were provisioned using Microsoft Azure. The process started by accessing the Azure portal at azure.com and logging in with the appropriate account credentials. A primary resource group named "RGProject" was then created and configured. Subsequently, the first virtual machine was created within the resource group "RGProject" with the name "VMProjectW", specifying the desired region for deployment, which in this case was Windows 10. User credentials were established, and the creation of the first VM was finalized after review. Following the same procedure, a second virtual machine was created under the same resource group, this time being configured for a Linux environment with the name "VMProjectL". 
</p>
<br />

<p>

  ![Capture2](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/b13978e6-cadf-4740-93f2-29db60c9655d)

</p>
<p>
In this IT demonstration, the virtual machine was accessed via a remote desktop connection. Initially, the IP address of the Windows VM was copied after clicking on it. Following that, the start menu was utilized to search for the remote desktop application. Subsequently, the copied IP address was pasted into the remote desktop software, initiating the remote connection process by clicking 'connect' and inputting the necessary username and password credentials. Once connected to the remote desktop environment, Wireshark was searched for on Google, downloaded, and installed as required.
</p>
<br />

<p>

  ![Capture3](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/e205611d-be0e-48f0-904b-98d044c25999)

</p>
<p>
In this IT demonstration, the monitoring and analysis of network traffic were conducted remotely using Wireshark. Initially, the connection to the Ethernet interface was established to commence capturing live network packets. Subsequently, the live traffic within the virtual machine was observed in real-time. Following that, a filter was applied to isolate and focus on network traffic specifically related to the ICMP (Internet Control Message Protocol), effectively halting its movement for inspection.
</p>
<br />

<p>

  ![Capture4](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/8a534c0f-1139-4e60-8412-39882badd5ce)

</p>
<p>
In this IT demonstration, the networking operation is executed within a Linux-based virtual machine. The process involves returning to Azure to access the second VM that was provisioned. Subsequently, within the Linux virtual environment, Powershell was launched to initiate a ping operation towards the private IP address of the second VM. By inputting the command "ping 10.0.0.5", the network connectivity between the two virtual machines was tested, displaying successful ping responses, affirming the communication between the two VMs.
</p>
<br />
