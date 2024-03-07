# Report
Fill your observations here.

## Part 1:

1) Host Operating System : Windows
   Guest Operating System : Ubuntu
   Hypervisor Used : VirtualBox

2) Size of the virtual disk on host : 20.1 GB
   Size of the file system VM sees : 19.6 GB

3) 2-3 min approx

4) Networking option : 
   IP Address Host : 10.0.0.141
   IP Address VM : 192.168.16.145

5) RAM : 1GB
   Disk Size : 20.1GB

6) There are a number of configurations that I observed while setting uo the VM Virtual Box. Some of   these options include:

*Virtual machine hardware specifications, such as the amount of memory and number of virtual CPUs   allocated to the VM.

*The storage configuration for the VM, including the size and type of virtual hard disk, and whether the disk is dynamically or fixed in size.

*Network configuration, such as the type of network adapter used by the VM, and whether the VM has a dedicated IP address or shares an IP address with the host machine.

*Configuration of virtual devices such as CD/DVD drives, USB controllers, or graphics cards.

*Boot options, such as the order of boot devices and the boot mode (BIOS or UEFI).

*Integration with the host operating system, such as whether to enable copy and paste or drag and drop functionality between the host and guest systems.

7) A dual-boot machine is a computer system that has two separate operating systems installed on the same hard drive, allowing the user to choose which operating system to use when starting up the machine. For example, a computer could have both Windows and Linux installed, and the user could choose to boot into either one of them when starting up the computer.

On the other hand, type-2 virtualization, which was used in this lablet, is a method of running multiple operating systems simultaneously on the same physical machine. With type-2 virtualization, a virtual machine (VM) is created on the host machine, and the guest operating system is installed on the VM. The host machine's operating system continues to run in the background, and the user can switch between the host and guest operating systems as needed.

The key difference between dual-boot machines and type-2 virtualization is that with a dual-boot machine, only one operating system can be used at a time, and the user needs to restart the computer to switch between operating systems. With type-2 virtualization, multiple operating systems can be run simultaneously without the need to restart the host machine, making it a more flexible and convenient option for running multiple operating systems on the same physical machine.

## Part 2:

1) Host OS: Windows

2) multipass 1.11.1+win
   multipassd 1.11.1+win

3) I've attached the screenshot that I got. I was unable to copy paste data from VM to my Main machine.

4) I did face some installation issues. My system was taking way too long to perform the configurations.




## Part 3:

1) Yes, emulation is slower than virtualization because in emulation, the entire software stack of the target system has to be emulated, which adds significant overhead. Virtualization, on the other hand, runs the guest operating system on top of a hypervisor that provides hardware abstraction and resource sharing, resulting in better performance.

2) The lscpu command provides information about the CPU architecture, including the number of processors, the number of cores per processor, the clock speed, and other details. The output of the command may vary depending on the CPU being used, but in general, it will display similar information in both virtualization and emulation. However, some details, such as CPU flags or cache sizes, may be different due to the virtualization layer.

3) The size of the file is 17 GB
   Yes it is different from the vmdk/vdi files in virtualization.

4) CPU utilization under Virtualization : Approx 55%
   CPU utilization under Emulation : Approx 68%


