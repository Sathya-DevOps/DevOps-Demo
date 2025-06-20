# DevOps-Demo
DevOps with Multi Cloud by SATISH @ Sathya Technologies, Ameerpet, Hyd. Ph. No: +91-91009 20092, +91-76718 52096.




                                # Linux Servers
                                                   
## Unix Distributions:
----------------------------
   * Solaris (SUN-OS) , MAC (Apple), AIX (IBM), HP-UX (HP-Corp)
   * System-V (AT&T Bell Labs),  Linux (Linus Torvald),
   * BSD Unix (Berkley Software distribution),  ...

## Linux Distributions:
----------------------------
   * Redhat, Ubuntu, Centos, Gentoo, Slackware, Fedora, 
   * Debain, SuSE , Amazon Linux, Open Linux, Berkeley Linux
   * Oracle Enterprise Linux, Turbo Linux, Mint Linux, ....



   #### 1.Virtual Box
   #### 2.VM-Ware
   #### 3.Vagrant
   #### 4.Cloud (AWS, Google, Azure, IBM, Rackspace, Oracle cloud...)



                                ##  AWS-EC2 Instance
                                ------------------------
                               * create a free AWS account   
                               * select "services" --> "compute"
                               * select "EC2" (Elastic compute cloud)
                               * select "Launch Instance"

  Step-1: Name and tags --> Redhat server

  Step-2: Application and OS Images --> Redhat9
 
  Step-3: Instance type  --> t2.micro (1 core, 1 gb RAM)

  Step-4: Key pair (login) --> create a New Key

  Step-5: Create security group --> allow "SSH, HTTP, HTTPS" traffic

  Step-6: Configure storage : 10 gb

  Step-7: Number of instances : 1



### Install Git-Bash:
------------------------
 Google --> "Git for Windows"  --> download and Install git-bash

     https://git-scm.com/download/win

### Connect to Linux Server:
------------------------------------        
  $ cp ~/Downloads/DEVOPS_9AM.pem ~/Desktop/
  $ ssh -i "DEVOPS_9AM.pem" ec2-user@ec2-compute.amazonaws.com


                                     ### Linux Commands
                                   ----------------------------
    $ cat /etc/os-release
    $ whoami
    $ date
    $ cal
    $ cal 2027
    $ cal may 2029
    $ pwd
    $ clear
    $ sudo su -    --> to switch to root user



