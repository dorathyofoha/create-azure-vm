<p align="center">
<img src="https://i.imgur.com/Bp7tRX1.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
In this project, I created a virtual machine on Azure and used Network Watcher to view its topology.<br />


<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account

<h2>High-Level Steps</h2>

- Create a Microsoft Azure Account.
- Select “Virtual machines” and click Create to set up an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- View newly created VM in Network Watcher
- Delete Resource Groups to minimize charges.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/zkr3A9P.png" height="70%" width="70%"/>
</p>
<p>
After creating my Microsoft Azure account, I typed “virtual machine” in the search bar at the top of the Azure homepage and selected “Virtual machines.” I clicked “Create” in the top left corner (the blue “Create” button in the middle of the screen also works) and then selected “Azure virtual machine.”
</p>
<br />

<p>
<img src="https://i.imgur.com/bwTogp0.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/3h91vqh.png" height="50%" width="50%"/>
</p>
<p>
The first page is the “Basics” page, where I provided information in the required fields to create a new Resource Group (RG)/ Virtual Machine. I created the RG by selecting the “Create new” option. Then, I selected an appropriate region based on my location (for example, U.S. East). Next, I chose the suitable size for the VM and set up my username and password. Don’t forget to check the box under Licensing! Once I was done filling this page out, I clicked “Review + create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/ksIytig.png" height="50%" width="50%"/>
</p>
<p>
Before the VM could be created, I had to make sure it passed validation. Once the message at the top confirmed that everything was set up properly, I clicked “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It took a bit of time for the VM to be set up by Azure, but once it was done, I was able to look at the configuration of my VM. I made a mental note of the location of the public and private IP addresses on this page, since finding this information would be important for future labs.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
To satisfy my curiosity, I viewed the various components of my new VM using Network Watcher in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group a.k.a. firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
✨ And that’s how I created a virtual machine in Azure! After using the Lab, don’t forget to clean up by deleting the VMs and the whole Resource Group created to minimize subscription charges.
</p>
<br />
