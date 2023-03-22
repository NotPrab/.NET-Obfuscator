# .NET-Obfuscator

>.NET Obfuscator is a tool that is used to protect .NET applications from reverse engineering. 

* This is done by **transforming the original .NET code into a form that is difficult to understand**, making it hard for attackers to decompile the code and understand how it works. 

* This can help to **prevent the theft of intellectual property** and also protect against potential security vulnerabilities. 

* **Obfuscation** can also help to reduce the size of the code, which can improve the performance of the application.

Here is an example of a simple C# program that calculates the factorial of a given number:
```csharp
using System;

namespace FactorialCalculator
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a number:");
            int num = int.Parse(Console.ReadLine());
            int factorial = 1;

            for (int i = 1; i <= num; i++)
            {
                factorial *= i;
            }

            Console.WriteLine("The factorial of {0} is {1}", num, factorial);
        }
    }
}
```

To obfuscate this code, a .NET Obfuscator would transform it into something like this:
```csharp
using System;

namespace XZkxcX
{
    class XxXXx
    {
        static void XxXXX(string[] XxxxX)
        {
            Console.WriteLine("Enter a number:");
            int XxXx = int.Parse(Console.ReadLine());
            int XXXXXXX = 1;

            for (int XxXX = 1; XxXX <= XxXx; XxXX++)
            {
                XXXXXXX *= XxXX;
            }

            Console.WriteLine("The factorial of {0} is {1}", XxXx, XXXXXXX);
        }
    }
}
```
As you can see, the obfuscated code is much harder to understand and follow, making it difficult for someone to reverse engineer the original code.


<!-- Options -->
  - [Open Source](#open-source)
  - [Free](#free)
  - [Freemium](#freemium)
  - [Paid](#paid)

### Open Source
* [Arya](https://github.com/HarmJ0y/Arya) - Arya is a simple obfuscator for .NET binaries.
* [AsStrongAsFuck](https://github.com/Charterino/AsStrongAsFuck) - A console obfuscator for .NET assemblies.
* [BasicProxyObfucator](https://github.com/XenocodeRCE/BasicProxyObfucator) - a very basic proxy obfuscator based on dnlib 
* [BitMono](https://github.com/sunnamed434/BitMono) - An open-source, free protector for Mono 
* [ConfuserEx](https://github.com/yck1509/ConfuserEx) - An open-source, free protector for .NET applications.
* [cil-examining](https://github.com/mira-ta/cil-examining) - A .NET Framework (.NET Core in the future) obfuscator. Owner is currently out sick thus working on project is stopped.
* [Cheap Obfuscator](https://github.com/Polymeth/cheap-obfuscator) - a pretty bad obfuscator made to learn
* [dotNetObfuscator](https://github.com/baskfx/dotNetObfuscator) - Обфускатор строки для C#
* [DarkFuscator](https://github.com/isigov/.NET-Obfuscator) - Code obfuscator for .NET framework programs. Outdated in 2016, but was very functional in 2010/2011.Uses the Mono.Cecil library for interacting with .NET assemblies. 
* [Denvelope](https://github.com/TWVyY3VyaW8K/Denvelope) - NET Obfuscator
* [DotNetPatcher](https://github.com/mwsrc/DotNetObfuscator) - DotNetObfuscator
* [Goldfuscator](https://github.com/AnErrupTion/Goldfuscator) - A fork of the original SimpleObfuscator project, made for training. 
* [JIEJIE.NET](https://github.com/dcsoft-yyf/JIEJIE.NET) - An open source tool to obfuscation .NET assembly file, help you protect your copyright. small,fast and powerful. 
* [Krawk Protector](https://github.com/xHeaven/Krawk-Protector) - .NET Obfuscator and Protector 
* [KoiVM](https://github.com/Loksie/KoiVM-Virtualization) - Virtualization made for .NET using ConfuserEX 
* [lookatme](https://github.com/pjc0247/lookatme) - NET Obfuscator for Studying purpose.
* [LoGic.NET](https://github.com/AnErrupTion/LoGiC.NET) - A more advanced free and open .NET obfuscator using dnlib.
* [MdCrypt](https://github.com/wwh1004/Mdcrypt) - [WIP] A next-generation protector for .NET applications (.NET Framework, .NET Core, and more) 
* [MemeVM](https://github.com/TobitoFatitoNulled/MemeVM) - A small virtualizer for .NET which works together with ConfuserEx 
* [MindLated](https://github.com/Sato-Isolated/MindLated) -  .net obfuscator using dnlib  
* [NET-Obfuscator](https://github.com/NightBaron/.NET-Obfuscator) - Simple .net obfuscator using Mono Cecil
* [NetRenamer](https://github.com/Zenixas/NetRenamer) - Simple tool to obfuscate/rename .NET module's methods, fields, classes and more using AsmResolver. 
* [Noisette](https://github.com/XenocodeRCE/Noisette-Obfuscator) - An Obfuscator for .NET assembly 
* [obfuscatus](https://github.com/stschake/obfuscatus) - a .NET obfuscator based on mono cecil
* [Obfuscord](https://github.com/JReverse/Obfuscord) - Obfuscates A file Through Discord as a Bot using Discord.Net Api
* [Obfuscar](https://github.com/obfuscar/obfuscar) - Open source obfuscation tool for .NET assemblies
* [Obfuscator-Demonstration](https://github.com/gigajew/Obfuscator-Demonstration) -  A simple obfuscator demonstration using dnlib
* [OctopusObfuscator](https://github.com/Alxs009/OctopusObfuscator) - Basic obfuscator for .NET
* [Panda-Obfuscator](https://github.com/barotyson/Panda-Obfuscator) - PandaObfuscator an simple Obfuscator, free, OpenSource for .Net Applications 
* [PAOfuscator](https://github.com/Schaboom/PAOfuscator) - Obfuscator für Paradise.de
* [SimpleObfuscator](https://github.com/GabrieleAsaro/SimpleObfuscator) - Simple obfuscator   
* [SourceCodeObfuscator](https://github.com/0x000N3X4N/SourceCodeObfuscator) - C# source code obfuscator
* [SpecterObfuscator](https://github.com/xXeptioN/SpecterObfuscator) - This Application will obfuscate your .NET Assembly
* [Sugar-Guard](https://github.com/leexey/Sugar-Guard) - Sugar Guard 
* [Unikod](https://github.com/SDSkyKlouD/Unikod) - Text styling & obfuscation library for C# 
* [UnmanagedString](https://github.com/MrakDev/UnmanagedString) - A simple tool for converting strings to unmanaged methods using AsmResolver. 
* [vot4cs](https://github.com/tum-i22/vot4cs) - A Virtualization Obfuscation Tool for C# program
* [VaporObfusactor](https://github.com/call-042PE/VaporObfuscator) - VaporObfuscator is an obfuscator for .net made with dnlib
* [ZenFuscator](https://github.com/Zenixas/ZenFuscator) - Obfuscator To Protect .NET Assemblies From Being Reverse Engineered.  
* [Z00bfuscator](https://github.com/Dentrax/Z00bfuscator) - Z00bfuscator is the simple, open-source, cross-platform obfuscator for .NET Assemblies built on .NET Core 

### Free
* [BitHelmet](https://bithelmet.software.informer.com/) - BitHelmet obfuscator protects your .NET Portable Executables 
* [Guardship-.NET-Protector](https://github.com/Rustemsoft/Guardship-.NET-Protector) - Guardship .NET Protector is a development software that helps to protect the executable file of .NET application by making its code unreadable for MSIL disassemblers.
* [Orange Heap obfuscator](http://orangeheap.blogspot.com/) - free and efficient way to protect your .NET software
* [Phoenix Protector](https://ntcore.com/?page_id=384) - .NET Obfuscator & Protector
* [Yano](https://yano.informer.com/) - Yano is an advanced obfuscator for Microsoft .NET applications 


### Freemium
* [Agile](https://secureteam.net/acode)- Agile.NET, Powerful Code Protection, Obfuscation, and Licensing Solution for your .NET Apps
* [Aldaray Rummage Obfuscator](https://www.aldaray.com/) - Tie your code into knots and make the hackers cry
* [AppFuscator](https://appfuscator.com/) - Inteligence algorithm provide your application powerful protection! 
* [ArmDot](https://www.armdot.com/) - Protection, software licensing tool, and obfuscator for C# and .Net with support of serial keys and files embedding
* [ByteHide](https://www.bytehide.com/products/shield-obfuscator/dotnet) - ByteHide provides .NET obfuscator to companies and organizations. Providing a set of tools that protect your intellectual property, ensure the integrity of your software and reducing costs.
* [Babel](https://www.babelfor.net/) - Protect your software against reverse engineering to safeguard the intellectual property of your code
* [BoxedApp](https://www.boxedapp.com/) - Import and virtualize ActiveX, Flash and .Net runtime • Rich SDK for developers • Create custom packers • Supports both 32-bit and 64-bit applications • Virtual file system and registry
* [Crypto](https://www.ssware.com/cryptoobfuscator/obfuscator-net.htm) - Powerful Obfuscation & Code Protection For .Net That Actually Works!
* [CSharpObfuscator](https://github.com/nwtsolution/CSharpObfuscator) - CSharp Obfuscator protects your .NET application code through obfuscation transforms, while maintaining debugging abilities for quality assurance testing. 
* [DeepSea](https://deepsea-obfuscator.soft112.com/) - DeepSea Obfuscator makes obfuscation of your .NET assemblies an intuitive and integrated part of your product development.
* [Dotfuscator](https://www.preemptive.com/products/dotfuscator/overview) - Dotfucator's .NET obfuscation and runtime checks have protected thousands of apps for over a decade.
* [Eazfuscator](https://www.gapotchenko.com/eazfuscator.net) - Eazfuscator.NET protects intellectual property ingrained in software, increasing commercial profitability and allowing to keep the advantage over the competition. 
* [Enigma Protector](https://enigmaprotector.com/en/about.html) - A professional system for licensing and protecting
executable files for Windows.
* [ILProtector](http://www.vgrsoft.net/Products/ILProtector) - ILProtector is a protector for .NET applications. ILProtector is designed to protect intellectual property of the software. 
* [IntelliProtector](https://intelliprotector.com/Products/Net-Obfuscator/Features) - IntelliProtector .Net Obfuscator is excellent Free tool for your IntelliProtector .Net projects.
* [MancoSoftware](https://en.freedownloadmanager.org/Windows-PC/Manco-NET-Obfuscator.html) - Manco .NET Licensing System is the powerful licensing and copy protection software for .NET Windows Forms, WPF, WCF, WWF and ASP.NET applications, controls and components.
* [netshrink](https://www.pelock.com/products/netshrink) - netshrink is an exe packer aka executable compressor, application password protector and virtual DLL binder for Windows & Linux .NET applications.
* [NET Reactor](https://www.eziriz.com/) - NET Reactor is a powerful .NET code protection and software licensing system which completely stops any decompiling.
* [Skater .NET Obfuscator](http://rustemsoft.com/obfuscator.aspx) - Rustemsoft proposes Skater .NET Obfuscator, an obfuscation tool for .NET code protection. It implements all known software protection techniques and obfuscation algorithms.
* [SmartAssembly](https://www.red-gate.com/products/dotnet-development/smartassembly/) - Protect your .NET code and IP with SmartAssembly
* [StrongVM](https://github.com/Modify24x7/StrongVM) - StrongVM is a virtualizing protector for .NET applications.
* [Spices](https://www.9rays.net/Category/55-spicesnet-obfuscator.aspx) - Spices.Net Obfuscator is a .Net code obfuscation, protection and optimization tool that offers the wide range of technologies to completely protect your .Net code and secure your data.
* [VMProtect](https://vmpsoft.com) - VMProtect protects code by executing it on a virtual machine with non-standard architecture that makes it extremely difficult to analyze and crack the software. Besides that, VMProtect generates and verifies serial numbers, limits free upgrades and much more.

### Paid
* [Cyphor](https://cyphor.net/details) - Cyphor is more than just an obfuscator. Cyphor is the best, fastest, and most reliable obfuscation protection tool to work with.
* [DNGuard HVM](http://www.dnguard.net/index.php) - Advanced .NET Code Protection and Obfuscation Technology
* [Obfuscator.NET 2009](http://www.macrobject.com/en/obfuscator/index.htm) - Protect your .NET assembly
* [PV Logiciels dotNet Protector](http://www.pvlog.com/) - PV Logiciels dotNet Protector is a powerful .NET code protection system that prevents your assemblies from being decompiled.
* [SEEUNSHARP](https://seeunsharp.net/obfuscator/en) - Have a sophisticated .NET solution?And very curious competitors?Got something valuable to hide?Take action and protect your investment!




