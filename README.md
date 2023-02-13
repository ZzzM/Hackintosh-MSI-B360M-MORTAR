
<h1>
Hackintosh OpenCore EFI</br>
<a href="https://github.com/ZzzM/Hackintosh-MSI-B360M-MORTAR/tags">
  <img src="https://img.shields.io/github/v/tag/ZzzM/Hackintosh-MSI-B360M-MORTAR">
</a>
<a href="https://raw.githubusercontent.com/ZzzM/Hackintosh-MSI-B360M-MORTAR/master/LICENSE">
  <img src="https://img.shields.io/github/license/ZzzM/Hackintosh-MSI-B360M-MORTAR">
</a>
<a href="https://zzzm.github.io/2020/07/24/hackintosh/">
  <img src="https://img.shields.io/badge/docs-%E4%B8%AD%E6%96%87-red">
</a>
</h1>
<img src="assets/000.png" width="60%">  

## Kexts

| AppleALC | IntelMausi | Lilu  | NVMeFix | VirtualSMC | WhateverGreen |
| :------: | :--------: | :---: | :-----: | :--------: | :-----------: |
|  1.7.8   |   1.0.7    | 1.6.3 |  1.1.0  |   1.3.0    |     1.6.3     |


## Version History

**⚡ Ventura**

| EFI   | macOS         | OpenCore |     -      |
| ----- | ------------- | :------: | :--------: |
| 3.2   | 13.2 ~ 13.2.1 |  0.8.8   | 2023.01.26 |
| 3.1   | 13.1          |  0.8.7   | 2022.12.14 |
| 3.0.1 | 13.0.1        |  0.8.6   | 2022.11.10 |
| 3.0   | 13.0          |  0.8.5   | 2022.10.28 |


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
      <td>LG 27UP850-W</td>
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

## Benchmark

- Devices

|                                    macOS 10.15.6                                    |         CPU          |                       Graphics                       |
| :---------------------------------------------------------------------------------: | :------------------: | :--------------------------------------------------: |
|               <img src="assets/001.png" width="280px"><br>Hackintosh                | Intel Core i5-9400F  |                  AMD Radeon RX 590                   |
| <img src="assets/002.png" width="280px"><br>MacBook Pro (Retina, 15-inch, Mid 2015) | Intel Core i7-4770HQ |                    Intel Iris Pro                    |
|       <img src="assets/003.png" width="280px"><br>MacBook Pro (16-inch, 2019)       | Intel Core i7-9750H  | ① AMD Radeon Pro 5300M <br> ② Intel UHD Graphocs 630 |

- Results

|             Geekbench 5.2.0             | Single-Core | Multi-Core |              OpenCL |               Metal |
| :-------------------------------------: | ----------: | ---------: | ------------------: | ------------------: |
|               Hackintosh                |        1025 |       5118 |               38203 |               39163 |
| MacBook Pro (Retina, 15-inch, Mid 2015) |         821 |       3303 |                5152 |                 520 |
|       MacBook Pro (16-inch, 2019)       |        1073 |       5425 | ① 25241 <br> ② 5186 | ① 23814 <br> ② 4718 |


## Note

- [**OC Auxiliary Tools**](https://github.com/ic005k/QtOpenCoreConfig) can help you update **config.plist** 

- Refer [**here**](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI#%E4%BD%BF%E7%94%A8-efi) to help you adjust **BIOS Settings**


## References
- [*MSI-B360M-MORTAR-IMACPRO-EFI*](https://github.com/andot/MSI-B360M-MORTAR-IMACPRO-EFI)
- [*MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI*](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI)
