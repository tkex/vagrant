# vagrant

Vagrantfiles exploitation boxes

Files for creating VMs in blazing speed with Vagrant. For this case older images (operating systems) have been used for the purpose of analyzing various vulnerability scanners on different system environments (MS Windows Server 2012 R2 Standard x64 + Ubuntu 16.04 LTS x64).

- Vagrant: https://www.vagrantup.com/
- Oracle VM VirtualBox: https://www.oracle.com/de/virtualization/technologies/vm/downloads/virtualbox-downloads.html
- Login (if not explicit changed): vagrant (username) and vagrant (password)

# Quick setup:

- Each Vagrantfile should be placed into a folder and optimally (re)named to 'Vagrantfile'
- CMD 'vagrant up' to set up the VM
- Images and possible additional packages or dependencies will be downloaded (can take a while)
- VMs can be accessed over VirtualBox, SSH or RDP dependend on the chosen OS and configuration
