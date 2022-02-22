# Ubuntu
![desktop image](desktoppng)
 Ubuntu is a[Linux distribution](https://en.wikipedia.org/wiki/Linux_distribution) based on Debian and composed mostly of free and open-source software.Ubuntu is officially released in three editions: Desktop, Server, and Core for [Internet of things](https://en.wikipedia.org/wiki/Internet_of_things) devices androbots. All the editions can run on the computer alone, or in a virtual machine. Ubuntu is a popularoperating system for cloud computing, with support for OpenStack. Ubuntu's default desktop has beenGNOME since version 17.10.

 Ubuntu is developed by British company **Canonical**, and a community of other developers, under ameritocratic governance model. Canonical provides security updates and support for each Ubuntu release,starting from the release date and until the release reaches its designated **end-of-life**(EOL) date.Canonical generates revenue through the sale of premium services related to Ubuntu and donations fromthose who download the Ubuntu software. Ubuntu is named after the **Nguni philosophy** of ubuntu, whichCanonical indicates means "humanity to others" with a connotation of *"I am what I am because of who we allare".

## Background 
Ubuntu is built on Debian's architecture and infrastructure, and comprises Linux server, desktop anddiscontinued phone and tablet operating system versions. Ubuntu releases updated versionspredictably every six months, and each release receives free support for nine monthTherecommended system requirements are:s (eighteen months prior to 13.04) with security fixes, high-impact bug fixes and conservative, substantially beneficial low-risk bug fixes. The first release was inOctober 2004.

Current long-term support (LTS) releases are supported for five years, and are released every two years.Since the release of Ubuntu 6.06, every fourth release receives long-term support. Long-term support
whatisubuntu.md12/30/20212/4

includes updates for new hardware, security patches and updates to the 'Ubuntu stack' (cloud computinginfrastructure). The first LTS releases were supported for three years on the desktop and five years on theserver; since Ubuntu 12.04 LTS, desktop support for LTS releases was increased to five years as well. LTSreleases get regular point releases with support for new hardware and integration of all the updatespublished in that series to date

## Features 
A default installation of Ubuntu contains a wide range of software that includes LibreOffice,Firefox,Thunderbird, Transmission, and several lightweight games such as Sudoku and Mines. Manyadditional software packages are accessible from the built in Ubuntu Software (previously UbuntuSoftware Center) as well as any other APT-based package management tools. Many additional softwarepackages that are no longer installed by default, such as Evolution, GIMP, Pidgin, and Synaptic, are stillaccessible in the repositories and installable by the main tool or by any other APT-based packagemanagement tool. Cross-distribution snap packages and flatpaks are also available,that both allowinstalling software, such as some of Microsoft's software, in most of the major Linux operating systems(such as any currently supported Ubuntu version and in Fedora). The default file manager is GNOME Files,formerly called Nautilus.

### Security
Ubuntu aims to be secure by default. User programs run with low privileges and cannot corrupt theoperating system or other users' files. For increased security, the sudo tool is used to assign temporaryprivileges for performing administrative tasks, which allows the root account to remain locked and helpsprevent inexperienced users from inadvertently making catastrophic system changes or opening securityholes. Polkit is also being widely implemented into the desktop. The recommended system requirementsare:ftware into four domains to reflect differences in licensing and the degree of support available. Someunsupported applications receive updates from community members, but not from Canonical Ltd

## Recommended Minimum System Requirements

### Ubuntu Desktop Edition 
1.  GHz dual core processor
2.  4 GiB RAM (system memory)
3.  25 GB (8.6 GB for minimal) of hard-drive space (or USB stick, memory card or external drive but seeLiveCD for an alternative approach)
4.  VGA capable of 1024x768 screen resolution5. Either a CD/DVD drive or a USB port for the installer media6. Internet access is help

### Ubuntu Server Edition
Ubuntu 20.04 Server Edition provides a common, minimalist base for a variety of server applications, suchas file/print services, web hosting, email hosting, etc. This version supports four 64-bit architectures:
. amd64 (Intel/AMD 64-bit)
. arm64 (64-bit ARM)
. ppc64el (POWER8 and POWER9)
whatisubuntu.md
 . s390x (IBM Z and LinuxONE
 The recommended system requirements 

 . CPU: 1 gigahertz or better
 . RAM: 1 gigabyte or more
 . Disk: a minimum of 2.5 gigabytes


### Releases
Version        Code Name            Release Date
_______________________________________________________________________________________________ 
14.04LTS       Trusty Tahr           2014-04-17    
________________________________________________________________________________________________
16.04LTS       Xenial Xerus          2016-04-21      
_______________________________________________________________________________________________                                       
18.04LTS       Bionic Beaver         2018-04-26                                               
________________________________________________________________________________________________

20.04LTS       Focal  Fossa          2020-04-23                                        
________________________________________________________________________________________________

21.04          Hirsute Hippo         2021-04-22                                                
________________________________________________________________________________________________

21.10          Impish Indri          2021-10-14                                              
________________________________________________________________________________________________  
22.04LTS       Jammy Jellyfish       2022-04-21
________________________________________________________________________________________________

### Variants
Ubuntu Desktop (formally named as Ubuntu Desktop Edition, and simply called Ubuntu) is the variantofficially recommended for most users. It is designed for desktop and laptop PCs and officially supportedby Canonical. A number of variants are distinguished simply by each featuring a different desktopenvironment. LXQt and Xfce are often recommended for use with older PCs that may have less memoryand processing power available.

#### Official distributions
Distribution    Distribution   
logo            name   
![kubuntu desktop](desktop.png)kubuntu desktop Kubuntu  An Ubuntu flavour using the KDE interface instead of the GNOME 
________________________________________________________________________________________________
![Lubuntu desktop](desktop.png)Lububtu    Lubuntu    An Ubuntu flavour that is "lighter, less resource hungry and moreenergy-efficient", using the LXQt desktop environmen
________________________________________________________________________________________________
![Ubuntu core desktop](desktop.png)ubuntu core    Ubuntu core   An Ubuntu edition focussed on IoT and embedded systems
________________________________________________________________________________________________
![Ubuntu Budgie desktop](desktop.png)
Ubuntu Budgie   UbuntuBudgie     An Ubuntu flavour using Budgie.
________________________________________________________________________________________________


Distribution       Distribution
logo         name

_
![Ubuntukylin desktop](desktop.png)Ubuntukylin Ubuntu Kylin   An Ubuntu flavour aimed at the Chinese market.
________________________________________________________________________________________________
![Ubuntu Mate desktop](deskto.png)Ubuntu mate  Ubuntu MATE   An Ubuntu flavour using MATE, a desktop environmen.
________________________________________________________________________________________________
![Ubuntu server desktop](desktop.png)
Ubuntu server Ubuntu Serve  Server edition of Ubuntu Desktop with no Desktop Environmen.
________________________________________________________________________________________________
![Ubuntu studio desktop](desktop.png)Ubuntu studio  Ubuntu Studio Based on Ubuntu, providing open-source applications for multimediacreation aimed at the audio, video and graphic editors.
________________________________________________________________________________________________
![xubuntu desktop](desktop.png)Xubuntu  Xubuntu   An Ubuntu flavour using Xfce
## How to update Ubuntu
First, open the terminal in Ubuntu desktop. You can find it in the menu, or use the Ctrl+Alt+T keyboardshortcut. If you are logged on to an Ubuntu server, you already have access to a terminal.In the terminal, you just have to use the following command:sudo apt update && sudo apt upgrade -yThe -y in the end automatically enters “yes” when the command “apt upgrade” ask for your confirmationbefore installing updates. Note that you can also use the two commands separately, one by one.


