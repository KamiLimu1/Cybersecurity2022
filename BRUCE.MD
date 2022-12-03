# Track 101 Validation - `Bruce's version`
## Objectives 
- Set up personal lab using virtual box
- Set up to 2 Virtual machines with varying with network profiles.
- Install Windows and Linux(with LAMP)
- Do all this using virtual box

`Given that I have dual booted my machine with Kali Linux and Windows, I installed virtual box and the subsequent set ups in my Kali Linux partition.`

### Installing Virtual box in Kali linux
By default Kali Linux comes with Virtual box pre-installed. But to learn on how to install it checkout the resources link below.

### Installing Kali Linux
I installed Kali Linux from a [pre-made Kali Linux Virtual Box images](https://www.kali.org/get-kali/#kali-virtual-machines).

I just had to configure the machine's settings.

Procedure in setting up the settings: 
    - Click new button and type the name of the Virtual Machine - I gave mine Kali Linux and selected the version as Debian(64-bit)
    ![This image is from Kali Linux page - same as my verison](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/vb-02.png)

    - Selecting RAM - the least is 2GB given some of the tools are resource intensive.
![Alt text](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/vb-03.png)
    
    - Creating a new virtual disk select the default choice.
    Then select the `Hard disk file type` to be VDI(VirtualBox Disk Image) still a default option.
![Alt text](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/vb-04.png)

    - Storage type should be Dynamically allocated.
    - Followed with giving the virtual hardisk's a designated size. 40GB or more should work just fine. Then click create to create the enivirnment. All this is done to define the resources the Machine will use.
![Alt text](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/vb-05.png)

    - A few other settings are set:
        1. Enable bidrectional sharing.
        2. Remove the optical version `Boot order` settings.
        3. Allocate atleast 2 cpus and enable `Enable PAE/NX`
        4. A video memory of 128 MB  should do.

When ready click the Start button and select the downloaded [pre-made Kali Linux Virtual Box images](https://www.kali.org/get-kali/#kali-virtual-machines)  and the virtual machine is ready to go.

### Installing LAMP in Kali Linux
LAMP is used to create websites and web applications.
It is an acronym for:
* Linux operating system.
* Apache HTTP server.
* MySQL relational database management system.
* PHP programming language.
Installation procedure:
    1. Update OS.
    2. Install Apache2 - `sudo apt-get install apache2`
    3. To Start/restart/Stop Apache 2 server - `/etc/init.d/apache2 start/stop/restart`
    4. Then installing MySQL and starting the services.
        * `sudo /etc/init.d/mysql start`
        * `sudo mysql_secure_installation`
    5. Restart the server then create a file and try running it.

### Installing Windows
1. Download windows from their official website.
2. Configure the required resources for the windows  machine. As done on Kali Linux with a difference that you select windows instead of Debian.

### Resouces
1. Installing [Virtual box](https://www.kali.org/docs/virtualization/install-virtualbox-host/) in Kali Linux
2. Installing [Kali Linux](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/)
3. Installing [LAMP in Kali Linux](https://betterprogramming.pub/how-to-install-lamp-stack-on-kali-linux-183fa4f48d16)