<p align="center">
<img src="https://i.imgur.com/tUjfXAc.png alt="Microsoft Azure Logo"/>
</p>

<h1>Creating Resource Groups and Virtual Machines in Azure</h1>
This tutorial outlines the steps to creating virtual machines and connecting them to the same network security group in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Cloud Computing in Azure  
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Linux (Ubuntu)

<h2>High-Level Deployment and Configuration Steps</h2>


  
- Create Resource Group 
- Create Windows 10 Virtual Machine with Vnet and Subnet
- Create Linux Virtual Machine and connect to VM1 Vnet


<h2>Deployment and Configuration Steps</h2>

<p> Begin by naming your resource group (e.g., RG-Lab2).   
</p>
<p>
<img src= https://i.imgur.com/fX1aTAX.png 
<p>
<img src= https://i.imgur.com/UQWExyF.png
</p>

<br />

<p> Next create your virtual machines and connect them to the resource group that you just created. You will name each virtual machine (e.g. VM1 or VM2). 
</p>


![image](https://github.com/Traviskthomas/Azure-Cloud-Computing/assets/166442537/34372ee3-da05-4f59-831c-2d666045a62e)

</p>
  
<p>
<img src= https://i.imgur.com/zFOyfJn.png
</p>
  
<p>Repeat the same steps to create VM2 except, choose the Linux (Ubuntu) operating system. 
</p> 

<p>
<img src= https://i.imgur.com/8ofVEv2.png
</p>

<p>Next we observe various network traffic to and from VM1 and VM2 with Wireshark as well as experiment with Network Security Groups.</p>
<p>
<img src= https://i.imgur.com/dLkMeG9.png
</p>
  
<br />
