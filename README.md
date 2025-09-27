<p align="center">
<img src="https://imgur.com/wYucC7L.png" alt="osTicket logo"/>
</p>

<h1>Microsoft Azure Compute and Networking 🪟 - Setting Up Virtual Machines</h1>
This section outlines the process of setting up Virtual Machines in Azure in preparation for Compute and Networking<br /> (Link Back to Main Project Contents Page is at the Bottom of this Repo)

<h2>Environments and Technologies Used</h2>

- Lenovo Ideapad 5 Pro 16gb AMD Ryzen 7
- Microsoft Azure Resource Group
- Microsoft Azure Windows 10 Pro version 22H2 - x64 Gen2 Virtual Machine
- Microsoft Azure Ubuntu Pro 24.04 LTS - x64 Gen2 Virtual Machine

<h2>Operating Systems Used </h2>

- Local Windows 11 Home Version 21H2</b>

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Microsoft Azure Subsription Credit 

<h2>Installation, Setup, Resource Setup, Executing Functions</h2>

1. In this lab I began with creating a Resource Group that would contain the virtual machines that would be used to execute the compute and networking activities in this section. 

<p>
<img src="https://i.imgur.com/zlIZDJB.png" alt="Disk Sanitization Steps"/>
</p>
<p>
2. The next stage involved creating the Windows 10 Pro version 22H2 - x64 Gen2 Virtual Machine. Key steps to look out for during this process were to make sure that the Virtual Machines were set to the same location as the Resource Group, choosing the right service (Virtual Machine type) and choosing the right size so the Virtual Machine could smoothly execute all the necessary functions for the lab. The region was UK (South) and the size chosen was Standard_D2s_v3 - 2 vcpus, 8 GiB memory. Below shows the process of creating a Virtual Network. Usually this is automatically created and connected to the Virtual Machine but in this case I created one manually. 
</p>
<br />

<p>
<img src="https://i.imgur.com/1GORug6.png" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Below we can see the the Windows Virtual Machine named "WindowsVM" and all of its associated resources nested inside the Resource Group created for the Virtual Machines. The other resources include the Public IP Address, Network Security Group, Virtual Network, Network Interface and Disk. 
</p>
<br />

<p>
<img src="https://i.imgur.com/m6oGF7G.png" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Below shows the end result of the exact same process as above but is the completed state of the Linux Virtual Machine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/YmTbM0Z.png" alt="Disk Sanitization Steps"/>
</p>
<p>
LINK BACK TO THE MAIN PROJECT CONTENTS PAGE - https://github.com/wahidonchain/Azure-Compute-and-Networking
