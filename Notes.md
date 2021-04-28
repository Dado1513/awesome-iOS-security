# Some Notes about iOS security testing

**Connect to a Device via SSH over USB**
- Install [usbmuxd](https://github.com/libimobiledevice/usbmuxd)
- Start proxy
```shell
iproxy 2222 22
```
- Connect to device
```shell
ssh -p 2222 root@localhost
```