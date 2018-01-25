# opensource-re-tools

A collection of open source reverse engineering tools


## IDA Plugins

* [onethawt/idaplugins-list: a list of IDA plugins](https://github.com/onethawt/idaplugins-list/blob/master/README.md)

IOCTL / Windows driver

* [mwrlabs/win_driver_plugin - A tool to help when dealing with Windows IOCTL codes or reversing Windows drivers.](https://github.com/mwrlabs/win_driver_plugin)
* [nccgroup/DriverBuddy - DriverBuddy is an IDA Python script to assist with the reverse engineering of Windows kernel drivers.](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/november/driverbuddy-tool-release/)

Diff / Patch

* [keypatch0 - A replacement of the internal IDA assembler](http://www.keystone-engine.org/keypatch0)
* [McGill-DMaS/Kam1n0-Plugin-IDA-Pro - The Kam1n0 Assembly Clone Search Engine](https://www.whitehatters.academy/diffing-with-kam1n0/)
* [ohjeongwook/DarunGrim - A Binary Diffing and Patch Analysis Tool (v3) http://darungrim.org](https://github.com/ohjeongwook/DarunGrim)

FLIRT / Signatures

* [Maktm/FLIRTDB - A community driven collection of IDA FLIRT signature files](https://github.com/Maktm/FLIRTDB)
* [polymorf/findcrypt-yara - IDA pro plugin to find crypto constants (and more)](https://github.com/polymorf/findcrypt-yara)

UEFI 

* [kyurchenko/IDAPython-scripts-for-UEFI-analisys: Analysis of the disassembled UEFI image](https://github.com/kyurchenko/IDAPython-scripts-for-UEFI-analisys)
* [gdbinit/EFISwissKnife - An IDA plugin to improve (U)EFI reversing](https://reverse.put.as/2017/06/13/efi-swiss-knife-an-ida-plugin-to-improve-uefi-reversing/)

Auxiliary

* [ampotos/dynStruct - Reverse engineering tool for automatic structure recovering and memory use analysis based on DynamoRIO and Capstone](https://github.com/ampotos/dynStruct)
* [IDA StringCluster - extending IDA's string navigation capabilities](https://github.com/Comsecuris/ida_strcluster)
* [ida_ea - A set of exploitation/reversing aids for IDA: Context Viewer, Instuction Emulator, Heap Explorer, Trace Dumper, CMD and Restyle](https://github.com/1111joe1111/ida_ea)
* [ida-arm-system-highlight - Decoding ARM system instructions](https://github.com/gdelugre/ida-arm-system-highlight)
* [alexhude/FRIEND - Flexible Register/Instruction Extender aNd Documentation](https://github.com/alexhude/FRIEND)
* [REhints/HexRaysCodeXplorer - Hex-Rays Decompiler plugin for better code navigation](https://github.com/REhints/HexRaysCodeXplorer)
* [comsecuris/gdbida: a visual bridge between a GDB session and IDA Pro's disassembler](https://github.com/comsecuris/gdbida)
* [darx0r/Reef - IDAPython plugin for finding Xrefs from a function](https://github.com/darx0r/Reef)
* [ALSchwalm/dwarfexport - Export dwarf debug information from IDA Pro](https://github.com/ALSchwalm/dwarfexport)
* [maddiestone/IDAPythonEmbeddedToolkit - IDAPython scripts for automating analysis of firmware of embedded devices](https://github.com/maddiestone/IDAPythonEmbeddedToolkit)
* [nccgroup/PythonClassInformer - an IDAPython plugin for viewing run-time type information](https://github.com/nccgroup/PythonClassInformer)
* [tkmru/nao- Simple No-meaning Assembly Omitter for IDA pro (CURRENTLY UNDER DEVELOPMENT)](https://github.com/tkmru/nao)

Unpacking

* [DavidKorczynski/RePEconstruct - a tool for automatically unpacking binaries and rebuild the binaries in a manner well-suited for further analysis, specially focused on further manual analysis in IDA pro.](https://github.com/DavidKorczynski/RePEconstruct)
* [iwseclabs/gunpack](https://bitbucket.org/iwseclabs/gunpack)

## LLDB plugins

* [gdbinit/lldbinit - A gdbinit clone for LLDB](https://github.com/gdbinit/lldbinit/)

## Windbg plugins

* [szimeus/evalyzer - Using WinDBG to tap into JavaScript and help with deobfuscation and browser exploit detection](https://github.com/szimeus/evalyzer)
* [comaeio/SwishDbgExt - Incident Response & Digital Forensics Debugging Extension](https://github.com/comaeio/SwishDbgExt)
* [zodiacon/GflagsX - Enhanced version of the GFlags tool](https://github.com/zodiacon/GflagsX)

## GDB plugins

* [libptmalloc gdb plugin](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2017/october/cisco-asa-blog-series-part-five-libptmalloc-gdb-plugin/)
* [voltron - A hacky debugger UI for hackers](https://github.com/snare/voltron)
* [pwndbg - Exploit Development and Reverse Engineering with GDB Made Easy](https://github.com/pwndbg/pwndbg)
* [peda - Python Exploit Development Assistance for GDB](https://github.com/longld/peda)
* [hugsy/gef - https://github.com/hugsy/gef](https://github.com/hugsy/gef)

## Standalone tools

Uncategorized

* [m4b/bingrep - like ~~grep~~ UBER, but for binaries](https://github.com/m4b/bingrep)
* [fireeye/flare-vm - a fully customizable, Windows-based security distribution for malware analysis, incident response, penetration testing](https://github.com/fireeye/flare-vm)

DotNet

* [enkomio/shed - .NET runtine inspector](https://github.com/enkomio/shed)

QT

* [KDAB/GammaRay - a tool to poke around in a Qt-application and also to manipulate the application to some extent](https://github.com/KDAB/GammaRay)

Mac

* [wzqcongcong/macSubstrate - Substrate for macOS](https://github.com/wzqcongcong/macSubstrate)

iOS

* [kernelcache - Identify and rename function stubs (plt entries) in an iOS kernelcache. ARM64 only.](https://github.com/saelo/ida_scripts/blob/master/kernelcache.py)

Emulators

* [pyrebox - Python scriptable Reverse Engineering Sandbox, a Virtual Machine instrumentation and inspection framework based on QEMU](https://github.com/Cisco-Talos/pyrebox)

Graph / Visualization

* [fireeye/SimplifyGraph - IDA Pro plugin to assist with complex graphs
](https://github.com/fireeye/SimplifyGraph)
* [patois/IDACyber - visualizing the currently loaded IDB's data](https://github.com/patois/IDACyber)

LLVM

* [trailofbits/mcsema - Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode](https://github.com/trailofbits/mcsema)

Auxiliary

* [fireeye/remote_lookup - scan a 32bit process and build an
export name/address map which can be queried](https://github.com/fireeye/remote_lookup)
* [trailofbits/mcsema - Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode](https://github.com/trailofbits/mcsema)

## Scripts

* [vallejocc/Reverse-Engineering-Arsenal - Useful Scripts for helping in reverse engeenering](https://github.com/vallejocc/Reverse-Engineering-Arsenal)

## Wiki

* [michalmalik/osx-re-101 - A collection of resources for OSX/iOS reverse engineering](https://github.com/michalmalik/osx-re-101)
* [recodeking/MalwareAnalysis - A curated list of awesome malware analysis tools and resources](https://github.com/recodeking/MalwareAnalysis)
* [wtsxDev/Malware-Analysis - List of awesome malware analysis tools and resources](https://github.com/wtsxDev/Malware-Analysis)

* [yellowbyte/reverse-engineering-reference-manual - a collage of reverse engineering topics that I find interesting](https://github.com/yellowbyte/reverse-engineering-reference-manual)
