# Hackintosh-B550
My Hackintosh files and info for my AMD PC

## Device Information

| Parts       | Variant                        |
| ----------- | ------------------------------ |
| CPU         | AMD Ryzen R5 5600X 6 Core 12 Threads          |
| iGPU        | None                           |
| dGPU        | Asus Dual RX 6600XT            |
| MotherBoard | [MSI B550M Mortar WIFI](https://www.msi.com/Motherboard/MAG-B550M-MORTAR-WIFI/Specification) |
| WiFi / BT   | AX200(Default Branch) or Broadcom bcm94360(Broadcom Branch) |
| Nvme        | Samsung 980 Pro 1TB            |
| RAM         | 3600Mhz 8G x 4                 |
| MacOS       | 15.6.1 (24G90)                 |
| OpenCore    | 1.0.5                          |

## Notable Changes
Need to change `alcid=11` to have sound, however, larger `alcid` might work better.

Need to set `PP,PP_WorkLoadPolicyMask` to `0x04` to stop GPU coil whine even with light usage. [1](https://www.reddit.com/r/hackintosh/comments/1126t9k/comment/j8judxi/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) [2](https://www.reddit.com/r/hackintosh/comments/reu78e/comment/hodzjox/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) [3](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.Radeon.en.md)
