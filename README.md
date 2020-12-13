<!-- Badges -->
![GitHub contributors](https://img.shields.io/github/contributors/NotPrab/.NET-Obfuscator?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/NotPrab/.NET-Obfuscator?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/NotPrab/.NET-Obfuscator?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/NotPrab/.NET-Obfuscator?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/NotPrab/.NET-Obfuscator?style=for-the-badge)


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/NotPrab/.NET-Obfuscator">
    <img src="https://www.kitto.app/image/logo-microsoft-net.png" alt="Logo" width="238" height="238">
  </a>

  <h3 align="center">.NET Obfuscator</h3>

  <p align="center">
    💻 🎉  Awesome lists about all kinds of interesting .NET Obfuscator.
    <br />
    <a href="https://github.com/NotPrab/.NET-Obfuscator/discussions">Discussions</a>
    ·
    <a href="https://github.com/NotPrab/.NET-Obfuscator/issues">Report Bug</a>
    ·
    <a href="https://github.com/NotPrab/.NET-Obfuscator/pulls">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

There are many great .NET obfuscators available on internet, however, I didn't find one that really suit my needs so I create this list. I want to gather all over .NET Obfuscator so that it'll be the last one you ever need.


<!-- utilization EXAMPLES -->
## Utilization

Certain languages like Java and .NET can be easily decompiled into readable source code. Code obfuscation is a process that makes your application binaries harder to read with a decompiler. It’s an important tool for protecting your business’s intellectual property.
### Why Obfuscate Code?

Compiled languages like C++ get converted directly to bytecode. The only way to reverse engineer how they work is with a disassembler, which is an arduous and complicated process. It’s not impossible, but trying to infer high level application logic from a stream of assembly language is hard.

On the other hand, languages like C# and Java aren’t compiled for any particular operating system. Rather, they’re compiled to an intermediary language, like .NET’s MSIL. The intermediary language is similar to assembly, but it can be easily converted back into the source code. This means that if you have a public DLL or executable that your business is distributing, anyone with a copy of your executable can open it up in a .NET decompiler like dotPeek, and directly read (and copy) your source code.

Code obfuscation can’t prevent this process—any .NET DLL can be plugged into a decompiler. What obfuscation does do is use a number of tricks to make the source code annoying as hell to read and debug.

The simplest form of this is entity renaming. It’s common practice to properly name variables, methods, classes, and parameters according to what they do. But you don’t have to, and technically there’s nothing stopping you from naming them with a series of lowercase L’s and I’s, or random combinations of Chinese unicode characters. To the computer, there’s no issue, but it’s completely illegible to a human:

```
IlIIIIlIIIllIIIllIIll
lIIIllIIllIlIIIIlIIIl
```

An basic obfuscator will handle this process automatically, taking the output from the build, and converting it to something that’s a lot harder to read. There’s **no performance hit** compared to non-obfuscated code

More advanced obfuscators can go further, and actually change the structure of your source code. This includes replacing control structures with more complicated but semantically identical syntax. They can also insert dummy code that doesn’t do anything except confuse the decompiler. The effect of this is that it makes your source look like spaghetti code, making it more annoying to read.

Another common focus is hiding strings from decompilers. In managed executables, you can search for strings like error messages to locate sections of code. String obfuscation replaces strings with encoded messages, which are decrypted at runtime, making it impossible to search for them from a decompiler. This usually comes with a performance penalty.

### Other Options: Convert to a Compiled Language

Converting one programming language to another isn’t an entirely crazy idea—Unity uses IL2CPP, a converter that transforms .NET code into compiled C++ bytecode. It’s a lot more performant, but it also helps secure games against easy cracking, which is crucial for an environment plagued by piracy and cheaters.

Microsoft has [CoreRT](https://github.com/dotnet/corert), an experimental .NET Core runtime using Ahead-Of-Time compilation, though it isn’t ready for production use.

### Should You Obfuscate?

If you’re deploying code in untrusted environments where you want to protect your source code, you should almost always use at least a basic obfuscator to rename functions, methods, and properties to make decompiling take a bit more effort.

If you really need nobody to be able to decompile your app, you can use a more intrusive obfuscator, but really you should consider if the problem would be better solved by switching to a language that doesn’t have this issue, such as C++ or Rust.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/NotPrab/.NET-Obfuscator/issues) for a list of proposed features (and known issues).


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

## References
[What is Code Obfuscation, and Should you use it?](https://www.cloudsavvyit.com/6923/what-is-code-obfuscation-and-should-you-use-it/) by Anthony Heddings


<!-- Lists -->
## Lists of .NET Obfuscator

<!-- A -->
## A =>
### Agile
* [Agile](https://secureteam.net/acode-features-detailed)- Agile.NET, Powerful Code Protection, Obfuscation, and Licensing Solution for your .NET Apps

### Aldaray Rummage Obfuscator
* [Aldaray Rummage Obfuscator](https://www.aldaray.com/) - Tie your code into knots and make the hackers cry
### AppFuscator
* [AppFuscator](https://appfuscator.com/) - Inteligence algorithm provide your application powerful protection! 
### ArmDot
* [ArmDot](https://www.armdot.com/) - Protection, software licensing tool, and obfuscator for C# and .Net with support of serial keys and files embedding
### Arya
* [Arya](https://github.com/HarmJ0y/Arya) - Arya is a simple obfuscator for .NET binaries.
### AsStrongAsFuck
* [AsStrongAsFuck](https://github.com/Charterino/AsStrongAsFuck) - A console obfuscator for .NET assemblies.

------------------
<!-- B -->
## B =>
### Babel
* [Babel](https://www.babelfor.net/) - Protect your software against reverse engineering to safeguard the intellectual property of your code
### Beds Protector

* [Beds Protector](https://github.com/BedTheGod/ConfuserEx-Mod-By-Bed) - Beds Protector | Best free obfuscation out right now ( ConfuserEx Mod )
### BitHelmet

* [BitHelmet](https://bithelmet.software.informer.com/) - BitHelmet obfuscator protects your .NET Portable Executables 
### BoxedApp

* [BoxedApp](https://www.boxedapp.com/) - Import and virtualize ActiveX, Flash and .Net runtime • Rich SDK for developers • Create custom packers • Supports both 32-bit and 64-bit applications • Virtual file system and registry
------------------
<!-- C -->
## C =>
### ConfuserEx

* [ConfuserEx](https://github.com/yck1509/ConfuserEx) - An open-source, free protector for .NET applications.
### ConfuserEx 2

* [ConfuserEx 2](https://github.com/mkaring/ConfuserEx) - Updated ConfuserEx (by mkaring), an open-source, free obfuscator for .NET applications.
### Crypto

* [Crypto](https://www.ssware.com/cryptoobfuscator/obfuscator-net.htm) - Powerful Obfuscation & Code Protection For .Net That Actually Works!
### Cyphor

* [Cyphor](https://cyphor.net/details) - Cyphor is more than just an obfuscator. Cyphor is the best, fastest, and most reliable obfuscation protection tool to work with.
### cil-examining

* [cil-examining](https://github.com/mira-ta/cil-examining) - A .NET Framework (.NET Core in the future) obfuscator. Owner is currently out sick thus working on project is stopped.
### Cheap Obfuscator

* [Cheap Obfuscator](https://github.com/Polymeth/cheap-obfuscator) - a pretty bad obfuscator made to learn
### Confuser1337

* [Confuser1337](https://github.com/ama6nen/Confuser1337) - bad 2016 code, i dont recommend anyone uses it
------------------
<!-- D -->
## D =>
### dotNetObfuscator

* [dotNetObfuscator](https://github.com/baskfx/dotNetObfuscator) - Обфускатор строки для C#
### DarkFuscator

* [DarkFuscator](https://github.com/isigov/.NET-Obfuscator) - Code obfuscator for .NET framework programs. Outdated in 2016, but was very functional in 2010/2011.Uses the Mono.Cecil library for interacting with .NET assemblies. 
### DarksProtector

* [DarksProtector](https://github.com/BillytheButcher/DarksProtector) - DarksProtector 2.0 | ConfuserEx Modded 
### DeepSea

* [DeepSea](https://deepsea-obfuscator.soft112.com/) - DeepSea Obfuscator makes obfuscation of your .NET assemblies an intuitive and integrated part of your product development.
### Demeanor

* [Demeanor](http://www.wiseowl.com/products/products.aspx) - Demeanor for.NET protects your intellectual property by making it extremely difficult to reverse engineer your .NET applications.
### Denvelope

* [Denvelope](https://github.com/TWVyY3VyaW8K/Denvelope) - NET Obfuscator
### DNGuard HVM

* [DNGuard HVM](http://www.dnguard.net/index.php) - Advanced .NET Code Protection and Obfuscation Technology
### Dotfuscator

* [Dotfuscator](https://www.preemptive.com/products/dotfuscator/overview) - Dotfucator's .NET obfuscation and runtime checks have protected thousands of apps for over a decade.
### DotNetGuard

* [DotNetGuard](https://github.com/Modify24x7/DotNetGuard) - .Net Protector ( ConfuserEx Mod )
### DotNetPatcher

* [DotNetPatcher](https://github.com/mwsrc/DotNetObfuscator) - DotNetObfuscator
### DotNetSafer

* [DotNetSafer](https://dotnetsafer.com/) - Increase the security of your software, reduce costs and save time with the tools that dotnetsafer offers you to protect your intellectual property and guarantee the integrity of your .NET and .NET Core applications.
### Dotpack

* [Dotpack](https://github.com/daeken/Dotpack/) - Extreme (TM) binary packer for .NET 
------------------
<!-- E -->
## E =>

### Eazfuscator

* [Eazfuscator](https://www.gapotchenko.com/eazfuscator.net) - Eazfuscator.NET is the obfuscator for .NET platform. 
### Enigma Protector

* [Enigma Protector](https://enigmaprotector.com/en/about.html) - A professional system for licensing and protecting
executable files for Windows.
### ElecKey

* [ElecKey](https://www.sciensoft.com/) - ElecKey is a suite of software and tools that provide a complete solution for software security, copy protection, and license management. It allows you to protect your software against piracy, tampering, and reverse-engineering, as well as gain full control over secure software distribution and licenses.
------------------
<!-- G -->
## G =>

### Guardship-.NET-Protector

* [Guardship-.NET-Protector](https://github.com/Rustemsoft/Guardship-.NET-Protector) - Guardship .NET Protector is a development software that helps to protect the executable file of .NET application by making its code unreadable for MSIL disassemblers.
### Goldfuscator

* [Goldfuscator](https://github.com/AnErrupTion/Goldfuscator) - A fork of the original SimpleObfuscator project, made for training. 
------------------
<!-- H -->
## H =>

### Habib Extreme Protector

* [Habib Extreme Protector](https://discord.gg/rQ4P6ZV) - A Strong .NET Obfuscator & Protector
------------------
<!-- I -->
## I =>
### ILProtector

* [ILProtector](http://www.vgrsoft.net/Products/ILProtector) - ILProtector is a protector for .NET applications. ILProtector is designed to protect intellectual property of the software.

### IntelliLock

* [IntelliLock](https://www.eziriz.com/intellilock.htm) - IntelliLock is an advanced 100% managed solution for licensing controls and applications. While .NET Reactor offers a licensing system based on native code protection, IntelliLock opts a 100% managed way to apply licensing and protection features. This way single files can be produced without the need of additional files. 
### IntelliProtector

* [IntelliProtector](https://intelliprotector.com/Products/Net-Obfuscator/Features) - IntelliProtector .Net Obfuscator is excellent Free tool for your IntelliProtector .Net projects.

------------------
<!-- K -->
## K =>

### Krawk Protector

* [Krawk Protector](https://github.com/cristlxrd/Krawk-Protector) - .NET Obfuscator and Protector 
### KoiVM

* [KoiVM](https://github.com/Loksie/KoiVM-Virtualization) - Virtualization made for .NET using ConfuserEX 
------------------
<!-- L -->
## L =>

### lookatme

* [lookatme](https://github.com/pjc0247/lookatme) - NET Obfuscator for Studying purpose.
### Lime-Crypter

* [Lime-Crypter](https://github.com/NYAN-x-CAT/Lime-Crypter) - An obfuscation tool for .Net + Native files.
### LoGic.NET

* [LoGic.NET](https://github.com/AnErrupTion/LoGiC.NET) - A more advanced free and open .NET obfuscator using dnlib.
------------------
<!-- M -->
## M =>

### MancoSoftware

* [MancoSoftware](http://www.mancosoftware.com/) - Manco .NET Licensing System is the powerful licensing and copy protection software for .NET Windows Forms, WPF, WCF, WWF and ASP.NET applications, controls and components.
### MdCrypt

* [MdCrypt](https://github.com/wwh1004/Mdcrypt) - [WIP] A next-generation protector for .NET applications (.NET Framework, .NET Core, and more) 
### MemeVM

* [MemeVM](https://github.com/TobitoFatitoNulled/MemeVM) - A small virtualizer for .NET which works together with ConfuserEx 

### MindLated

* [MindLated](https://github.com/Sato-Isolated/MindLated) -  .net obfuscator using dnlib  
### ModPhuserEx

* [ModPhuserEx](https://github.com/0xFireball/ModPhuserEx) - A .NET protector supporting .NET Core forked from the discontinued ConfuserEx
### MPRESS

* [MPRESS](http://www.matcode.com/) - Free high-performance executable packer for PE32/PE32+/.NET executable formats!
------------------
<!-- N -->
## N =>

### netshrink

* [netshrink](https://www.pelock.com/products/netshrink) - netshrink is an exe packer aka executable compressor, application password protector and virtual DLL binder for Windows & Linux .NET applications.
### Neo ConfuserEx

* [Neo ConfuserEx](https://github.com/XenocodeRCE/neo-ConfuserEx) - Updated ConfuserEX, an open-source, free obfuscator for .NET applications
### NetFuscate

* [NetFuscate](http://netfuscate.com/) - NETFuscate is a .NET obfuscator and a .NET code protection tool that offers protection against reverse engineering of your code.
### NetShields

* [NetShields](https://discord.gg/baVPenN) - A really strong & recommended for .NET Obfuscator
### NETGuard

* [NETGuard](https://netguard.io/) - NETGuard.IO will decompose your file, encrypt your strings, data, resources, methods, will perform numerous runtime-based verifications to ensure a fully-shielded security for 
your file. The list of feature can be founded on our official documentation page. 
### NET Reactor

* [NET Reactor](https://www.eziriz.com/) - NET Reactor is a powerful .NET code protection and software licensing system which completely stops any decompiling.
### NETZ Compressor

* [NETZ Compressor](https://github.com/madebits/msnet-netz-compressor) - 2004 .NETZ compresses Microsoft .NET executables 
### NET-Obfuscator

* [NET-Obfuscator](https://github.com/NightBaron/.NET-Obfuscator) - Simple .net obfuscator using Mono Cecil
### Noisette

* [Noisette](https://github.com/XenocodeRCE/Noisette-Obfuscator) - An Obfuscator for .NET assembly 

------------------
<!-- O -->
## O =>

### obfuscatus

* [obfuscatus](https://github.com/stschake/obfuscatus) - a .NET obfuscator based on mono cecil
### ObfuscationAttributes

* [ObfuscationAttributes](https://github.com/obfuscators-2019/ObfuscationAttributes) - Add watermarks of obfuscators, makes de4dot think your file is obfuscated. bad 2016 code, i dont recommend anyone uses it
### Obfuscord

* [Obfuscord](https://github.com/TobitoFatitoNulled/Obfuscord) - Obfuscates A file Through Discord as a Bot using Discord.Net Api
### Obfuscar

* [Obfuscar](https://github.com/obfuscar/obfuscar) - Open source obfuscation tool for .NET assemblies
### Obfuscator.NET 2009

* [Obfuscator.NET 2009](http://www.macrobject.com/en/obfuscator/index.htm) - Protect your .NET assembly
### OctopusObfuscator

* [OctopusObfuscator](https://github.com/Alxs009/OctopusObfuscator) - Basic obfuscator for .NET
### Orange Heap obfuscator

* [Orange Heap obfuscator](http://orangeheap.blogspot.com/) - free and efficient way to protect your .NET software
------------------
<!-- P -->
## P =>

### pshield

* [pshield](https://github.com/developervariety/pshield) - Plugin-based obfuscator
### Panda-Obfuscator

* [Panda-Obfuscator](https://github.com/barotyson/Panda-Obfuscator) - PandaObfuscator an simple Obfuscator, free, OpenSource for .Net Applications 
### PAOfuscator

* [PAOfuscator](https://github.com/Schaboom/PAOfuscator) - Obfuscator für Paradise.de
### PC Guard

* [PC Guard](http://www.sofpro.com/pc-guard) - Professional software protection and licensing system for .NET framework (x86, AnyCpu, x64) and Windows 32bit and 64 bit applications.
### PEunion

* [PEunion](https://github.com/bytecode77/pe-union) - PEunion (Binder, Crypter & Downloader)
### Phoenix Protector

* [Phoenix Protector](https://ntcore.com/?page_id=384) - .NET Obfuscator & Protector
### PV Logiciels dotNet Protector

* [PV Logiciels dotNet Protector](http://www.pvlog.com/) - PV Logiciels dotNet Protector is a powerful .NET code protection system that prevents your assemblies from being decompiled.
------------------
<!-- R -->
## R =>

### Rzy Protector

* [Rzy Protector](https://github.com/Riziebtw/RzyProtector) - Rzy Protector | A public confuserex modded
------------------
<!-- S -->
## S =>

### Semantic Designs

* [Semantic Designs](http://www.semdesigns.com/products/obfuscators/csharpobfuscator.html) - The C# Obfuscator tool scrambles C# source code to make it very difficult to understand or reverse-engineer 
### Self-Morphing C# Binary

* [Self-Morphing C# Binary](https://github.com/bytecode77/self-morphing-csharp-binary) - C# binary that mutates its own code, encrypts and obfuscates itself on runtime
### SharpObfuscator

* [SharpObfuscator](https://archive.codeplex.com/?p=sharpobfuscator) - It is a Software Protection tool, designed to help .NET developers efficiently protect their software. It will obfuscate and protect your .NET code, optimize your .NET assembly for better deployment, minimize distribution size, increase performance & add powerful post-deployment debugging capabilities.
### Skater .NET Obfuscator

* [Skater .NET Obfuscator](http://rustemsoft.com/obfuscator.aspx) - Rustemsoft proposes Skater .NET Obfuscator, an obfuscation tool for .NET code protection. It implements all known software protection techniques and obfuscation algorithms.
### SkiDzEX

* [SkiDzEX](https://github.com/NotPrab/SkiDzEX) - A modded version of ConfuserEx | SkiDzEx
### SmartAssembly

* [SmartAssembly](https://www.red-gate.com/products/dotnet-development/smartassembly/) - Protect your .NET code and IP with SmartAssembly
### String Encrypt

* [String Encrypt](https://www.pelock.com/products/string-encrypt) - Encrypt strings in source code & files using randomly generated algorithms, and generate the corresponding unique decryption code for any supported programming language.
### StrongVM

* [StrongVM](https://github.com/Modify24x7/StrongVM) - StrongVM is a virtualizing protector for .NET applications.
### SourceCodeObfuscator

* [SourceCodeObfuscator](https://github.com/0x000N3X4N/SourceCodeObfuscator) - C# source code obfuscator
### SpecterObfuscator

* [SpecterObfuscator](https://github.com/xXeptioN/SpecterObfuscator/tree/master/Obfuscator) - This Application will obfuscate your .NET Assembly
### Spices

* [Spices](https://www.9rays.net/Category/55-spicesnet-obfuscator.aspx) - Spices.Net Obfuscator is a .Net code obfuscation, protection and optimization tool that offers the wide range of technologies to completely protect your .Net code and secure your data.
------------------
<!-- T -->
## T =>

### Themida

* [Themida](https://www.oreans.com/Themida.php) - Advanced Windows software protection system
### Trinity-ConfuserEx-Mod

* [Trinity-ConfuserEx-Mod](https://github.com/TrinityNET/Trinity-ConfuserEx-Mod) - A modded ConfuserEx created by Mighty, Bed and Centos. 
------------------
<!-- U -->
## U =>

### Unikod

* [Unikod](https://github.com/SDSkyKlouD/Unikod) - Text styling & obfuscation library for C# 
------------------
<!-- V -->
## V =>

### vot4cs

* [vot4cs](https://github.com/tum-i22/vot4cs) - A Virtualization Obfuscation Tool for C# program
### VaporObfusactor

* [VaporObfusactor](https://github.com/call-042PE/VaporObfuscator) - VaporObfuscator is an obfuscator for .net made with dnlib 
### VMProtect 3.4

* [VMProtect 3.4](https://vmpsoft.com/20190803/vmprotect-3-4/) - VMProtect protects code by executing it on a virtual machine with non-standard architecture that makes it extremely difficult to analyze and crack the software. Besides that, VMProtect generates and verifies serial numbers, limits free upgrades and much more.
------------------
<!-- Y -->
## Y =>

### Yano

* [Yano](https://yano.informer.com/) - Yano is an advanced obfuscator for Microsoft .NET applications 
------------------
<!-- Z -->
## Z =>

### Z00bfuscator

* [Z00bfuscator](https://github.com/Dentrax/Z00bfuscator) - Z00bfuscator is the simple, open-source, cross-platform obfuscator for .NET Assemblies built on .NET Core 

