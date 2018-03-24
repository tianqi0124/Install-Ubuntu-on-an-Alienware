# Install-Ubuntu-on-an-Alienware
How to install ubuntu on a Alienware

Step 1: create a bootable Ubuntu USB stick on Windows 10

Step 1.1 : Download ubuntu 16.04 from the wbesite https://www.ubuntu.com/download/desktop

step 1.2 : Download and install UltraISO

step 1.3 : Plug in a 4GB+ USB stick

step 1.4 : Open UltraISO and open Ubuntu 16.04 iso

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/1.jpeg)

step 1.5 : UltraISO -> Bootable -> Write Disk Image

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/2.png)

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/3.png)

step 1.6 (not necessary): After writing, press Xpress Boot->Write New Drive Boot Sector -> Syslinux


Step 2: Create a new SSD partition for Ubuntu

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/4.png)

This depends on your disk, it is better more than 100G.

Step 3: change BIOS settings

step 3.1: Reboot, press F2 into BIOS interface.

step 3.2: Swith to Advance Panel, change SATA Operation to AHCI fromn RAID on.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/8.jpeg)

Step 3.3: Swith to Boot Panel, Change secure boot to disabled.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/9.jpeg)

(The Boot Option #1 is ubuntu is because that I have install ubunutu on my machine.)

step 4: install Ubuntu 16.04

Step 4.1:Reboot, press F12 to boot USB stick.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/14.JPG)

just click on install Ubuntu.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/5.png)

I do not recommand to mark the two.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/6.png)

click on something else

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/7.png)


Step 4.2:Create some partitions for installing.

1. (/swap) mount point, this means the virtual memory, if your memory is less than 8G, you should double it. If your memory is 4G, you can set it to 8000M, and if your memory is 16G, set it to 16000M.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/16.png)


2. (/ ) mount point, from several GB to 20G is Ok, it depends on your disk.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/17.png)

3. (/home) mount point, the rest space.

![image](https://github.com/tianqi0124/Install-Ubuntu-on-an-Alienware/blob/master/image/15.png)

4. Device for boot loader installtion:

you can select where your windows boot.

