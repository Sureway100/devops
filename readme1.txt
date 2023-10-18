chocolatey is a tool in windows to install software through command lines
- choco install notepad++

https://chocolatey.org/install
open powershell in admin mode, check if execution policy is restricted annd
enable it.
then run the link to download chocolatey.

so any software you want to download, just look for it on chocolatey and 
copy the cmd given

.
.
.
.
- installing tools or software
#note while install sublime and encounter an error, you can use --force


-
-
-
-
-
-virtualization
#one computer does job of many computers (multiple OS)
life before virtualization, if you have 10 running services, then you provision 
more than 10 servers.

#hypervisors helps us create virtual machines and we have two types -> type 1 (bare metal) runs a the base OS 
and type 2, runs as a software like virtualbox.
type 1 for production and type 2 for test


#vagrant automates or manages VM lifecycles and this helps us solve this 
problem from manual management
- OS installation
- time consuming
- manual => human error
- tough to replicate multi vms


BUT WITH VAGRANT, WE HAVE -> 
- vm images/ box
- free box available on bagrant cloud

- manage all vm settings in a file
- provisioning
- simple commands like vagrant up etc