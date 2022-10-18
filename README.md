# Virtualisation
## Dev Env
### Vagrant


- check internet connectivity `sudo apt-get update`
- Run upgrade `sudo apt-get upgrade -y`
- Where am i `pwd` give you your current location
- Whomai `uname` or `uname -a`
- How to create a file in linux `touch filename` & `nano filename`
- How to check file/folder available in current location `ls` or to check all files hidden files as well `ls -a`
- How to create a folder `mkdir fodler-name`
- How navigate to the folder `cd folder-name`
- How to navigate back/out `cd ..` or `cd` Enter
- How to delete a file/folder `rm -rf file/foldername`
- Research how to copy file from 1 location to another
- copy test.txt into app folder
- How to navigate between OS & VM `exit` Enter
- for Admin access `sudo` switch to admin user `sudo su`
- change permission `chmod instruction file-name` i.e `chmod 700 test.text`
- Currently running process `top` & `ps aux`
- To remove any process `kill PID` - `kill 7`
- how to delete folder/hidden folder `ls -a`
- print last 3 lines from the test.txt
- print first 3 lines from the test.txt
- print last 10 lines from the test.txt
- print last  lines from the test.txt
- Research how to use `| pipe` & `grep` & `sort`
- The Pipe is a command in Linux that lets you use two or more commands such that output of one command serves as input to the nex
- The grep command will scan the document for the desired information and present the result in a format you want
- The sort command helps in sorting out the contents of a file alphabetically.
- `ps aux` short list by name
- How to create/run a process in the background & foreground, create/run a process in both areas
- kill the process that you created
- Install `nginx` in our VM
- create a `private-network` betweek localhost&vm
- allocate an IP address - for mac users 
- `sudo apt-get install nginx -y`
- How to check a tool/software status in linux `sudo systemctl status nginx`
- How to restart a process in Linux `
- Mac ip ranges `192.168.56.10` `192.168.56.11` `192.168.56.12`
- `vagrant reload` or `vagrant destroy` then `vagrant up`
- `rm -rf .vagrant` then `vagrant up`

## What is Virtualisation?
Virtualization is the process of running a virtual instance of a computer system in a layer separate from the actual hardware.

### Types of Virtualisation
- server
- application
- network
- desktop
- storage

### Benefits of Virtualisation
- Reduced upfront hardware and continuing operating costs
- Minimized or eliminated downtime
- Increased IT productivity and responsiveness
- Greater business continuity and disaster recovery response
- Simplified data center management
- Faster provisioning of applications and resources

## What is Development Environment?
A development environment in software and web development is a workspace for developers to make changes without breaking anything in a live environment. 

## What is Vagrant?
Vagrant is a tool for working with virtual environments, and in most circumstances, this means working with virtual machines. Vagrant provides a simple and easy to use command-line client for managing these environments, and an interpreter for the text-based definitions of what each environment looks like, called Vagrantfiles. 

## What is VirtualBox?
VirtualBox is defined as a tool for virtualizing x86 and AMD64/Intel64 computing architecture, enabling users to deploy desktops, servers, and operating systems as virtual machines..