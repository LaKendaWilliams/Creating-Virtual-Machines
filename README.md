# Creating-Virtual-Machines-to-block-traffic
<p align="center">

![images](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/35091daf-99a2-4124-86e1-1c9a8fba7ceb)



This Project consists of creating resource groups for two virtual machines: one Windows and one Linux. The utility allows you to remotely connect to a desktop in the first virtual machine and install Wireshark in the second virtual machine which will ping and observe traffic. In the second virtual machine, the network security groups' traffic will be blocked and stopped.




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
In this demonstration, a resource group and two virtual machines were created through Microsoft Azure. First step logged into Azure.com under account information. Created the main resource group (RGProject) reviewed and created. 
Next, I created the first virtual machine under the Resource group (RGProject), then created a virtual machine name (VMProjectW) and selected
the region in which VM was made. I also created a VM in Windows 10. Lastly, I created the username and password then reviewed and created the first VM.
I Followed this step to create the second VM and that one was created under Linux (VMProjectL). 
</p>
<br />

<p>

  ![Capture2](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/b13978e6-cadf-4740-93f2-29db60c9655d)

</p>
<p>
In this demonstration, the virtual machine was connected through a remote desktop.
First I clicked on the Windows VM and copied the IP Address. Next, I clicked the start menu
to search the remote desktop. After, I pasted the IP address on the remote desktop 
I clicked search to connect remotely (connect with username and password). Then, on the remote desktop I Google searched Wireshark then downloaded
and installed it.
</p>
<br />

<p>

  ![Capture3](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/e205611d-be0e-48f0-904b-98d044c25999)

</p>
<p>
In this demonstration, the navigation is all remotely done through Wireshark. First, I connected 
to the ethernet this step is to start capturing live packets. Now observing all the live traffic
that is happening in the VM. After filtering the traffic by the ICMP (internet Control Message Protocol) to stop movement.
</p>
<br />

<p>

  ![Capture4](https://github.com/Admiller12/Creating-Virtual-Machines-to-block-traffic/assets/138805066/8a534c0f-1139-4e60-8412-39882badd5ce)

</p>
<p>
In this demonstration, the connection is being made through the virtual machine with Linux. Navigating back to Azure 
to the second VM that was created to ping the Private IP address essentially. Next, I opened up Powershell and typed in "ping 10.0.0.5" 
which is the second VM's private IP address. Now we can see it pinging and replying from the second VM. 
</p>
<br />
