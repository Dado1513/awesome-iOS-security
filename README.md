# iOS awesome security tools
> List of all interesting iOS tools for security purpose
---


### Utilities

- [itms-services](https://www.npmjs.com/package/itms-services) Getting the IPA File from an OTA Distribution Link

```shell
$ npm install -g itms-services
$ itms-services -u "itms-services://?action=download-manifest&url=https://s3-ap-southeast-1.amazonaws.com/test-uat/manifest.plist" -o - > out.ipa
```

- [ipainstaller](https://github.com/autopear/ipainstaller). The IPA can also be directly installed on the iOS device via the command line with ipainstaller

- [Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper)

- [frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump) Pull a decrypted IPA from a jailbroken device

- [checkra1n](https://github.com/checkra1n)

- [unc0ver.dev](https://unc0ver.dev/)

- [idb](https://github.com/dmayer/idb) 

- [idb-facebook](https://github.com/facebook/idb/). Tool for replacing WebDriverAgent.

- [WebDriverAgent](https://github.com/facebookarchive/WebDriverAgent). Archive.

- [imobax](https://github.com/Siguza/imobax). The iOS Mobile Backup Xtractor.

- [Clutch](https://github.com/KJCracks/Clutch). Clutch is a high-speed iOS decryption tool. Clutch supports the iPhone, iPod Touch, and iPad as well as all iOS version, architecture types, and most binaries. Clutch is meant only for educational purposes and security research.

- [ish](https://github.com/ish-app/ish). A project to get a Linux shell running on iOS, using usermode x86 emulation and syscall translation.



- [plistutil]() 
```shell
$ apt install libplist-utils
$ plistutil -i Info.plist -o Info_xml.plist
```




**[libimobiledevice](https://libimobiledevice.org/)**

Requirements

```shell
sudo apt-get install \
	build-essential \
	checkinstall \
	git \
	autoconf \
	automake \
	libtool-bin \
    libzip-dev \
    libxml2-dev \
	libcurl4-openssl-dev \
    zlib1g-dev \
    libfuse-dev \
	libreadline-dev \
	libusb-1.0-0-dev \
```

```shell
sudo apt-get install \
	doxygen \
	cython
```

All modules are installed with the  following commands (in the following order)


```shell
./autogen.sh
make
sudo make install
sudo ldconfig 
```
- [usbmuxd](https://github.com/libimobiledevice/usbmuxd) A socket daemon to multiplex connections from and to iOS devices.

- [libplist](https://github.com/libimobiledevice/libplist) A small portable C library to handle Apple Property List files in binary or XML format.

- [libusbmuxd](https://github.com/libimobiledevice/libusbmuxd) A client library for applications to handle usbmux protocol connections with iOS devices.

- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) A library to communicate with services on iOS devices using native protocols.

- [ideviceinstaller](https://github.com/libimobiledevice/ideviceinstaller) A command-line application to manage apps and app archives on iOS devices.

- [libideviceactivation](https://github.com/libimobiledevice/libideviceactivation) A library to manage the activation process of Apple iOS devices.

- [ifuse](https://github.com/libimobiledevice/ifuse) A fuse filesystem implementation to access the contents of iOS devices.

- [libirecovery](https://github.com/libimobiledevice/libirecovery) The libirecovery library allows communication with iBoot/iBSS of iOS devices via USB.

- [idevicerestore](https://github.com/libimobiledevice/idevicerestore) A command-line application to restore firmware files to iOS devices.

- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.


**nowsecure**

- [r2frida](https://github.com/nowsecure/r2frida) Radare2 and Frida better together.

- [node-applesing](https://github.com/nowsecure/node-applesign) NodeJS module and commandline utility for re-signing iOS applications (IPA files).

    ```npm install```

- [ipa-extract-info](https://github.com/nowsecure/ipa-extract-info) Extract the Info.plist from an IPA, in node.js and the browser!

**ioscontrol**
- [ios-deploy](https://github.com/ios-control/ios-deploy) Install and debug iOS apps from the command line. Designed to work on un-jailbroken devices (Requirement - MacOs)



---
### Static Analysis

- [Ghidra](https://ghidra-sre.org/)
	- [Ghidra-script](https://github.com/ghidraninja/ghidra_scripts) 
- [Cutter](https://cutter.re/)
- [Radare2](https://rada.re/n/)

---
### Dynamic Analysis
- [Fastbot_iOS](https://github.com/bytedance/Fastbot_iOS) Fastbot is a model-based testing tool for modeling GUI transitions to discover app stability problems. It combines machine learning and reinforcement learning techniques to assist discovery in a more intelligent way.

- [introspy-iOS](https://github.com/iSECPartners/Introspy-iOS) Blackbox tool to help understand what an iOS application is doing at runtime and assist in the identification of potential security issues.

- [iOS-Debug-Hacks](https://github.com/aozhimin/iOS-Debug-Hacks)

- [objection](https://github.com/sensepost/objection) objection is a runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications, without needing a jailbreak.

- [Grapefruit](https://github.com/ChiChou/grapefruit) Grapefruit: Runtime Application Instruments for iOS.

- [Frida-Mobile-Scripts](https://github.com/m0bilesecurity/Frida-Mobile-Scripts) Collection of useful FRIDA Mobile Scripts

- [frida-ios-hook](https://github.com/noobpk/frida-ios-hook). A script that helps you trace classes, functions, and modify the return values of methods on iOS platform.

- [iOS-Tagent](https://github.com/AirtestProject/iOS-Tagent). iOS-Tagent is a project based on facebook WebDriverAgent and intend to fit Airtest Project.





**nowsecure**
- [fsmon](https://github.com/nowsecure/fsmon) FileSystem Monitor utility that runs on Linux, Android, iOS and OSX.

- [frida-trace](https://github.com/nowsecure/frida-trace) Trace APIs declaratively through Frida.

- [frida-cycript](https://github.com/nowsecure/frida-cycript) This is a fork of [Cycript] 1 in which we replaced its runtime with a brand new runtime called [Mjølner] 3 powered by [Frida] 4. This enables frida-cycript to run on all the platforms and architectures maintained by [frida-core] 8.

- [frida-screenshot](https://github.com/nowsecure/frida-screenshot) Grab screenshots using Frida.



--- 
### Other
- [RMS-Runtime-Mobile-Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security)

- [MobSf](https://github.com/MobSF/Mobile-Security-Framework-MobSF)

---
### Cydia
- [AppSync](https://cydia.akemi.ai/?page/net.angelxwind.appsyncunified). AppSync is a tweak that patches installd, allowing the installation of fake-signed IPA packages

- [Cydia Impactor](http://www.cydiaimpactor.com/). This tool was originally created to
jailbreak iPhones, but has been rewritten to sign and install IPA packages to iOS devices via sideloading.


### Resources and Tutorial

- [ios-frida-objection-cheat-sheet](https://www.virtuesecurity.com/kb/ios-frida-objection-pentesting-cheat-sheet/)
- [ios-Swift Anti-Jailbreak Bypass with Frida](https://syrion.me/blog/ios-swift-antijailbreak-bypass-frida/)
- [RE-iOS-Apps](https://github.com/ivRodriguezCA/RE-iOS-Apps)
- [iOS-Bypass-Jailbreak](https://philkeeble.com/ios/reverse-engineering/iOS-Bypass-Jailbreak/)
- [Post-on-iOS-RE](https://philkeeble.com/categories/#ios)

### CTF
- [NCC-CON-2018](https://ch1kpee.com/2018/01/08/ncc-con-2018-ios-ctf-solutions/)
- [awesome-mobile-ctf](https://github.com/xtiankisutsa/awesome-mobile-CTF)
- [ios-ctf](https://www.ivrodriguez.com/mobile-ctf/)
- [Walkthrough of an iOS CTF](https://www.optiv.com/explore-optiv-insights/source-zero/walkthrough-ios-ctf)
- [H1702 CTF](http://redgetan.cc/h1_702-ctf-reversing-ios-android-arm-writeup/)
- [frida-ios-jailbreak-bypass](https://syrion.me/blog/ios-swift-antijailbreak-bypass-frida/)
- [bypass-jailbreak-detection-ios](https://blog.attify.com/bypass-jailbreak-detection-frida-ios-applications/)
