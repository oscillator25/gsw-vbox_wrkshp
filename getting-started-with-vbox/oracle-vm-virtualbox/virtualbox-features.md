---
description: 'Let''s dive deep into a few VirtualBox features:'
---

# Features of VirtualBox

* **Free**: VirtualBox is free and open source.
* **Portability**: VirtualBox can run on both a 32-bit and 64-bit OS based on the Intel x86-64-based processors. VirtualBox is a Type 2 hypervisor. It is functionally identical on all of the host platforms. Also, the same file and image formats can be used across different host operating systems, which means a VM created on one host can easily run on another and, by using Open Virtualization Format \(OVF\), the guest VMs can be imported and exported when required.
* **No hardware virtualization required**: VirtualBox does not requirea hardware virtualization feature. So VirtualBox can even run on older hardware where features such as Intel VT-X or AMD-V are not present.
* **VM groups**: This feature enables the user to organize virtual machines individually as well as collectively. Operations such as start, close, pause, reset, save state, shutdown, power off, and so on can be applied to VM groups like individual VMs.
* **Guest additions**: These are the add-on software packages that are installed on the guest VMs that are certified to run on VirtualBox and help improve the performance and provide additional integration and communication with the host system. There is also a very compelling feature known as a _shared folder_ that helps in accessing files from the host OS system within a guest VM.
* **Multigeneration branched snapshots**: VirtualBox supports the save snapshots feature of guest VM state information. So ideally, you can go back and revert the virtual machine to any snapshot and start an alternative VM configuration from there, depending on your requirement. It also allows creating and deleting snapshots while the VM is active and running.
* **Remote machine display**: The VirtualBox Remote Desktop Extension \(VRDE\) is a feature that helps to access any guest VM that is running remotely. It supports RDP built into Microsoft Windows, but doesn't rely on the inbuilt RDP server for Microsoft Windows; rather it is plugged directly into the virtualization layer.
* **Great hardware support**: VirtualBox supports guest SMP, USB devices, full ACPI support, multiscreen resolution, built-in iSCSI support, and PXE network boot.

