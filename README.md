<!---  Update the following   -->

[os_img]: https://img.shields.io/badge/macOS-14.5-6D67E4
[os_link]: https://support.apple.com/en-hk/HT214106

[oc_img]: https://img.shields.io/badge/OpenCore-1.0.0-519872
[oc_link]: https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.0

[oclp_img]: https://img.shields.io/badge/OpenCore_Legacy_Patcher-1.4.3-blue
[oclp_link]: https://github.com/dortania/OpenCore-Legacy-Patcher/releases/tag/1.4.3

<!---              -->

[bs_img]: https://img.shields.io/badge/BIOS-7B23v1A-yellow
[bs_link]: https://www.msi.com/Motherboard/B360M-MORTAR/support


[dc_img]: https://img.shields.io/badge/docs-%E4%B8%AD%E6%96%87-red
[dc_link]: https://zzzm.github.io/2020/07/24/hackintosh/

[ls_img]: https://img.shields.io/github/license/ZzzM/Hackintosh-MSI-B360M-MORTAR
[ls_link]: https://raw.githubusercontent.com/ZzzM/Hackintosh-MSI-B360M-MORTAR/master/LICENSE

# Hackintosh OpenCore EFI
[![os_img]][os_link]
[![oc_img]][oc_link]
[![oclp_img]][oclp_link]
[![bs_img]][bs_link]
[![dc_img]][dc_link]
[![ls_img]][ls_link]


<img src="Assets/about.png" width="25%">

## Sonoma 🆕 


| EFI   | macOS             | OC & OCLP         |     -      |
| ----- | ----------------- | :---------------: | :--------: |
| 4.5   | 14.5              |  1.0.0 & 1.4.3    | 2024.05.17 |
| 4.4   | 14.4 ~ 14.4.1     |  0.9.9 & 1.4.3    | 2024.04.09 |
| 4.3   | 14.3 ~ 14.3.1     |  0.9.8 & 1.3.0    | 2024.02.28 |
| 4.2.1 | 14.2.1 ~ 14.3     |  0.9.7 & 1.3.0    | 2024.01.24 |

## Kexts

<table>
    <tr>
      <td>AppleALC</td>
      <td>1.9.1</td>
    </tr>
    <tr>
      <td>IntelMausiEthernet</td>
      <td>1.0.8</td>
    </tr>
    <tr>
      <td>Lilu</td>
      <td>1.6.8</td>
    </tr>
    <tr>
      <td>NVMeFix</td>
      <td>1.1.2</td>
    </tr>
    <tr>
      <td>USBInjectAll</td>
      <td>0.8.0</td>
    </tr>
    <tr>
      <td>VirtualSMC</td>
      <td>1.3.3</td>
    </tr>
    <tr>
      <td>WhateverGreen</td>
      <td>1.6.7</td>
    </tr>
</table>

**Sonoma Requirements**

<table>
    <tr>
      <td>IOSkywalkFamily</td>
      <td>1.0</td>
    </tr>
    <tr>
      <td>IO80211FamilyLegacy</td>
      <td>1200.12.2b1</td>
    </tr>
    <tr>
      <td>IO80211FamilyLegacy Plugin - AirPortBrcmNIC</td>
      <td>1400.1.1</td>
    </tr>
    <tr>
      <td>AMFIPass</td>
      <td>1.4.0</td>
    </tr>
</table>

## Version History

<details>
<summary><b> Ventura </b></summary>

| EFI   | macOS             | OpenCore |     -      |
| ----- | ----------------- | :------: | :--------: |
| 3.6.3 | 13.6.3            |  0.9.7   | 2023.12.14 |
| 3.6   | 13.6 ~ 13.6.1     |  0.9.5   | 2023.10.28 |
| 3.5.1 | 13.5 ~ 13.6       |  0.9.4   | 2023.08.08 |
| 3.5   | 13.5              |  0.9.3   | 2023.07.25 |
| 3.4   | 13.4 ~ 13.4.1 (c) |  0.9.2   | 2023.05.19 |
| 3.3   | 13.3 ~ 13.3.1 (a) |  0.9.0   | 2023.03.28 |
| 3.2   | 13.2 ~ 13.2.1     |  0.8.8   | 2023.01.26 |
| 3.1   | 13.1              |  0.8.7   | 2022.12.14 |
| 3.0.1 | 13.0.1            |  0.8.6   | 2022.11.10 |
| 3.0   | 13.0              |  0.8.5   | 2022.10.28 |

</details>

<details>
<summary><b> Monterey </b></summary>

| EFI   | macOS         | OpenCore |     -      |
| ----- | ------------- | :------: | :--------: |
| 2.6   | 12.6 ~ 12.6.1 |  0.8.4   | 2022.09.13 |
| 2.5   | 12.5 ~ 12.5.1 |  0.8.3   | 2022.08.05 |
| 2.4   | 12.4          |  0.8.0   | 2022.05.17 |
| 2.3   | 12.3 ~ 12.3.1 |  0.7.9   | 2022.03.15 |
| 2.2.1 | 12.2.1        |  0.7.8   | 2022.02.14 |
| 2.2   | 12.2          |  0.7.7   | 2022.01.28 |
| 2.1   | 12.1          |  0.7.6   | 2021.12.14 |
| 2.0.1 | 12.0.1        |  0.7.5   | 2021.11.02 |

</details>


<details>
<summary><b> Big Sur </b></summary>

| EFI   | macOS  | OpenCore |     -      |
| ----- | ------ | :------: | :--------: |
| 1.9.1 | 11.6.1 |  0.7.4   | 2021.10.27 |
| 1.9   | 11.6   |  0.7.3   | 2021.09.15 |
| 1.8   | 11.5.2 |  0.7.2   | 2021.08.14 |
| 1.7   | 11.5.1 |  0.7.1   | 2021.07.22 |
| 1.6   | 11.4   |  0.6.9   | 2021.05.25 |
| 1.5   | 11.3.1 |  0.6.8   | 2021.05.01 |
| 1.4   | 11.2.3 |  0.6.7   | 2021.03.10 |
| 1.3   | 11.2.2 |  0.6.6   | 2021.02.10 |
| 1.2   | 11.1   |  0.6.4   | 2020.12.17 |
| 1.1   | 11.0.1 |  0.6.3   | 2020.11.06 |

</details>

<details>
<summary><b> Catalina </b></summary>

| EFI | macOS   | OpenCore |     -      |
| --- | ------- | :------: | :--------: |
| 1.0 | 10.15.7 |  0.6.0   | 2020.07.23 |

</details>


## Working

- [x] Audio
- [x] Graphics / Hardware Acceleration ( H.264 & HEVC )
- [x] WiFi & Bluetooth, USB
- [x] Shutdown & Restart, Sleep & Wake
- [x] Sleep & Wake
- [x] AirDrop, SharePlay, Handoff
- [x] App Store, FaceTime, iMessage 

## Hardware & Peripherals

<table>
    <tr>
      <td>Motherboard</td>
      <td>MSI B360M MORTAR</td>
    </tr>
    <tr>
      <td>CPU</td>
      <td>Intel Core i5-9400F</td>
    </tr>
    <tr>
      <td>Graphics</td>
      <td>Sapphire Radeon RX 590 NITRO+ SE</td>
    </tr>
     <tr>
      <td>SSD</td>
      <td>HIKVISION C2000 PRO 512GB</td>
    </tr>
    <tr>
      <td>RAM</td>
      <td>Apacer PANTHER 16GB(2x8GB) DDR4 2666Mhz C16</td>
    </tr>
     <tr>
      <td>Power</td>
      <td>Super Flower HX550W 80 Plus Gold</td>
    </tr>
     <tr>
      <td>WiFi & Bluetooth	</td>
      <td>Fenvi FV-T919 BCM94360CD</td>
    </tr>
    <tr>
      <td>Monitor</td>
      <td>Xiaomi RMMNT27NU</td>
    </tr>
    <tr>
      <td>Webcam & Microphone</td>
      <td>Logitech C920 PRO</td>
    </tr>
    <tr>
      <td>Mouse</td>
      <td>Logitech G PRO WIRELESS</td>
    </tr>
    <tr>
      <td>Trackpad</td>
      <td>Apple Magic Trackpad</td>
    </tr>
    <tr>
      <td>Keyboard</td>
      <td>Apple Magic Keyboard </td>
    </tr>
</table>


## Recommended

- [BIOS Settings](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI/blob/master/README.en.md#bios-settings)
- [OpenCore Auxiliary Tools ](https://github.com/ic005k/QtOpenCoreConfig)

## Credits
- [andot](https://github.com/andot/MSI-B360M-MORTAR-IMACPRO-EFI)
- [GeQ1an](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI)
- [黑果小兵](https://blog.daliansky.net/)
- [Hackintool](https://github.com/benbaker76/Hackintool)
- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [OpenCore Auxiliary Tools ](https://github.com/ic005k/QtOpenCoreConfig)
- [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
