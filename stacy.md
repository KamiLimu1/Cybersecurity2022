A REPORT ON THE SET UP OF A VIRTUAL MACHINE.
OBJECTIVES.
•	Set up a personal lab using VirtualBox.
•	Set up two virtual machines with varying networking profiles.
•	Run the virtual machines on both windows and Linux.
•	Have LAMP installed on the Linux virtual machine.
•	Use more than 80% of VirtualBox on the setup process.

INTRODUCTION
Virtualization is the process of creating a software-based, or "virtual" version of a computer, with dedicated amounts of CPU, memory, and storage that are "borrowed" from a physical host computer in many cases your personal computer and/or a remote server such as a server in a cloud provider's datacenter. A virtual machine is a computer file, typically called an image, that behaves like an actual computer. It can run in a window as a separate computing environment, often to run a different operating system or even to function as the user's entire computer experience as is common on many people's work computers. The virtual machine is partitioned from the rest of the system, meaning that the software inside a VM can't interfere with the host computer's primary operating system.
USES OF VIRTUAL MACHINES
Here are a few ways virtual machines are used:
•	Building and deploying apps to the cloud.
•	Trying out a new operating system (OS), including beta releases.
•	Spinning up a new environment to make it simpler and quicker for developers to run dev-test scenarios.
•	Backing up your existing OS.
•	Accessing virus-infected data or running an old application by installing an older OS.
•	Running software or apps on operating systems that they weren't originally intended for.
BENEFITS OF VIRTUAL MACHINES
While virtual machines run like individual computers with individual operating systems and applications, they have the advantage of remaining completely independent of one another and the physical host machine. A piece of software called a hypervisor, or virtual machine manager, lets you run different operating systems on different virtual machines at the same time. This makes it possible to run Linux VMs, for example, on a Windows OS, or to run an earlier version of Windows on more current Windows OS.
And, because VMs are independent of each other, they're also extremely portable. You can move a VM on a hypervisor to another hypervisor on a completely different machine almost instantaneously.
Because of their flexibility and portability, virtual machines provide many benefits, such as:
•	Cost savings—running multiple virtual environments from one piece of infrastructure means that you can drastically reduce your physical infrastructure footprint. This boosts your bottom line—decreasing the need to maintain nearly as many servers and saving on maintenance costs and electricity.
•	Agility and speed—Spinning up a VM is relatively easy and quick and is much simpler than provisioning an entire new environment for your developers. Virtualization makes the process of running dev-test scenarios a lot quicker.
•	Lowered downtime—VMs are so portable and easy to move from one hypervisor to another on a different machine—this means that they are a great solution for backup, in the event the host goes down unexpectedly.
•	Scalability—VMs allow you to more easily scale your apps by adding more physical or virtual servers to distribute the workload across multiple VMs. As a result, you can increase the availability and performance of your apps.
•	Security benefits— Because virtual machines run in multiple operating systems, using a guest operating system on a VM allows you to run apps of questionable security and protects your host operating system. VMs also allow for better security forensics, and are often used to safely study computer viruses, isolating the viruses to avoid risking their host computer.

A virtual machine, commonly shortened to just VM, is no different than any other physical computer like a laptop, smart phone, or server. It has a CPU, memory, disks to store your files, and can connect to the internet if needed. While the parts that make up your computer (called hardware) are physical and tangible, VMs are often thought of as virtual computers or software-defined computers within physical servers, existing only as code.
 METHODOLOGY
1.	I Opened Oracle download page.
2.	Under the “VirtualBox binaries” section, I clicked the Windows hosts link and save the installers on my Windows 10 device.
 VirtualBox download page
3.	I double-clicked the VirtualBox-x.x.x-x-Win.exe file to launch the installer.
4.	I clicked the Next button.
5.	I used the default settings selection, and clicked the Next button.
 VirtualBox default install settings
6.	I clicked the Next button and proceeded to install VirtualBox on Windows 10.
 Custom setup options
7.	I clicked the Yes button to confirm the virtual network adapter installed warning on Windows 10.
 VirtualBox network adapter warning
8.	I clicked the Install button 
9.	I clicked the Finish button.
 The software finished the installation, and launched automatically.
ON SETTING UP THE VIRTUAL WINDOWS PC
1.	Creating a new pc

First off, head over to the Windows 10 download page. If you are a Windows user, MS will prompt you to download the Media Creation Tool before allowing you to download an OS image. You can use this tool to create an ISO file locally, or you can follow these additional instructions if you want to download the ISO manually without being forced to grab the tool first.
 

 I press	ed the “New” button, and named my virtual machine windows. My type was set to Microsoft Windows, and my version was set to Windows 10.
 
3. Allocating RAM
 I have 16GB of RAM in my desktop, so I decided to allocate 4GB  for my configuration. 
 
4. Creating a virtual drive
I created a virtual drive. Since 20GB is required for the 64-bit version. I decided on a 50GB virtual drive on my desktop.
 
I had not downloaded the windows 10 iso file so when I pressed launch it said aborted
I then went and downloaded the iso file from then set it up on my pc then began from step 1 to step 4 so as to get to step 5.
5. Locating the Windows 10 ISO
I went into the settings for this virtual machine, and navigated to the storage tab, clicked the disc icon with a green plus next to Controller: SATA. Clicked “Choose disk,” and then located the Windows 10 ISO I had just downloaded.
 
6. Launching of the installer
With all of that setup finished, I pressed the Start button in VirtualBox, and began the Windows 10 installation process. I followed the instructions on the screen to the end.
 

CHALLENGES
•	I had trouble in installing the windows 10 virtual pc as I had forgotten to download the ISO file.
•	It is challenging to set up a virtual box for Linux as I am not conversant with that operating system and I’m still learning hence I did not complete the task.
•	The time allocated was minimal putting into consideration its exam period and most of my time is occupied with school submissions.
CONCLUSION
This was a very good exercise for us mentees as it helps us learn new things. I aim to complete the task as soon as possible and hopefully be conversant with both Linux and Windows operating system.
