# VMWARE T-POT INSTALLATION

First of all, we download our iso file from the given link. **https://github.com/telekom-security/tpotce/releases**
Open the VMware Workstation application and select the **"Create New Virtual Machine"** button. The same process can be done by following the **"File > New Virtual Machine"** steps.
After the virtual machine creation wizard starts, there are two options for installation, 'Typical' and 'Custom'. Continue with this option, as the typical installation option is recommended.

images-1

On the screen that comes up, the **"Installer disc image file (iso)"** option is selected for the installation file and the file path is shown. Next, continue by selecting the iso file. Then continue by selecting the operating system and version.

images-2 images-3

Next, the machine we installed is given a name and the installation location is selected.

images-4

On the left, continue by selecting the disk size and storage type of the virtual machine. Disk size can be changed according to the application and data to be used in the virtual machine.
On the right, if you want to make changes in the hardware features, the operations are performed with the **"Customize Hardware"** option and finished with the **'finish'** button.

images-5 images-6

This is how we give the characteristics for Honeypot.

images-7

After the configuration on the virtual machine, TPOT is started for installation.

images-8

Continue with selecting the first option on the incoming Boot screen. 

images-9

By selecting the region, the installation continues.

images-10

You can continue by selecting the keyboard type you are using from the keyboard settings section.

images-11

The T-pot installer will automatically select a debian archive mirror to download the packages. We choose the debian archive to download the packages required for the T-pot installation.

images-12 
images-13

Since there is no proxy, the installation continues by saying **"Continue"**.

images-14

There are pre-built and ready-made installation types available. Since I want to install industrial tpot, choose industrial and continue.

images-15

##### Standard
•	Honeypots: adbhoney, ciscoasa, citrixhoneypot, conpot, cowrie, dicompot, dionaea, elasticpot, heralding, honeysap, honeytrap, mailoney, medpot, rdpy, snare & tanner
•	Tools: cockpit, cyberchef, ELK, fatt, elasticsearch head, ewsposter, nginx / heimdall, spiderfoot, p0f & suricata
##### Sensor
•	Honeypots: adbhoney, ciscoasa, citrixhoneypot, conpot, cowrie, dicompot, dionaea, elasticpot, heralding, honeypy, honeysap, honeytrap, mailoney, medpot, rdpy, snare & tanner
•	Tools: cockpit, ewsposter, fatt, p0f & suricata
•	Since there is no ELK stack provided the Sensor Installation only requires 4 GB of RAM.
##### Industrial
•	Honeypots: conpot, cowrie, dicompot, heralding, honeysap, honeytrap, medpot & rdpy
•	Tools: cockpit, cyberchef, ELK, fatt, elasticsearch head, ewsposter, nginx / heimdall, spiderfoot, p0f & suricata
##### Collector
•	Honeypots: heralding & honeytrap
•	Tools: cockpit, cyberchef, fatt, ELK, elasticsearch head, ewsposter, nginx / heimdall, spiderfoot, p0f & suricata
##### NextGen
•	Honeypots: adbhoney, ciscoasa, citrixhoneypot, conpot, cowrie, dicompot, dionaea, glutton, heralding, honeypy, honeysap, ipphoney, mailoney, medpot, rdpy, snare & tanner
•	Tools: cockpit, cyberchef, ELK, fatt, elasticsearch head, ewsposter, nginx / heimdall, spiderfoot, p0f & suricata
##### Medical
•	Honeypots: dicompot & medpot
•	Tools: cockpit, cyberchef, ELK, fatt, elasticsearch head, ewsposter, nginx / heimdall, spiderfoot, p0f & suricata

We need to provide a password for the **tsec** user.

images-16

Now we create a username to access T-pot's web interface.

images-17

We set a password for the user we have given for the web interface.

images-18

Then the installation starts, this part may take a while.

images-19

For our user name tsec, we also provide the password that we created for tsec.

images-20

Installation is complete. T-pot is now active. We can enter from the given IP addresses to enter the web interface.

images-21

By entering the username and password we have given for the web interface, we open the T-pot interface.

images-22

This is how the Web interface is. The Web interface is connected via Port 64297. It is connected to the Admin panel from Port 64294

images-23

