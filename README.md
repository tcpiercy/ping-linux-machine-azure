
<img src="https://github.com/user-attachments/assets/9499b61f-0733-48a9-a9fb-e608663e37a3" width="400" />


<h1>Azure- Computer Networking and Viewing Traffic</h1>

  

This lab outlines the processes used in viewing and filtering network traffic between two virtual machines, as well as creating a firewall on Azure

Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell
- Wireshark

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Linux Ubuntu

<h2>List of Prerequisites</h2>

- Create Virtual Machines in Azure
- Install Wireshark in VM


<a href="https://drive.google.com/file/d/1wtcZP9u37IKxT53l0XAHxm5A10G3HyLV/view">
  <img src="https://raw.githubusercontent.com/tcpiercy/ping-linux-machine-azure/main/image.png" width="400">
</a>


  
In the video demonstration in the thumbnail above, I demonstrate how I observed traffic between two virtual machines I created inb Azure, one Windows and one Linux, using RDP, Wireshark, and Powershell. Firstly, I filtered for ICMP traffic and observed. Then I pinged the Linux machine from the Windows machine, and observed in Wireshark as well. I then verified by using ipconfig /all the traffic between the machines as well. 

