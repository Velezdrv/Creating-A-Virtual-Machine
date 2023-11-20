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

   - Through Azure Services, go to <b>Resource Groups</b> to create a Resource Group and name your Resource Group What ever you need it to be for your job or project, this case we will just call ours RG1. When choosing a Region for your Resouce Group, rember which once you chose as it will come in play when setting up our VMs so we can put them into the same region. Once done click on Review + Create. This may take a while on the back end to fully complete.
  
   ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/9b8992ad-ed4f-4223-9fca-9b689bd74423)

- Virtual Machine
  - Through Azure Services, go to <b>Virtual Machines</b> to create an Azure Virtual Machine. 

  ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/c9cb22eb-8894-4e3b-aeb8-9efc56dac545)
   
   - Select the Resource group we have already created (RG1) and name the virtual machine VM1. Make sure the Region is the same as your Resource Group and we will set our <b>Availability Options</b> to No infrastructure and Security Type to Standard.
   - Set the Image (our Operating System) to Windows 10 Pro, Version 22H2, x64 Gen

  ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/2a70790f-ed0d-486a-ac3d-101b33a77cb3)
   
   - The Size selected dicates the general processing power and RAM of our VM, for this tutorial we'll set it to <b>Standard_D4s_V3</b> which provides 4 virtual CPUs and 16 GiBs of RAM (memory, which allows more application usage).
  
  ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/66a6c1c7-1f13-4d8b-9f0c-615d2608f609)

   - Set the username and password to login to your <b>Virtual Machine</b>, make sure to check the box for the licensing agreement.

  ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/9e7b81ad-fd69-4e48-9309-20fd464076ac)

  - Go to the <b>Networking</b> tab, the Virtual Network created by the <b>Virtual Machine</b> should have been made by the Resource Group. It will be made automatically by the Virtual Machine.
  
  ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/7954a468-e0db-425e-ad26-e1e9d4209fb0)

  - The Following Screen will indicate when your <b>Virtual Machine</b> is complete
 
   ![image](https://github.com/Velezdrv/Creating-A-Virtual-Machine/assets/147437260/c9bf33ee-4ff1-41fd-9542-0a99894ea8a7)

  
<h2>Virtual Machine Remote Login</h2>  

- Remote Desktop
  - Using Remote Desktop, We will login to our newly created <b>Virtual Machine</b>
  - Through <b>Azure Services</b>, go to <b>Virtual Machines</b> and select VM1, click on Connect to connect to the VM, from this page you can obtain the Public IP Address which we will use to connect to it via Remote Desktop Connection
