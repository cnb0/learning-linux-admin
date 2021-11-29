Section 1: Linux Basic Administration
             
Chapter 1: Installing Linux
                    
            The Linux operating system
            Linux distributions
            Choosing the right Linux distribution
            Common Linux distributions
            Linux distributions – a practical guide
            Installing Linux – the basics
            How to install Linux
            Installing Ubuntu
            Installing CentOS
            The Windows Subsystem for Linux (WSL)
            Installing Linux graphical user interfaces
            GNOME
            KDE
            Setting up and using the Linux workstation
            Installing Ubuntu Desktop
            Default software packages
            Additional software packages
            Managing software packages with APT
               

Chapter 2: The Linux Filesystem
             
            Introducing the Linux shell
            Bash shell features
            The shell connection
            The command-line prompt
            Shell command types
            Command structure
            Help from the manual
            The Linux filesystem
            Directory structure
            Working with files and directories
            Understanding file paths
            Basic file operations
            Commands for file viewing
            Commands for file properties
            Using text editors to create and edit files
                   
Chapter 3: Linux Software Management
             
            Linux software package types
            The DEB and RPM package types
            The snap and flatpak package types
            Managing software packages
            Managing DEB packages
            Managing RPM packages
            Using snap and flatpak packages
            Application streams in CentOS 8
            Building a package from source
            The source code file
            Preparing the source code
            Setting up the environment
               
Chapter 4: Managing Users And Groups
             
            Managing users
            Understanding sudo
            Creating, modifying, and deleting users
            Managing groups
            Creating, modifying, and deleting groups
            Managing permissions
            File and directory permissions
               
                 
Chapter 5: Working With Processes, Daemons, And Signals
             
            Introducing processes
            Understanding process types
            The anatomy of a process
            Working with processes
            The ps command
            The pstree command
            The top command
            The kill and killall commands
            The pgrep and pkill commands
            Working with daemons
            Working with SysV daemons
            Working with systemd daemons
            Exploring interprocess communication
            Shared storage
            Shared memory
            Unnamed pipes
            Named pipes
            Message queues
            Sockets
            Working with signals
               
                 
Section 2: Advanced Linux Server Administration
             
Chapter 6: Working With Disks And Filesystems
             
            Understanding devices in Linux
            Linux abstraction layers
            Device files and naming conventions
            Understanding filesystem types in Linux
            The Ext4 filesystem features
            The XFS filesystem features
            The btrfs filesystem features
            Understanding disks and partitions
            Common disk types used
            Partitioning disks
            Logical Volume Management in Linux
            LVM snapshots
               
Chapter 7: Networking With Linux
             
            Exploring basic networking
            Computer networks
            The OSI model
            The TCP/IP model
            TCP/IP protocols
            IP addresses
            Sockets and ports
            Linux network configuration
            Working with networking services
            DHCP servers
            DNS servers
            Authentication servers
            File sharing
            Printer servers
            File transfer
            Mail servers
            NTP servers
            Remote access
            Understanding network security
            VPNs
            Working with VPNs
            Setting up OpenVPN
               
                 
Chapter 8: Configuring Linux Servers
             
            GitHub
                   
Chapter 9: Securing Linux
             
            Understanding Linux security
            Introducing SELinux
            Working with SELinux
            Introducing AppArmor
            Working with AppArmor
            Final considerations
            Working with firewalls
            Introducing netfilter
            Working with iptables
            Introducing nftables
            Using firewall managers
               
                   
Chapter 10: Disaster Recovery, Diagnostics, And Troubleshooting
             
            Planning for disaster recovery
            A very short introduction to risk management
            Risk calculation
            Designing a disaster recovery plan
            Backing up and restoring the system
            Disk cloning solutions
            Introducing common Linux diagnostic tools for troubleshooting
            Tools for troubleshooting boot issues
            Tools for troubleshooting general system issues
            Tools for troubleshooting network issues
            Tools for troubleshooting hardware issues
               
Section 3: Cloud Administration
             
Chapter 11: Working With Containers And Virtual Machines
             
            Introduction to virtualization on Linux
            Efficiency in resource usage
            Introduction to hypervisor
            Understanding VMs
            Choosing the hypervisor
            Understanding Linux containers
            Containers versus VMs
            Understanding the underlying container technology
            Understanding Docker
            Working with Docker
            Which Docker version to choose?
            Installing Docker CE
            Using the Docker commands
            Managing Docker containers
            Deploying a containerized application with Docker
                   
Chapter 12: Cloud Computing Essentials

            Introduction to cloud technologies
            Understanding the need for cloud computing standards
            Knowing the architecture of the cloud
            Knowing the key features of cloud computing
            Short introduction to OpenStack
            Introducing IaaS solutions
            Amazon EC2
            Microsoft Azure Virtual Machines
            Other strong IaaS offerings
            Introducing PaaS solutions
            Amazon Elastic Beanstalk
            Google App Engine
            DigitalOcean App Platform
            Red Hat OpenShift
            Cloud Foundry
            The Heroku platform
            Introducing CaaS solutions
            Introducing the Kubernetes container orchestration solution
            Deploying containers in the cloud
            The rise of micro operating systems
            Introducing microservices
            Introducing DevOps
            Introducing cloud management tools
               
                   
Chapter 13: Deploying To The Cloud With AWS And Azure
                     
            Working with AWS EC2
            Creating AWS EC2 instances
            Using AWS EC2 instances
            Working with the AWS CLI
            Working with Microsoft Azure
            Creating a virtual machine
            Managing virtual machines
            Working with the Azure CLI
                   
Chapter 14: Deploying Applications With Kubernetes
             
            Understanding the Kubernetes architecture
            Introducing the Kubernetes object model
            The anatomy of a Kubernetes cluster
            Installing and configuring Kubernetes
            Installing Kubernetes on desktop
            Installing Kubernetes on virtual machines
            Running Kubernetes in the cloud
            Working with Kubernetes
            Using kubectl
            Deploying applications
               
Chapter 15: Automating Workflows With Ansible
             
            Introducing Ansible
            Understanding the Ansible architecture
            Introducing configuration management
            Installing Ansible
            Installing Ansible on Ubuntu
            Installing Ansible on RHEL/CentOS
            Installing Ansible using pip
            Working with Ansible
            Setting up the lab environment
            Configuring Ansible
            Using Ansible ad hoc commands
            Using Ansible playbooks
            Using templates with Jinja2
            Using roles with Ansible Galaxy