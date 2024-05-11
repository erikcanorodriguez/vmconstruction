<p align="center">
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/c770b37c-5a22-4617-bed5-7cfdc10a3e7f" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Mastering Azure: A Beginner's Guide to Creating Virtual Machines! </h1>
This tutorial outlines the construction of creating a Virtual Machine within Azure<br />


<h2>Video Demonstration</h2>

- ### [YouTube: A Beginner's Guide to Creating Virtual Machines!](https://youtu.be/3jMfxReHiB8)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Command Line

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment</h2>

This project offers a concise and beginner-friendly tutorial on creating virtual machines using Microsoft Azure. Through step-by-step guidance, users learn how to leverage Azure's infrastructure to set up virtual machines tailored to their needs. From provisioning to configuration, this tutorial equips users with essential skills for harnessing the power of cloud computing through Azure. Dive into the world of virtualization with confidence, courtesy of this comprehensive Azure VM creation tutorial.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/d00e2953-0c98-4149-9b14-5bfd5500c0aa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the Azure portal we head over to the icon/section labeled “Virtual Machines” 
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/5a243f06-dc4c-464d-ad6f-479d46688119" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the section labeled resource group we press create new and create a resource group with whichever title we feel necessary. This is important if we want to create multiple VM’s, we want to make sure they are under the same resource group in order to ensure connectivity between them.
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/8ce49ad9-1778-4e2d-b7d9-4f27fa73abbf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We then Name our virtual machine in order to distinguish various VMS from one another, in this example I simply name my virtual machine VM1. We also have to pay attention to the region and make sure it matches the region we are in (or the region that you would like the virtual machine to be located in).

</p>
<br />
<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/2beb48f5-4762-4396-ae6d-a6f2e7b9ead5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a username and password that we will remember and tick off the box at the bottom.
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/0aeeb89a-3032-40fe-a196-073e745e79d5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When creating multiple VMS make sure the virtual network is the same for all, then just click on “Review + Create”
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/vmconstruction/assets/168192619/af515532-6b57-4d7b-b7ce-fe043500c320" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, we want to open up “Remote Desktop Connection” which can be opened by simply clicking on the search bar on the bottom left. Once opened we copy the public IP Address given to us for the VM we just created and paste it onto the remote desktop connection App. Once this is done we press connect and then login with the previously created Username and Password. Once this is done the Virtual machine will automatically open up.
</p>
<br />
