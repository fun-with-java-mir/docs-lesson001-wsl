created: 05092025
# docs-lesson001-wsl
documentation for tutorials about WSL

command: **wsl --list --online** 
| NAME                          | FRIENDLY NAME                  |
| :---------------------------- | :----------------------------- |
| AlmaLinux-8                   |  AlmaLinux OS 8                |          
| AlmaLinux-9                   |  AlmaLinux OS 9                |          
| AlmaLinux-Kitten-10           |  AlmaLinux OS Kitten 10        |                  
| AlmaLinux-10                  |  AlmaLinux OS 10               |           
| Debian                        |  Debian GNU/Linux              |            
| FedoraLinux-42                |  Fedora Linux 42               |           
| SUSE-Linux-Enterprise-15-SP6  |  SUSE Linux Enterprise 15 SP6  |                        
| SUSE-Linux-Enterprise-15-SP7  |  SUSE Linux Enterprise 15 SP7  |                        
| Ubuntu                        |  Ubuntu                        |  
| Ubuntu-24.04                  |  Ubuntu 24.04 LTS              |            
| archlinux                     |  Arch Linux                    |      
| kali-linux                    |  Kali Linux Rolling            |              
| openSUSE-Tumbleweed           |  openSUSE Tumbleweed           |               
| openSUSE-Leap-15.6            |  openSUSE Leap 15.6            |              
| Ubuntu-20.04                  |  Ubuntu 20.04 LTS              |            
| Ubuntu-22.04                  |  Ubuntu 22.04 LTS              |            
| OracleLinux_7_9               |  Oracle Linux 7.9              |            
| OracleLinux_8_10              |  Oracle Linux 8.10             |             
| OracleLinux_9_5               |  Oracle Linux 9.5              |

**AlmaLinux** 
In old times was released **RedHat** linux as server side OS from Red Hat company, it was based on RHEL packages (.rpm), with payed support and priced licenses. From this RHEL basics was derived **Fedora** as community project for common users (experienced) and other free version maintained by RedHat was called **Centos** (scientific linux) with long term updates and focus to security. When I used it, main repositories were based on CERN servers. This version was best choice for low cost companies. But around 2020 redHat changed development policy and stability was dropped out. Business needs stability and for that was released new community edition AlmaLinux. Alma linux is quite good choice for clouds.

https://almalinux.org/  
<img width="1339" height="612" alt="image" src="https://github.com/user-attachments/assets/be96dfeb-7f86-406c-acbb-2974202d4160" />

https://www.fedoraproject.org/
<img width="1314" height="1012" alt="image" src="https://github.com/user-attachments/assets/29350367-66d9-411f-ab2c-c582e1c473a8" />

https://www.centos.org/
<img width="1295" height="481" alt="image" src="https://github.com/user-attachments/assets/aa0101e4-b8c7-43c1-b80d-a740555bfc5a" />

https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux
<img width="1451" height="623" alt="image" src="https://github.com/user-attachments/assets/c983b3b0-ea70-4415-82e8-383f3817b95f" />

**Debian**
In old times was built Debian as father of all distributions which are using .deb packages. Theoretically is used in business as stable alternative for redhat, but in fact I lived in redhad world and never used him on production environment. When I tried him, I had issues with drivers and administration from console. But we van beleive that it is good distro :-) Later used him Caonical from South Africa to build most fames OS **Ubuntu** At start was ubuntu small and efective OS with many small tools, it was using Gnome2 as default gui, they started with cloud storage for free and extesion for money, tot of users love them and made tutorials. And then came Gnome3 :-) I hate it and I am not objective, but in time they removed small tools and tends to big universal system for everybody without knowlege and effort of thinking. Maybe for this sentiment, that Ubuntu was start distribution for many people, this OS is used on clouds in server version. And yes it is quite stable. 

https://www.debian.org/
<img width="1145" height="1009" alt="image" src="https://github.com/user-attachments/assets/1366ae43-d634-4c08-a648-b72715062870" />

https://ubuntu.com/desktop - funfact: antivirus detected some malicious js on their homepage :-)
<img width="1392" height="602" alt="image" src="https://github.com/user-attachments/assets/c5df69ac-ddd7-4608-8dc8-37a2399ff9be" />

**openSUSE**
Like always in old times (I so old :-)) started project based on .rpm packages like redHat but with own repositories. After some time it was covered by Novell, famous network company which bring into suse tools for graphical settings on HW and network, when I used it it was haven after revriting configs on ubuntu in console. Time goes on and Suse linux evolved into independent company which delivers enterprice version for business **SUSE-Linux-Enterprise**, opensource version **openSUSE-Leap** for users on desktop and **openSUSE-Tumbleweed** for geeks. All distributions has server lightweight version for clouds. 

https://www.suse.com/products/server/
<img width="937" height="700" alt="image" src="https://github.com/user-attachments/assets/9a1fca55-8f08-496d-afdb-15ab5189d13b" />

https://get.opensuse.org/desktop/
<img width="2239" height="702" alt="image" src="https://github.com/user-attachments/assets/dd27c9b1-a9e4-42b2-b5ec-ff7ddc20f0e2" />


**kali-linux**
It is OS based on debian, practically it is some cyber security distribution with 600 tools for monitoring systems and network, I am not sure if it is good choice for WSL, because wsl is little defensive in crossing line between linux and windows. 

https://www.kali.org/
<img width="1149" height="474" alt="image" src="https://github.com/user-attachments/assets/7f47517b-7045-45af-b9c1-5e283c77ac69" />

**archlinux**
It is hardcore system, with own packaging mechanism and without mainstream software support. When you want something besides command line, you have to write or reuse compile scripts and install it manually. It can be faster than light beam but that effort and time spended on maintanance will be for yung and enthusiastic people. And times when I recompiled graphic drivers every month and new distro every hal year are in long past away.

https://archlinux.org/ - dont expect pictures :-)
<img width="1897" height="530" alt="image" src="https://github.com/user-attachments/assets/4e8c495f-cd99-4cf3-86f0-8595e323479f" />


**OracleLinux**
One of OS that I never used (and I tried almost everything, even solaris :-)) Oracle developed system compatible with RHEL and used for his applications in cloud and oracleDB. It is eneterprice version for business = stable and secure, pricing is for support and it can be needed when you try some unexpected applications. Common user has no reason to use it.

https://www.oracle.com/linux/
<img width="1397" height="626" alt="image" src="https://github.com/user-attachments/assets/b1dfcf35-7161-4622-9032-09ee68efcf51" />
