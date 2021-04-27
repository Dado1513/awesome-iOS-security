# iOS-awesome-security-tools
> List of all interesting iOS tools for security purpose

---


### Utilities

- [frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump) Pull a decrypted IPA from a jailbroken device

- [checkra1n](https://github.com/checkra1n)

- [idb](https://github.com/dmayer/idb) 

- [imobax](https://github.com/Siguza/imobax). The iOS Mobile Backup Xtractor.


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
    libfuse-dev
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



- [idevicerestore](https://github.com/libimobiledevice/idevicerestore) A command-line application to restore firmware files to iOS devices.

- [ifuse](https://github.com/libimobiledevice/ifuse) A fuse filesystem implementation to access the contents of iOS devices.



**nowsecure**
- [node-applesing](https://github.com/nowsecure/node-applesign) NodeJS module and commandline utility for re-signing iOS applications (IPA files).

    ```npm install```


**ioscontrol**
- [ios-deploy](https://github.com/ios-control/ios-deploy) Install and debug iOS apps from the command line. Designed to work on un-jailbroken devices (Requirement - MacOs)





---
### Static Analysis

- [Ghidra]()
- [Cutter]()
- [Radare2]()

---
### Dynamic Analysis

- [objection](https://github.com/sensepost/objection) objection is a runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications, without needing a jailbreak.

- [Grapefruit](https://github.com/ChiChou/grapefruit) Grapefruit: Runtime Application Instruments for iOS.

- [Frida-Mobile-Scripts](https://github.com/m0bilesecurity/Frida-Mobile-Scripts) Collection of useful FRIDA Mobile Scripts



**nowsecure**
- [fsmon](https://github.com/nowsecure/fsmon) FileSystem Monitor utility that runs on Linux, Android, iOS and OSX.

- [frida-trace](https://github.com/nowsecure/frida-trace) Trace APIs declaratively through Frida.

- [frida-cycript](https://github.com/nowsecure/frida-cycript) This is a fork of [Cycript] 1 in which we replaced its runtime with a brand new runtime called [Mjølner] 3 powered by [Frida] 4. This enables frida-cycript to run on all the platforms and architectures maintained by [frida-core] 8.


--- 
### Other
- [RMS-Runtime-Mobile-Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security)
- [MobSf](https://github.com/MobSF/Mobile-Security-Framework-MobSF)






