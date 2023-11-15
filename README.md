<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Enter portal.azure.com. Enter "Virtual Machines" in the search bar. Click on 'Create' on the top left.
- ![image](https://github.com/Sheen300/configure-ad/assets/150862861/4f88a018-194b-45db-ae51-9734aff6a67a)

- Step 2: Create a Virtual Machine with the Resource group name: "AD-Lab" for Active Directory Lab with the Virtual Machine named 'DC-2'. 
- Step 3: Choose a US region with Availability options as: No infrstructure redundancy required and a Standard security type.
- Step 4: The image will be Windows Server 2022.

- You should see the image below once completed correctly. 

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/Sheen300/configure-ad/assets/150862861/bb4116f1-162e-4800-aa40-893d92947090)


<p>
Click create. Repeat the same steps by creating another Virtual Machine only this time with the name 'Client-2' in the field that asks for a Virtual machine name with an asterisk next to it. For the resource group name, you will add it to the AD-Lab resource group in which we created when we created our very first Virtual Machine that was named 'DC-2'.  </p>

You should see the following image below. 
<br />

![image](https://github.com/Sheen300/configure-ad/assets/150862861/939d6e3a-44f0-41f7-acab-7be884d4ab97)

<p>
You will now name the new Virtual Machine 'Client-2'. The following credentials should be entered into each field: Region: US West US 3 (or whichever region you chose for the first Virtual Machine). Availability options: No infrastrcture redundancy required. Security type: Standard. For the image, instead of Windows Server 2022, this time we will use Windows 10 Pro, Version 2022. </p>
<br />

![image](https://github.com/Sheen300/configure-ad/assets/150862861/c4ed6818-96c2-4343-92ad-df85b9638d36)
<p>
Click Review + Create </p>
<br />

