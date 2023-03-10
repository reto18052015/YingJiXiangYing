XueTr is a free anti-virus&rootkit utility.It offers you the ability to detect, analyze and fix various kernel structure modifications and gives you a wide scope of the kernel.With its help,you can easily spot and remove malwares hidden from normal software.

XueTr currently supports the following Windows 32-bit versions:

Windows 2000 SP4
Windows XP (no SP,SP1, SP2, SP3)
Windows Server 2003 (no SP,SP1,SP2,R2)
Windows Vista (no SP,SP1,SP2)
Windows Server 2008 (no SP,SP1)
Windows 7

Currently,the following features are available:

*Process Manager
View system process and thread basic information.
Detect hidden processes,threads,process modules.
Terminate, suspend and resume processes and threads.
View and manipulate process handles,windows and memory regions.

*Kernel Module Viewer
Display kernel module information including ImageBase,Size,Driver Object,ImagePath,ServiceName and Load Order.
Detect hidden kernel modules.
Unload kernel module(dangerous,never try it on Windows 7).
Dump kernel image memory.
Display and delete system driver service information.

*Hook Detector
View and restore SSDT,Shadow SSDT,sysenter and int2e hooks.
View and restore FSD and keyboard disptach hooks.
View and restore kernel code hooks including kernel inline hooks,patches,IAT and EAT hooks.
View and restore usermode process hooks incluing inline hooks,patches,IAT and EAT hooks.
View and restore message hooks(both global and local).
View and restore kernel ObjectType hooks.
Display Interrupt Descriptor Table(IDT).

*System Callback Viewer
Display and remove Kernel Notifications(Process/Thread/Image/Registry/Lego/Shutdown/Bugcheck/FileSystem/Logon).

*Network Viewer
Display current network connections, including the local and remote addresses and state of TCP connections.
View and delete IE plugins and context menu.
View and restore tcpip dispatch hooks.
Display winsock providers(SPI).
View and edit hosts file.

*Filter Viewer
View and remove filters for common devices including disk,volume,keyboard and network devices. 
 
*Registry Viewer
View and edit system registry.
Detect hidden registry entries using live registry hive analysis.

*File Explorer
Detect hidden files using both disk analysis and driver methods.
View and delete locked files and folders.
View file basic information including NTFS Alternate Data Streams. 

*Autorun Manager
Display and delete common autorun entries.

*Service Manager 
Display Win32 service information (for Ring0 modules,it is included in Kernel Module Viewer).
Change service status and configuration.

*DPC Timer
Enumerate and delete DPC Timer objects.

*Miscellaneous
View and repair common filetype assosications.
View and repair image hijacks.

*Settings
Option to defense from process creation,thread creation,module load and message hook installation.
Option to defense from file creation,registry key creation.
Option to prevent system suspend,log-off,shutdown and reboot.
Option to prevent locking workstation and switching destop.
option to prevent setting system time.

Warning:Use it at your own risk.This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY.


2011-03-02 V0.39:
*Improved kernel hook scan
*Improved object hook scan
*Fixed several bugs.

2010-11-30 Special version for www.52pojie.cn:
*Added worker thread enumeration feature
*Fixed several bugs.

2010-10-01 V0.37:
*Added mouse driver irp hook scan
*Added user32.ll:_apfnDispatch hook scan
*Added LSP/Safeboot repair feature
*Added list and remove feature for hidden reg
*Fixed several bugs.

2010-07-16 V0.36:
*Added GDT detection feature
*Added Object Hijack detection feature for detecting the TDL3 malware
*Fixed one potential BSOD

2010-07-07 V0.35:
*Fixed one potential BSOD
*Fixed several bugs.

2010-05-16 V0.34:
*Added MBR Rootkit detection feature
*Added Input Method Editor(IME) enumeration feature
*Added classpnp\atapi\acpi irp hook scan
*Fixed two potential BSODs
*Fixed several bugs.

2010-04-01 V0.33:
*Added Hot key enumeration feature
*Added Process's timer enumeration feature
*Added Windows Firewall rules display
*Fixed several bugs.

2009-12-20 V0.32:
*Fixed a potential BSOD
*Fixed a bug in deleting folders on FAT partitons 

2009-12-13 V0.31:
*Several bugs fixed
*Added common filetype assosiations
*Added a configuration file

2009-11-22 V0.30:
*Fixed two potential BSODs
*XueTr now can highlight suspicious images
*Various internal improvements to explorer 
		
2009-10-08 V0.29:
*XueTr now fully supports Windows 7 Build 7600 x86
*Added option to prevent switching destop
*Added option to prevent locking workstation
*Added kernel bugcheck callback list and remove feature
*Improved kernel hook scan

2009-07-07 V0.28:
*Added:XueTr now displays IE context menu 
*Added option to prevent system time modification
*Added list and remove feature for CmpCallback 
*Fixed a bug in registry hive parse
*Fixed one autorun entry enumeration bug

2009-05-28 V0.27:
*Full support Windows Vista SP2 and Windows Server 2008 SP1 x86
*Fixed a bug handling null-embeded registry keys
*Fixed a bug in display of function index for Ring3 hook scan
*Added file force delete support for exFAT file system
*Several internal improvements
		
2009-04-27 V0.26:
*Fixed out of memory issue on unusual scenario
		
2009-04-25 V0.25:
*Fixed a rare driver load failure issue
*Added Force Shutdown feature
*Added support for Safe Mode
		
2009-04-10 V0.24:
*Added DPC Timer enumeration feature
*Added Unload Modules Globally feature
*Added Kernel Module Load Order display
*Added delay delete file feature
*Added file attributes display
*Improved ability to track double jumps in kernel code hook scan
*Improved unknown image identification for kernel hooks
*Fixed a bug in retrieving Shadow SSDT address
*Fixed a bug in FAT32 file system analysis
*Improved right menu,more feature to explorer
		
2009-03-22 V0.23:
*Improved message hook scan:XueTr now displays thread id and image name 
*Improved prevent registry creation feature,added defense from RegRestoreKey method
*Improved file search
*Fixed a diver bug

2009-03-15 V0.22:
*Added Traditional Chinese language support
*Added Find Files feature
*Fixed a bug in parsing file properties
*Fixed a ObjectType hook display issue 
*Fixed a bug XueTr failed to delete service config registry in some cases

2009-03-01 V0.21:
*Fixed a bug in SPI display
*Reduced some false positives in kernel module scan
*Fixed a file verification issue
*XueTr now supports maximuming its child windows
*XueTr now supports displaying process modules in sub window 
*Fixed a bug XueTr may hang when deleting some driver's notifications
*Added prevent Registry Creation feature
*Added Lock File After Deletion feature
*Added Who Locked Me Viewer feature in file list

2009-02-16 V0.20:
*Added support for Windows 7 Beta(test)
*Added PE digital signature verification
*Added Find Unsigned Modules feature
*Improved thread information viewer,XueTr now displays modules for thread entries
*Added defense from some kind of dll injection
*Added defense from fake process id
*XueTr now reports code inject on startup
*Added driver service name display in kernel module list
*Several bugs fixed
		
2009-02-05 V0.19:
*XueTr's disk analysis now supports exFAT file system
*Added termintate process & delete file feature in process list
*Added File Corporation display
		
2009-02-02 V0.18:
*Added more autorun entries display
*Added Find Module feature in process list
*Reduced some false positives in kernel module scan
*Fixed a driver deadlock issue

2009-01-30 V0.17:
*Added remove message hook feature
*Added Process Window Viewer and Manipulator
*Added prevent system log off,shutdown & restart feature

2009-01-26 V0.16:
*XueTr now can auto select its internal language 
*Added prevent process,thread,file creation,image load and message hook installation feature
*Added registry hive live analysis feature
*Added self defense
*Improved kernel hook scan
*Fixed some GUI bugs 
	
2009-01-17 V0.15:
*Added Suspend and Resume Process feature 
*Added disk analysis for NTFS,FAT32,FAT16 partitions(on by default)
		
2009-01-06 V0.14:
*Added ObjectType hook scan
*Fixed an issue XueTr failed to enum files in removable devices
*Fixed a GUI bug

2009-01-02 V0.13:
*Improved GUI display
*Added IE Plugin,SPI,Common Autorun Entries,Image Hijack and Hosts File Viewer 
*Fixed a bug displaying filters

2008-12-22 V0.12:
*Fixed an incompatibility issue with Micropoint

2008-12-11 V0.11:
*Fixed some bugs XueTr failed to initialize in some cases
																																												linxer
																																												2008-12-10 ShenZhen.China.