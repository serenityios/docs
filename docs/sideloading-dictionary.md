# Sideloading Dictionary

You hear a lot of words you don’t understand about iOS Sideloading, right?  
Here we’ll cover every word and definition that has to do with Sideloading.

> [!NOTE]  
> Some People make Words Shorter, You might realize what they mean from this dictionary.

> [!IMPORTANT]  
> We hope this makes you understand iOS better.

## Apps & AppClips

1. Configuration Profile / .mobileconfig - A file that installs settings, VPNs, or web clips to your device. Used for things like signing with third-party tools or setting up webapps.
2. .mobileprovision - A provisioning profile that allows apps to run on specific devices. It binds the app, certificate, and allowed UDIDs.
3. .p12 - A certificate file that includes the private key. Required to sign apps.
4. .ipa / .app - The actual app archive. .ipa is a zipped app used for sideloading.
5. Appclip / Webclip / Webapp - Lightweight versions of apps or shortcuts. Webclip creates a home screen icon that opens a website.
6. Payload of a Profile - The actual content inside a mobileconfig, like the app name, URL, or VPN settings.
7. .dylib - Dynamic library file used to inject code into apps, mostly in tweaks or jailbreak environments.
8. App Entitlements - Permissions or abilities granted to an app, like iCloud access or push notifications.
9. Certificate Entitlements - Entitlements granted to a certificate which affect what apps signed with it can do.
10. Bundle Identifier / ID - The unique string that identifies an app, like `com.example.myapp`.
11. Appname / Bundlename - Human-readable name of the app shown on the home screen.
12. Bundle Version / Version - The version number of the app, shown in settings or app info.
13. Certificate - A digital signature used to sign apps. Required to install on iOS.
14. .pem File - A plaintext format of certificates or keys. Often used for conversions.
15. .der File - A binary format of certificates. Sometimes used in Apple tools.
  

## Third Party Stores

1. ESign - Famous sideloading tool, good for reverse engineering and .ipa editing & signing.
2. Scarlet - Smooth and popular sideloading tool. Doesn’t offer as many features as ESign.
3. GBox - Sideloading tool similar to ESign.
4. Feather - Lightweight sideloading tool. Still growing in popularity.
5. AltStore - Sideloading tool using your Apple ID. Requires a computer to set up and refresh apps every 7 days.
6. SideStore - AltStore alternative that uses Wi-Fi sync to refresh apps, bypasses 3 app limit and doesn’t revoke. Needs a PC once to set up.

## Other Sideloading Terms

1. Jailbreaks - Escape Apple’s restrictions. Gives full control over your device. Risky but powerful.
2. Emulators - Apps that mimic other consoles like PSP, PS Vita, or even Windows. Lets you run non-iOS systems.
3. Tweaks - Mods for iOS or apps. Usually need jailbreak or injected through sideloaded apps.
4. Revoked - Revoked from using a Certificate to Sign Apps, Apps will not work after
5. Blacklisted - Blacklisted from a Certificate, cant install/use apps after, just like revoked
6. Whitelisted - Getting whitelisted on a certificate, apps will work and can be installed.
7. Repositories - Big Libraries of Modified/Free Apps.

## Jailbreaks

Jailbreaks - Exploits that inject code into your device, letting you do almost everything.

1. Checkra1n - Semi-tethered jailbreak for A5-A11 devices using checkm8 exploit.
2. Unc0ver - Popular jailbreak supporting iOS 11 to iOS 14 with tweak injection.
3. Taurine - Jailbreak for iOS 14 - 14.3, fast and stable with Sileo.
4. Odyssey - Jailbreak for iOS 13 - 13.7, uses modern exploits for tweaks.
5. Chimera - Jailbreak for iOS 12 with support for Sileo package manager.
6. Electra - Jailbreak for iOS 11, one of the first with Substitute tweaks.
7. RootlessJB - Partial jailbreak focusing on security research, no tweak injection.
8. Jailbreak Detection - Techniques apps use to detect if device is jailbroken.
9. Substrate - Framework for hooking and modifying iOS apps on jailbroken devices.
10. Substitute - Alternative hooking platform to Cydia Substrate, used in modern jailbreaks.

View other jailbreaks at [https://theapplewiki.com/wiki/Jailbreak](https://theapplewiki.com/wiki/Jailbreak)


# Nerd Level
> [!WARNING]  
> This is alot to comprehend

## Binary related stuff
1. .deb - Packaged Version of .dylib/.app, usually compiled with theos  
2. theos - A cross-platform build system for creating iOS, macOS, Linux, and Windows programs.  
3. compile - Turning human-written code into a language the device understands and runs.  
4. mach-o binary - Mach-O binaries are app files that run on iPhones and Macs.  
5. .dylib - .dylib files are shared libraries that apps use on iOS and Mac, it can inject code (if for cheats, like patch offsets)  
6. linker - Combines compiled code pieces into a single executable or library.  
7. runtime - The environment where a program runs and executes its instructions.  
8. static library - Code library linked during compile time, embedded into the app.  
9. dynamic library - Code library loaded during app runtime, like .dylib on iOS/macOS.  
10. patch offset - Memory address used to modify app behavior by injecting code.  
11. symbol - Name representing functions or variables in compiled binaries.  
12. framework - A bundle of shared resources, libraries, and headers for development.  
13. SDK (Software Development Kit) - Tools and libraries needed to build apps for a platform.  
14. architecture - The CPU design a binary targets, like ARM64 for iOS devices.  
15. disassembler - Tool that converts machine code back to readable assembly code.  
16. binary header - Metadata at the start of a binary describing its structure.  
17. entitlements - Permissions embedded in iOS/macOS apps defining allowed capabilities.  
18. fat binary - A binary containing code for multiple architectures in one file.  
19. injection - Technique to insert code into a running process or binary.  
20. load commands - Instructions in Mach-O binaries telling the system how to load the program.

## Reverse Engineering
1. Ghidra - Free open-source software reverse engineering tool developed by NSA.
2. Frida - Dynamic instrumentation toolkit for hooking and modifying running apps.
3. Fishhook - Library for rebinding symbols in Mach-O binaries at runtime.
4. Ellekit - Modern tweak injection platform for jailbroken iOS devices.
5. H5GG + H5GGFrida - Tools for hooking and debugging iOS apps with Frida.
6. ImGui (For UI) - Immediate mode graphical user interface library for tools/debug.
7. Hopper - Mac/iOS disassembler and decompiler for reverse engineering binaries.
8. IDA Pro - Interactive disassembler widely used for malware and app analysis.
9. LLDB - Debugger for macOS/iOS with support for runtime app inspection.
10. Radare2 - Open-source framework for reverse engineering and binary analysis.
11. Cycript - Hybrid of JavaScript and Objective-C for runtime iOS introspection.
12. Binary Ninja - User-friendly reverse engineering platform with scripting support.


> [!TIP]
> Please tell us words & definitions to add in our discord server,
it will help beginners understand more

The discord invite is in our homepage:
[Return to Homepage](https://serenityios.github.io/docs)

