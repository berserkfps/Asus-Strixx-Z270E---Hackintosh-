# ASUS-STRIXX Z270-E-OpenCore Hackintosh
<p align="center">
<b>Ready-to-use OpenCore 1.0.4 EFI for Asus Z270-E (Desktop) for Latest MacOs - Sequoia</b>
</p>

<p align="center">
<img width="282" height="548" src="https://github.com/berserkfps/Asus-Strixx-Z270E---Hackintosh-/blob/main/About%20this%20Mac.png">
</p>



> ❓ If you don't know how to use this EFI, please refer to this [guide](https://dortania.github.io/OpenCore-Install-Guide/)<br>
> ⚠️ If you want to use this EFI with your Hackintosh, Generate a new SMBIOS!! please refer to this [guide](https://youtu.be/JtYAAjgniIc) (but generate serial for Imac19,2 not Imac18,2) to avoid any problems<br>
## ☑️ Supported versions
| macOS |  | OpenCore| | EFI |

| Sequoia| | 1.0.4 | [Download](EFI.zip)


## 🔘 Status
| Feature | Works? | Notes |
| :---: | :---: | :---: |
| **Built-in Wi-Fi & Bluetooth** | ❌ | Need Itlwm+Heliport |
| **Ethernet** | ✅ | Need IntelMausi.kext |
| **Intel GPU (iGPU)** | ✅ | Works with Patches in Device-properties |
| **Audio** | ✅ | OOB |
| **USB 2, USB 3 & USB-C** | ✅ | Map USB Ports with UsbToolBox |
| **Sleep** | ✅ | OOB |
| **Nvidia GPU** | ❌ | Need AMD GPU, lot of Nvidia GPU's no longer supported in new versions of MacOS |

## 🔧 BIOS Settings
| Setting | Enabled? |
| :---: | :---: |
| Secure Boot | ❌ |
| Fast Boot | ❌ |
| Intel Virtual Technology | ✅ |
| Intel Platform Trust Technology | ❌ |





## Acknowledgments
**[dortania](https://github.com/dortania/)** for [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)<br>
**[acidanthera](https://github.com/acidanthera)** for [OpenCore](https://github.com/acidanthera/OpenCorePkg) and most of the kexts and drivers<br>
**[USBToolBox](https://github.com/USBToolBox)** for [USBToolBox & UTBmap](https://github.com/USBToolBox/kext) kexts<br>
**[ferxiit](https://github.com/ferxiit)** for inspiration how to write this ReadMe<br>
**[Hackintosh Discord](https://discord.gg/Wxam8aH)** awesome support from like-minded people!<br>
