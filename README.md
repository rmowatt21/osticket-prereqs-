# osticket-prereqs-

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create VM in Azure
- Install and download software configuration 
- Open IIS as an Admin.Register PHP from the IIS  
- Install osticket (enable php configurations)

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/66971462-633b-4df7-b1a6-e3a560686aed"/>
</p>
<p>
Virtual machine that is being used in Azure. Create the name, the username and password. Azure allows the user to create a VM(virtual machine). It will add a resource group that is created along with a IP address that is being used to connect to a network. In azure an automatic IP address is created(172.210.78.80) along with a default network(os-ticket-vnet/default). Another important component in azure is the size that you choose that determines factors such as processing power, memory, and storage capacity. Azure offers a wide variety of sizes to support many types of uses.
</p>
</p>
<br />

<img width="500" alt="image" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/0af72453-2434-4935-9cf8-713f4c166773">

The installation files that is being used to create a ticketing system. After we create the VM, we now can install the ticketing system configurations. Learn to install the os-ticket system here https://youtu.be/K7T_JjvEamg?si=m9BsoX0fl2mKoGFM 
</p>
<p>

<img width="500" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/c5fe06d3-6df7-4713-bd4d-848a4933baff">
<img width="500" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/a18d9d52-39b0-4550-838a-1a66152e8dae">

Open IIS as an Admin, Register PHP from within IIS. Once we configure and finish with this section of the installation we can continue to finally installing the OS-ticket

<img width="500" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/80b3c65f-67e5-4934-bc94-6978f91cc6d7">

</p>
<p>
installing the os-ticketing system there will be a few extensions that aren't installed when the users first installs the software. The user needs to enable the extensions which can be found in the IIS(internet information services manager). 
</p>
<br />

<img width="500" alt="image" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/dcca6e16-b4df-48fc-9529-43e19155d9af">

These are the configurations that need to be enabled in OS-ticketing system in order to fully assemble the OS-ticketing system. 

<img width="400" alt="image" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/9eb2fdfd-3816-4929-ae3c-64ec3d186549">
<img width="400" alt="image" src="https://github.com/rmowatt21/osticket-prereqs-/assets/98135951/19f47270-ae2a-457b-87e9-494f5f3af68b">

after the configuration is complete and all the enabled configurations are done the next step would be to continue setting up osticket using the username and password.
Setting up the ticket system should be complete and ready 
