[alt text](https://i.imgur.com/jZqMXmu.png)
hostname whoami /user ping -4 Win10-02

[alt text](https://i.imgur.com/THMoH9k.png)
hostname whoami /user ping -4 Win10-01

[alt text](https://i.imgur.com/frmDApI.png)

In this lab, I created and configured a virtual machine (VM) called Win10-Template using VMware Workstation Pro, and then installed Windows 10 Enterprise Edition on the virtual machine.  I also installed Guest Addition tools and configured the virtual machine.

I performed Sysprep (System Preparation) on the Win10-Template VM and setup Win10-01 and Win10-02 VMs by cloning the Win10-Template VM.

Sysprep is used to clone an existing Windows installation across multiple PCs.  Cloning Microsoft Windows without first running Sysprep would be problematic because Windows 10, Windows Server and other versions of Microsoft Windows include security identifiers (SIDs) that must be unique from one computer to the next.  Sysprep generalizes Windows by removing the security identifiers and other computer-specific information.  
