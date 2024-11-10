# OPNsense
Installing Pfsense on VM - Lab
<img src="https://img.shields.io/badge/Firewall-OPNsense-orange?logo=opnsense&logoColor=white"></img>

## Objective
This lab includes steps for installing OPNsense firewall in a VM for leanring and educational purpose .

### Skills Learned

- What is OPNsense
- Installing OPNsense on VM
- Setting up OPNsense on VM.

### What is OPNsense ?
OPNsense is an open source, easy-to-use and easy-to-build FreeBSD based firewall and routing platform. OPNsense includes most of the features available in expensive commercial firewalls, 
and more in many cases. It brings the rich feature set of commercial offerings with the benefits of open and verifiable sources.

<a href="https://opnsense.org/about/about-opnsense/">About OPNsense</a>

<a href="https://opnsense.org/users/get-started/">Requirements</a>

<a href="https://opnsense.org/download/">Downlaod OPNsense</a>

![image](https://github.com/user-attachments/assets/4fc503e1-cf4a-443b-8eac-83001f6b0b8e)


### Tools Used

- OPNsense version24.7 DVD 
- Hypervisor either Vmware or Oracke Virtualbox
- bzip 1.0.5 file extractor Free can be downloaded from <a href="https://gnuwin32.sourceforge.net/packages/bzip2.htm">Download Link</a>

### Extraction Using bzip tool
- install on WIN platfrom or others as per insructions
- ON WIN platform use powershell in admin mode and run command from location where bzip2.exe was installed in my case it was C:\Program Files (x86)\GnuWin32\bin
  - .\bzip2.exe -d "D:\Home_Lab-Softwares\OPNsense-24.7-dvd-amd64.iso.bz2" chnage your downloaed location for OPNsense DVD Image file it will take some time to extarct the ISO file.
    ![image](https://github.com/user-attachments/assets/d40cee1c-6d70-4d2e-b2f0-a411c86e0775)
    
