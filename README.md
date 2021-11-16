This repository is a list of some of the public projects I've worked on.

# Bugs / Exploits
* [Netgear RCE in UPnP Daemon](https://github.com/grimm-co/NotQuite0DayFriday/tree/trunk/2021.11.16-netgear-upnp)
* [Netgear MITM RCE Exploit](https://github.com/grimm-co/NotQuite0DayFriday/tree/trunk/2021.09.21-netgear-circle)
* [Denial of Service in macOS's necp_client_action syscall (again)](https://github.com/grimm-co/NotQuite0DayFriday/tree/trunk/2021.03.18-ios-macos)
* [RHEL Kernel Exploit](https://github.com/grimm-co/NotQuite0DayFriday/tree/trunk/2021.03.12-linux-iscsi) ([Nominated for a Pwnie Award](https://pwnies.com/new-old-bugs-in-linux-kernel/))
* [RCE and DoS in the NITRO NITF parsing library](https://github.com/grimm-co/NotQuite0DayFriday/tree/trunk/2021.01.29-nitro)
* [Information Leak in FreeBSD and OpenBSD kernels](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2020.07.10-bsd)
* [Unauthenticated RCE Exploit for 79 Netgear Devices](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2020.06.15-netgear) ([Nominated for a Pwnie Award](https://pwnies.com/netgear-router-roundup/))
* [Denial of Service in iOS Safari](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2020.06.02-iOS-safari)
* [LPE Exploit for VMware Fusion](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2020.03.17-vmware-fusion) and [Bypass for the Fix](https://twitter.com/jeffball55/status/1242530508053110785)
* [Denial of Service in Excel](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2020.03.07-excel)
* [NULL Pointer and Infinite Recursion bugs in pdftk](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2018.07.05-pdftk)
* [Denial of Service in macOS's necp_client_action syscall](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2018.05.24-macos)
* [Heap Corruption and Integer Overflow bugs in ccd2cue](https://github.com/grimm-co/NotQuite0DayFriday/blob/master/2018.04.26-ccd2cue)
* [Heap overflow in macOS's necp_client_action syscall](https://github.com/grimm-co/NotQuite0DayFriday/tree/master/2018.04.06-macos)
* [Two Denial of Service Bugs in macOS's workq_kernreturn syscall](https://github.com/grimm-co/NotQuite0DayFriday/blob/master/2018.02.16-macos)

# Blogs / Writeups
* [Seamlessly Discovering Netgear Universal Plug-and-Pwn (UPnP) 0-days](https://blog.grimm-co.com/2021/11/seamlessly-discovering-netgear.html)
* [Mama Always Told Me Not to Trust Strangers without Certificates](https://blog.grimm-co.com/2021/09/mama-always-told-me-not-to-trust.html)
* [New Old Bugs in the Linux Kernel](https://blog.grimm-co.com/2021/03/new-old-bugs-in-linux-kernel.html) 
* [DJI Privacy Analysis Validation](https://blog.grimm-co.com/2020/07/dji-privacy-analysis-validation.html) ([code](https://github.com/grimm-co/dji-go-4))
* [SOHO Device Exploitation - Netgear Case Study](https://blog.grimm-co.com/2020/06/soho-device-exploitation.html)
* [Analyzing SUID Binaries - VMware Fusion Case Study](https://blog.grimm-co.com/2020/05/analyzing-suid-binaries.html)
* [Analyzing the Linux Kernel in Userland with AFL and KLEE](https://blog.grimm-co.com/2020/05/analyzing-linux-kernel-in-userland-with.html)
* [Crash Triage Process](https://blog.grimm-co.com/2020/05/crash-triage-process.html)
* [Delta Debugging](https://blog.grimm-co.com/2020/05/delta-debugging.html)
* [Heap overflow in the necp_client_action syscall](https://blog.grimm-co.com/2020/05/heap-overflow-in-necpclientaction.html)
* [DEF CON 2017 Quals CTF - Reeses Revenge Writeup](https://github.com/jeffball55/ctf_writeups/tree/master/defcon_quals_2017/reeses)
* [Boston Key Party 2017 - barewithme Writeup](https://github.com/jeffball55/ctf_writeups/tree/master/boston_key_party_2017/barewithme)
* [PETS 2016 - SoK: Privacy on Mobile Devices – It’s Complicated](https://petsymposium.org/2016/files/papers/SoK__Privacy_on_Mobile_Devices_%E2%80%93_It%E2%80%99s_Complicated.pdf)
* [POC||GTFO 0x8 - On Error Resume Next](https://github.com/jeffball55/on_error_resume_next)
* Contributing Author to [Google Hacking for Penetration Testers, Volume 2](https://www.amazon.com/Google-Hacking-Penetration-Testers-Johnny/dp/1597491764)

# Talks
* [GRIMMCon0x2 - Embedded Device ROP Tips and Tricks - Netgear](https://www.youtube.com/watch?v=33vjLZrTc-U) ([presentation materials](https://github.com/jeffball55/grimmcon2_netgear_rop))
* [GRIMMCon - Analyzing SUID Binaries - VMWare Fusion](https://www.youtube.com/watch?v=L4tB8Ck1ed0)
* [BSidesCHS - An Introduction to macOS Kernel Exploitation](https://www.youtube.com/watch?v=OYZyk2q5XJY) ([presentation materials](https://github.com/jeffball55/intro_to_xnu_exploitation))
* MTEM: Pyrop: An Open-Source, Multi-Architecture ROP Compiler
* DEF CON Skytalks - Stiltwalker Round 2 - Breaking reCAPTCHA (again)
* [BSidesLV - Stiltwalker Round 2 - Breaking reCAPTCHA (again)](https://www.youtube.com/watch?v=3ZyTUsd-gAE)
* [LayerOne - Stiltwalker - Breaking reCAPTCHA](https://www.youtube.com/watch?v=Mj3thHKeKyg)
* Outerzone - Stiltwalker Preview
* [BSidesCHS - Practical Issues in Virtual Machine Covert Channels](http://www.securitybsides.com/w/page/50788290/BSidesCharleston)
* [DEF CON: oCTF: 5 years in 50 minutes](https://www.youtube.com/watch?v=lhHdu1RJ-0U)

# Projects
* [Pyrop ROP Compiler](https://github.com/jeffball55/rop_compiler/tree/master/pyrop)
* [Binary Ninja Processor Plugin for cLEMENCy](https://github.com/jeffball55/ctf_writeups/tree/master/defcon_finals_2017/binja)
* [Stiltwalker](https://dc949.org/projects/stiltwalker/)
* [Linux Kernel ASN.1 Parser and inet_diag Bytecode Interpreter Fuzzers](https://github.com/grimm-co/linuxklee)
* [SetRegTime - Registry Timestamp Modifier](https://github.com/grimm-co/SetRegTime)
* [String Converter for Bad Byte Avoidance](https://github.com/jeffball55/string_converter)
* [Overwrite MBR tools for PCDC Red Teaming](https://github.com/jeffball55/overwrite_mbr)
