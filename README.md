EFI for install MacOS on Lenovo ThinkStation P720 with dual Xeon CPUs.

* EFI prepared for Wireless Patch on Sonoma/Sequoia/Tahoe using RP-Core. You can try any OCLP mod fork, but the simple way is use RP-Core tool.

* Needs to add Serial and SMBIOS infos.

For this machine is needed to use an SSDT-CPU-DEVICE-WRAPPER to rename Devices (from DSDT table) to Processor, to MacOS identify processors correctly.

Credits to Metacollin for CPU-WRAPPER.
https://gist.github.com/metacollin/dc0a401154c0ddbaac00336632599a6b
