StarAgile : 

Start Date : 7th Apr. 2025

Module 2 :

Module 2: Linux Fundamentals

• Overview of Linux
• Linux Architecture
• Linux Distributions
• Basic Linux Commands
• File Permission Management
• User Creation
• Shell Scripts
• SSH and VI Utility


######################
Day 1 : 7th Apr. 2025
######################

• Overview of Linux

Linux is an Operating System :

	OS is an interface between the underlying hardware and Applications
	
Why Linux ?

	Linux Operating System 
		- Open-Source 
		- Is Secured 
		- Linux OS was created based on the Unix Operating System 
		- Is an interface between the user applications and underlying Hardware.
		- Linux OS is based on the Command User Interface
		- Core of Linux OS is called kernel!
			Components of Linux OS Architecture
				- Networking 
				- Storage 
				- IPC - Inter Process Communication
				- User Management 
				- Security Management 
				- Control Groups 
				- Namespace 
				- Process 

		- Command Line Interface 
		
		- Linux Distributions :::
		
			- Flavors of Linux OS 
			
				- Centos / RHEL 
				- Debian / Ubuntu 
				- Fedora
			
				
			Package Management - Package Managers :::
				- Package Managers are used to install/Uninstall/Upgrade the Packages/software 
			
					- Centos / RHEL 		===> 	yum package Manager 
					- Debian / Ubuntu 		===>	apt/apt-get package Manager 
					- Fedora				===>	dnf (Latest Version of Fedora)
													yum (Previous Version of Fedora)
													
				- Package Managers can be executed only by the root user on Linux
				
					- TO work with Package Manager :
						- Elevate the Access to Root Level 
							- sudo -i			# This Command is used to elevate the access to root level

	Learn Linux on DevOps Perspectives :
	
		What the Role of DevOps Team/Engineer on Linux.
		
			- All the DevOps Tools can be installed and Managed in Linux Machines 
		
		What is your role here ????
		
			- Install all the DevOps Tools 
			- Package Management - Periodically Upgrade/Uninstall - Backup of the Tools
			- Managing Remote Servers 
				- Client Server Architecture 
				- Server1 (VM)
					- Client1,2,3,4,5,6
					
			- As a DevOps Team we can Manage the Linux Machines
			
				- Package Management 
				- File Management 
				- User Management 
				- Access Ma-nagement 
				 Remote Servers Management 
				- Process Automation(Shell Scripting)
				
	Working with Linux :
		
		Package Management :::
		
		- Basic Linux Commands 
		
			Package Manager - apt/yum/dnf ==> can e executed as a root user.
			
		- Linux Distributions 
				
			Packages can be managed based on the Distributions 
			
		
		- Package Management :::

			- Package Managers are used to install/Uninstall/Upgrade the Packages/software 
		
				- Centos / RHEL 		===> 	yum package Manager 
				- Debian / Ubuntu 		===>	apt/apt-get package Manager 
				- Fedora				===>	dnf (Latest Version of Fedora)
												yum (Previous Version of Fedora)
												
			- Package Managers can be executed only by the root user on Linux
			
				- TO work with Package Manager :
					- Elevate the Access to Root Level 
						- sudo -i			# This Command is used to elevate the access to root level
		
		sudo -i
		
		yum install git 


			- To Install any tool/package :
			
				Install Pre-requisites	
				Install Actual Tool
				Post Installation Actions				
		
		git   - tool
		
		tomcat/nginx/jenkins/ - WAS 
		
					Eg.: Tomcat :::: 
					
						Install Pre-requisites			===> jdk 
						
						Install Actual Tool				===> Installed Tomcat 
						
						Post Installation Actions		===> Started Tomcat 
		
		
			How to Install/Manage Packages ? :::
			
			- Elevate the Access to Root Level
				sudo -i 					# This Command is used to elevate the access to root level
				
			- apt update 					# Used update the default packages
			
			- apt install openjdk-11		# Install Java Package 
			
			- Linux Application Service(nginx/Jenkins) 		
			
				- Start / Stop / Enable / Status / restart 
				
				systemctl status nginx 
				
				systemctl start nginx
				
				systemctl stop nginx
				
				systemctl enable nginx		# Used to define the service as as start up service
		
				systemctl disable nginx		# Used to remove the service from the start-up task list
				
				systemctl restart nginx 
				
			- apt install git				# Install git 
			
			- apt remove git 				# Uninstall git 
			
			- apt upgrade git 				# Used to upgrade git
		

		
			Package :
			
				- Stand-alone Tool			Eg.: git
				- Service					Eg.: tomcat/nginx/jenkins/docker 
		
			which nginx						# Used to get the path of installation ?
			
			which get 
			
			git --version
			
			
Working with Linux Package Management :::

	-	Lab ::: AWS Cloud Platform
				Create Virtual Machines (Ubuntu - previous version)
