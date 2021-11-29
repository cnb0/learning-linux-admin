### 1. Introduction And Environment Setup

            Understanding and choosing a distribution
            Ubuntu
            Debian
            CentOS - the one we'll mostly be using
            Red Hat Enterprise Linux
            Installing VirtualBox
            Installing VirtualBox on Ubuntu
            Command-line installation
            Graphical installation
            Installing VirtualBox on macOS
            Command-line installation
            Graphical installation
            Installing VirtualBox on Windows
            Graphical installation
            Installing our chosen distribution manually
            Obtaining our CentOS installation media
            Checking the checksum
            Setting up our VM
            VirtualBox main window
            CentOS installation
            Accessing and updating our VM
            Logging in from the VirtualBox window
            Logging in from the host Terminal
            Making sure sshd is running
            Making sure that VirtualBox lets us through
            Updating our VM
            Understanding how VMs differ
            dmidecode
            lshw
            Quick sudo explanation
            Using Vagrant to automatically provision VMs
            Kickstart
            Vagrant
            Anecdote - try, try, and try again

### 2. Remote Administration With SSH

            Generating and using key pairs with ssh-keygen
            RSA example
            Ed25519 example
            The public and private key files
            The authorized_keys file
            To passphrase or not to passphrase
            Additional flags
            SSH client arguments and options
            SSH using hostnames instead of IPs
            SSHing to a different user
            SSHing to a different port
            SSHing to an IPv6 address
            SSHing before running a command
            SSH and X11 forwarding
            Using a client-side SSH configuration file
            Modifying the server-side SSH configuration file
            Changing the default port
            Changing the listen address
            Changing the daemon logging level
            Disallowing root login
            Disabling passwords (force key use)
            Setting a message of the day (motd)
            The UseDNS setting
            AllowUsers
            Rotating host keys and updating known_hosts
            Using local forwarding
            On the command line
            Using an SSH config file
            Watching our SSH session
            Connecting to systems beyond the remote host
            Using remote forwarding
            On the command line
            Using an SSH config file
            ProxyJump and bastion hosts
            Using an SSH config file
            Multiple hosts
            ProxyCommand
            Bastion hosts
            Using SSH to create a SOCKS Proxy
            On the command line
            Using an SSH config file
            Understanding and using SSH agents
            ssh-add
            AddKeysToAgent
            Running multiple SSH servers on one box
  
### 3. Networking And Firewalls
            
            Determining our network configuration
            Discerning the IP
            Discerning the IP (deprecated method)
            Discerning the gateway address
            Discerning the gateway address (deprecated method)
            Checking connectivity
            Checking what route our box will take
            More examples of using the ip suite
            Adding and removing an IP against an interface
            Shutting down and bringing up an interface administratively
            Adding a new route to our routing table
            Adding and configuring network interfaces
            Configuring a new interface
            Modern domain name resolution on Linux
            Querying a domain
            Checking the domain resolution settings
            Changing the domain resolution settings
            Configuring NTP and the problems we face
            Checking if NTP is running
            Checking if NTP traffic is flowing
            Enabling an NTP client
            Enabling an NTP server
            Listing firewall rules on the command line
            iptables
            firewall-cmd
            ufw
            Adding and removing firewall rules on the command line
            firewall-cmd
            iptables
            ufw
            Determining the running services and ports in use
            Debugging with iftop

### 4. Services And Daemons
                   
            Determining running services
            Listing installed services
            Starting and stopping services
            Stopping our service
            Starting our service
            Changing which services start and stop at boot
            Enabling our service
            Disabling our service
            Common services you might expect to see
            auditd.service
            chronyd.service
            crond.service
            lvm2-*.service
            NetworkManager.service
            nfs.service
            postfix.service
            rsyslog.service
            sshd.service
            systemd-journald.service
            systemd-logind.service
            Understanding service unit files
            Customizing systemd unit files
            Testing running services
            Writing a basic unit file
            Working with systemd timers (and cron)
            systemd timers
            cron
            Other init systems
            CentOS 6 and Upstart
            Debian 7 and SysV init
            Round-up - services and daemons

### 5. Hardware And Disks
    
            Determining hardware
            lspci
            lshw
            /proc
            /sys
            dmesg (and the kernel logs)
            dmidecode
            /dev
            Testing hardware
            Self-monitoring, analysis, and reporting technology (SMART)
            hdparm
            Memory testing
            The role of the kernel
            Disk configuration on Linux
            Listing disks with lsblk
            Listing mount points with df
            Listing filesystems with df
            Listing logical volume manager disks, volume groups, and logical volumes
            Physical disks
            Volume groups
            Logical volumes
            Listing swap
            The filesystem hierarchy
            Configuring a blank disk and mounting it
            Re-configuring a disk using LVM
            Using systemd-mount and fstab
            fstab
            systemd-mount
            Disk encryption and working with encryption at rest
            Current filesystem formats
            Upcoming filesystem formats
            Round-up - hardware and disks

### 6. Security, Updating, And Package Management
    
            Checking package versions
            CentOS
            Debian
            Checking the OS version
            CentOS
            Debian
            Ubuntu
            Checking for updates
            CentOS
            Debian
            Automating updates
            CentOS
            Debian
            Automatic provisioning
            Checking mailing lists and errata pages
            Package changelogs
            Official sources and mailing Lists
            Other sources
            Using snaps
            Searching out snaps
            Installing snaps
            Listing installed snaps
            Interacting with daemon snaps
            Removing snaps
            Using Flatpak
            Searching for a package
            Installing our package
            Running our package
            Listing installed packages
            User installations
            Removing packages
            Using Pip, RubyGems, and other package managers
            Pip
            RubyGems
            When to use programming-language package managers
            --user/ --system (pip) and --user-install (gem)
            Python virtualenv
            Dependency hell (a quick word)
            System-installed and third-party installed versions of Pip
            Dependency problems in conflicting Pip packages
            Apt's conflict solution
            Potential solutions

### 7. Compiling from source

            Adding additional repositories
            CentOS - Adding the EPEL repository with epel-release
            CentOS - Adding the ELRepo repository by file
            Debian - Adding additional repositories
            Ubuntu - Adding PPAs
            Roundup - security, updating, and package management


### 8. Monitoring And Logging
    
            Reading local logs
            Using journalctl on systemd systems
            Centralizing logging
            Remote logging with rsyslog - UDP example
            Remote logging with rsyslog - TCP example
            Remote logging with journald
            Local resource measuring tools
            top
            free
            htop
            NetData
            Local monitoring tools
            atop
            sar
            vmstat
            Remote monitoring tools
            Nagios
            Icinga2
            Centralizing logging with the Elastic Stack
            centos2
            debian1 and debian2
            Kibana
            Roundup - Monitoring and Logging

### 9. Permissions, SELinux, And AppArmor
    
            Linux file permissions
            exampledir
            examplefile
            Root access to directories and files
            Other execute characters
            Modifying file permissions
            chown
            chmod
            chattr
            chown
            chmod
            chattr
            Avoiding octal notation (if you hate it) in chmod
            Hierarchical permissions
            Users and groups
            whoami
            Users on a system
            Groups on a system
            Daemons using users
            AppArmor and modification
            SELinux and modification
            Checking SELinux is running, and the importance of keeping it running
            Resetting SELinux permissions
            Roundup - permissions, SELinux, and AppArmor

### 10. Containers And Virtualization
    
            What is a container?
            cgroups (Linux control groups)
            namespaces
            The breakdown of our creation
            The LXD daemon
            Installing Docker
            Slightly more
            Running your first Docker container
            Creating a container
            Listing our container
            Executing commands in our container
            Stopping our container
            Debugging a container
            Searching for containers (and security)
            What is virtualization?
            Starting a QEMU machine with our VM
            Using virsh and virt-install
            virt-install
            virsh
            Comparing the benefits of local installs, containers, and VMs
            Local Nginx install
            Docker Nginx install
            VM Nginx install
            Brief comparison of virtualization options (VMware, proxmox, and more)
            VMware ESXi
            Proxmox Virtual Environment
            OpenStack
            Roundup - containers and virtualization

### 11. Git, Configuration Management, And Infrastructure As Code
    
            What is Git?
            Cloning
            Exploring and making changes
            Setting up a Git server
            Committing to our Git repository
            Matching versus simple
            Branching our Git repository and committing changes
            Installing Ansible
            The raw module
            The shell and command modules
            Using Ansible to install Java from a role
            Storing our Ansible configuration in Git
            Exploring options for IaC
            Terraform
            Packer
            Roundup - Git, Configuration Management, and Infrastructure as Code

### 12. Web Servers, Databases, And Mail Servers
    
            Installing and understanding a web server
            Installing httpd (Apache) on CentOS
            Installing Nginx on Debian
            Basic Apache configuration
            Basic Nginx configuration
            SSL, TLS, and LetsEncrypt
            Let's Encrypt
            Work environment certificates
            Basic MySQL or MariaDB Installation
            Listing, creating, and selecting databases and tables
            Basic PostgreSQL installation
            Listing, creating, and selecting databases and tables
            Local MTA usage and configuration (Postfix)
            main.cf
            /etc/aliases
            Local MTA usage and configuration (Exim)
            NoSQL documents (MongoDB example)
            NoSQL KV (Redis example)
            Messaging brokers and   s (RabbitMQ example)
            Roundup - web servers, databases, and mail servers
            Super personal preference time!

### 13. Troubleshooting And Workplace Diplomacy
    
            What is troubleshooting?
            Isolating the real issue
            Giving estimates and deciding on next steps
            Using ss, iftop, tcpdump, and others for network issues
            Ping
            ss
            iftop
            tcpdump
            Using cURL, wget, and OpenSSL for remote web issues
            cURL
            Wget
            OpenSSL
            Using iotop, top, and vmstat for local resource issues
            iotop
            top
            vmstat
            Using ps, lsof, Strace, and /proc for service issues
            ps
            lsof
            Strace
            /proc
            Making a copy of problems for later debugging
            Temporary solutions and when to invoke them
            Handling irate developers
            Handling irate managers
            Handling irate business owners
            Roundup - Troubleshooting and workplace diplomacy
            Don't trust time
            Don't overlook the simple
            On "cloud" deployments
            Learn from my mistakes
            BSDs, Solaris, Windows, IaaS And PaaS, And DevOps
    
### 14. Determining the type of system you're on

            uname
            The filesystem check
            Understanding how the BSDs differ
            The differences
            FreeBSD
            OpenBSD
            Understanding how Solaris and illumos differ
            The differences
            Oracle Solaris
            illumos
            Understanding how Windows differs
            The differences
            IaaS (Infrastructure as a Service)
            IaaS providers and features
            PaaS (Platform as a Service)
            PaaS providers and features
            The Ops versus DevOps Wars
            More of a skirmish, really
            Roundup - BSDs, Solaris, Windows, IaaS and PaaS, DevOps
