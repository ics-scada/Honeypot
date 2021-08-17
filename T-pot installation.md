# VMWARE T-POT INSTALLATION

First of all, we download our iso file from the given link. **https://github.com/telekom-security/tpotce/releases**
Open the VMware Workstation application and select the **"Create New Virtual Machine"** button. The same process can be done by following the **"File > New Virtual Machine"** steps.
After the virtual machine creation wizard starts, there are two options for installation, 'Typical' and 'Custom'. Continue with this option, as the typical installation option is recommended.

![image-1](https://github.com/ics-scada/Honeypot/blob/main/İmages/1.PNG) 

On the screen that comes up, the **"Installer disc image file (iso)"** option is selected for the installation file and the file path is shown. Next, continue by selecting the iso file. Then continue by selecting the operating system and version.

![alt text](https://github.com/ics-scada/Honeypot/blob/main/İmages/2.PNG)![image-3](https://github.com/ics-scada/Honeypot/blob/main/İmages/3.PNG)

Next, the machine we installed is given a name and the installation location is selected.

![image-4](https://github.com/ics-scada/Honeypot/blob/main/İmages/4.PNG)

On the left, continue by selecting the disk size and storage type of the virtual machine. Disk size can be changed according to the application and data to be used in the virtual machine.
On the right, if you want to make changes in the hardware features, the operations are performed with the **"Customize Hardware"** option and finished with the **'finish'** button.

![image-5](https://github.com/ics-scada/Honeypot/blob/main/İmages/5.PNG)![image-6](https://github.com/ics-scada/Honeypot/blob/main/İmages/6.PNG)

This is how we give the characteristics for Honeypot.

![image-7](https://github.com/ics-scada/Honeypot/blob/main/İmages/7.PNG)

After the configuration on the virtual machine, TPOT is started for installation.

![image-8](https://github.com/ics-scada/Honeypot/blob/main/İmages/8.PNG)

Continue with selecting the first option on the incoming Boot screen. 

![image-9](https://github.com/ics-scada/Honeypot/blob/main/İmages/9.PNG)

By selecting the region, the installation continues.

![image-10](https://github.com/ics-scada/Honeypot/blob/main/İmages/10.PNG)

You can continue by selecting the keyboard type you are using from the keyboard settings section.

![image-11](https://github.com/ics-scada/Honeypot/blob/main/İmages/11.PNG)

The T-pot installer will automatically select a debian archive mirror to download the packages. We choose the debian archive to download the packages required for the T-pot installation.

![image-12](https://github.com/ics-scada/Honeypot/blob/main/İmages/12.PNG)
![image-13](https://github.com/ics-scada/Honeypot/blob/main/İmages/13.PNG)

Since there is no proxy, the installation continues by saying **"Continue"**.

![image-14](https://github.com/ics-scada/Honeypot/blob/main/İmages/14.PNG)

There are pre-built and ready-made installation types available. Since I want to install industrial tpot, choose industrial and continue.

![image-15](https://github.com/ics-scada/Honeypot/blob/main/İmages/15.PNG)

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

![image-16](https://github.com/ics-scada/Honeypot/blob/main/İmages/16.PNG)

Now we create a username to access T-pot's web interface.

![image-17](https://github.com/ics-scada/Honeypot/blob/main/İmages/17.PNG)

We set a password for the user we have given for the web interface.

![image-18](https://github.com/ics-scada/Honeypot/blob/main/İmages/18.PNG)

Then the installation starts, this part may take a while.

![image-19](https://github.com/ics-scada/Honeypot/blob/main/İmages/19.PNG)

For our user name tsec, we also provide the password that we created for tsec.

![image-20](https://github.com/ics-scada/Honeypot/blob/main/İmages/20.PNG)

Installation is complete. T-pot is now active. We can enter from the given IP addresses to enter the web interface.

![image-21](https://github.com/ics-scada/Honeypot/blob/main/İmages/21.PNG)

By entering the username and password we have given for the web interface, we open the T-pot interface.

![image-22](https://github.com/ics-scada/Honeypot/blob/main/İmages/22.PNG)

This is how the Web interface is. The Web interface is connected via Port 64297. It is connected to the Admin panel from Port 64294

![image-23](https://github.com/ics-scada/Honeypot/blob/main/İmages/23.PNG)
