<p align="center">
 <img src="https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/0c92122c-77df-44df-bc1a-6c4f6a0bc33a&auto=format&fit=crop&w=2772&q=80" width="200" height="200" border="10"/>
</p>

<h1 align="center"> Creating A Virtual Machine In Microsoft Azure </h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Microsoft Remote Desktop
- Windows Command Prompt

<h2>Operating Systems Used</h2>

- Windodws 11 Pro
- Windows 10 (Virtual Machine)

<h2>List of Prerequisites</h2>

- Microsoft Azure Account and Subscription
- Access to Microsoft Remote Desktop Connection

<h2>Creating our Resource Group and Virtual Machines </h2>
 
- Resource Group
  - Through Azure Services, go to Resource groups to create a Resource Group and name your Resource Group RG-VM. Take note of the Region of your Resouce Group as it'll come in play when setting up our VMs. Once done, then click on Review + Create
   



- Virtual Machine 1 using Windows 10
  - Through Azure Services, go to Virtual Machines to create an Azure Virtual Machine. Select the Resource group we've created (RG-VM) and name the virtual machine VM-1. Make sure the Region is the same as your Resource Group and we'll set our Availability Options set to No infrastructure and Security Type to Standard for this tutorial
  - Set the Image (our Operating System) to Windows 10 Pro, Version 22H2, x64 Gen2
  - The Size selected dicates the general processing power and RAM of our VM, for this tutorial we'll set it to Standard_E2s_V3 which provides 2 virtual CPUs and 16 GBs of RAM
