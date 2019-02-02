# Google Drive CLI Client Binary Builds
This is the binary builds of the [gdrive](https://github.com/prasmussen/gdrive) CLI client by [prasmussen](https://github.com/prasmussen) on GitHub.
## Why?
It because they distribute their binary builds on Google drive, which is not very nice for HTTP CLI downloaders like [wget](https://www.gnu.org/software/wget/) and it is the reason why gdrive was invented. Recursion! By distributing their binaries on GitHub, gdrive is now wget-friendly to get.
## Installing gdrive on linux
To install gdrive on 64 bit linux
```
wget https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-x64
mv gdrive-linux-x64 gdrive
chmod +x gdrive
./gdrive about
```
### Downloads
| Filename               | Version | Description        | Shasum                                   |
|:-----------------------|:--------|:-------------------|:-----------------------------------------|
| [gdrive-osx-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/osx/gdrive-osx-x64) | 2.1.0 | OS X 64-bit | 297ccf3c945b364b5d306cef335ba44b0900e927 |
| [gdrive-osx-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/osx/gdrive-osx-386) | 2.1.0 | OS X 32-bit | c64714676a5b028aeeaf09e5f3b84d363e0ec7ed |
| [gdrive-osx-arm](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/osx/gdrive-osx-arm) | 2.1.0 | OS X arm | eb23b7bb5a072497372bd253e8fc8353bec8a64c |
| [gdrive-linux-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-x64) | 2.1.0 | Linux 64-bit | 4fd8391b300cac45963e53da44dcfe68da08d843 |
| [gdrive-linux-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-386) | 2.1.0 | Linux 32-bit | de9f49565fc62552fe862f08f84694ab4653adc2 |
| [gdrive-linux-rpi](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-rpi) | 2.1.0 | Linux Raspberry Pi | e26e9ca3df3d08f970a276782ac5e92731c85467 |
| [gdrive-linux-arm64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-arm64) | 2.1.0 | Linux arm 64-bit | 3d670905e13edf96d43c9f97293bdba62c740926 |
| [gdrive-linux-arm](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-arm) | 2.1.0 | Linux arm 32-bit | 5b1036e0ef479ce228f7c32d1adfdc3840d71d10 |
| [gdrive-linux-mips64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-mips64) | 2.1.0 | Linux mips 64-bit | 334bbd74b87fd1d05550e366724fe8e3c9e61ca4 |
| [gdrive-linux-mips64le](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-mipsle) | 2.1.0 | Linux mips 64-bit le | bb6961a2c03c074e6d34a1ec280cc69f5d5002f5 |
| [gdrive-linux-ppc64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-ppc64) | 2.1.0 | Linux PPC 64-bit | 70a1ac5be9ba819da5cf7a8dbd513805a26509ac |
| [gdrive-linux-ppc64le](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/linux/gdrive-linux-ppc64le) | 2.1.0 | Linux PPC 64-bit le | f426817ee4824b83b978f82f8e72eac6db92f2d1 |
| [gdrive-windows-386.exe](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/windows/gdrive-windows-386.exe) | 2.1.0 | Window 32-bit | 1429200631b598543eddc3df3487117cad95adbb |
| [gdrive-windows-x64.exe](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/windows/gdrive-windows-x64.exe) | 2.1.0 | Windows 64-bit | 17f692a027a049385af2576503cd376593cc87b7 |
| [gdrive-dragonfly-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/dragonfly/gdrive-dragonfly-x64) | 2.1.0 | DragonFly BSD 64-bit | dc214a24e59f68d99ca62757d99099051f83804a |
| [gdrive-freebsd-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/freebsd/gdrive-freebsd-x64) | 2.1.0 | FreeBSD 64-bit | 93a5581652f9c01c47fb6c16e8ae655182f265da |
| [gdrive-freebsd-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/freebsd/gdrive-freebsd-386) | 2.1.0 | FreeBSD 32-bit | b9a3ee1e0fdbb5fa970942ab89b354ee863a5758 |
| [gdrive-freebsd-arm](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/freebsd/gdrive-freebsd-arm) | 2.1.0 | FreeBSD arm | 7f5d1dedaa98501932ea368f2baba240da0b00d8 |
| [gdrive-netbsd-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/netbsd/gdrive-netbsd-x64) | 2.1.0 | NetBSD 64-bit | 2a088dbd1e149204eb71a47ade109816983fe53f |
| [gdrive-netbsd-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/netbsd/gdrive-netbsd-386) | 2.1.0 | NetBSD 32-bit | a2c231b91839171a58da780657c445d4a1430537 |
| [gdrive-netbsd-arm](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/netbsd/gdrive-netbsd-arm) | 2.1.0 | NetBSD arm | ac8a6354f8a8346c2bf84585e14f4a2cc69451db |
| [gdrive-openbsd-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/openbsd/gdrive-openbsd-x64) | 2.1.0 | OpenBSD 64-bit | 54be1d38b9014c6a8de5d71233cd6f208c27ac1c |
| [gdrive-openbsd-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/openbsd/gdrive-openbsd-386) | 2.1.0 | OpenBSD 32-bit | c2e08a9c7242de6d6ffa01598425fea0550076b8 |
| [gdrive-openbsd-arm](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/openbsd/gdrive-openbsd-arm) | 2.1.0 | OpenBSD arm | 22cd413c2705012b2ac78e64cc9f2b5bfa96dbea |
| [gdrive-solaris-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/solaris/gdrive-solaris-x64) | 2.1.0 | Solaris 64-bit | 2da03dfcc818a0bd3588ad850349a5a2554913fb |
| [gdrive-plan9-x64](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/plan9/gdrive-plan9-x64) | 2.1.0 | Plan9 64-bit | 7b498ce0f416a3e8c1e17f603d21a3e84c1a9283 |
| [gdrive-plan9-386](https://raw.githubusercontent.com/AnimMouse/gdrive-binaries/master/plan9/gdrive-plan9-386) | 2.1.0 | Plan9 32-bit | cccd9ba86774bc6bd70f092158e2fcafa94601c0 |
