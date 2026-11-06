<div align="center">

<img src="assets/header.svg" width="100%" alt="Alfred Vipin - Embedded / RF / FPGA"/>

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=14&duration=3200&pause=1000&color=00E5FF&center=true&vCenter=true&width=520&lines=SDR+%2F+FPGA+%2F+PCIe;STM32+%2F+ESP32+firmware;RF+front+ends+and+custom+PCBs" alt=""/>

<br/>

[![GitHub](https://img.shields.io/badge/github-nihcoc-0a0e14?style=for-the-badge&logo=github&logoColor=00e5ff&labelColor=0a0e14&color=00e5ff)](https://github.com/nihcoc)
[![Instagram](https://img.shields.io/badge/instagram-alf.rde-0a0e14?style=for-the-badge&logo=instagram&logoColor=00e5ff&labelColor=0a0e14&color=12414d)](https://www.instagram.com/alf.rde/)

</div>

<div align="center">

```
 _____┐  ┌──┐  ┌─────┐  ┌┐ ┌──┐  ┌────────┐  ┌──┐  ┌┐ ┌─────
      └──┘  └──┘     └──┘└─┘  └──┘        └──┘  └──┘└─┘
```

</div>

## `> stack`

<div align="center">

![FPGA](https://img.shields.io/badge/FPGA-Artix--7-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![HDL](https://img.shields.io/badge/HDL-Verilog-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![RF](https://img.shields.io/badge/RF-AD9364-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![PCIe](https://img.shields.io/badge/IF-PCIe%202.0-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![STM32](https://img.shields.io/badge/MCU-STM32-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![ESP32](https://img.shields.io/badge/MCU-ESP32-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![Arduino](https://img.shields.io/badge/MCU-Arduino-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![KiCad](https://img.shields.io/badge/EDA-KiCad-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)
![C](https://img.shields.io/badge/LANG-C%2FC%2B%2B-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)

</div>

## `> active`

<div align="center">

<a href="https://github.com/nihcoc/PeriR"><img src="https://github-readme-stats.vercel.app/api/pin/?username=nihcoc&repo=PeriR&hide_border=false&border_color=12414d&bg_color=0a0e14&title_color=00e5ff&icon_color=00e5ff&text_color=9fb8c0" alt="PeriR"/></a>

</div>

```
 AD9364 RF ──── data ────▶ Artix-7 50T ──── PCIe 2.0 ────▶ RPi CM4
 transceiver               FPGA / DSP                       host
```

Software-defined radio for the Raspberry Pi CM4, built around an Artix-7 50T FPGA and the AD9364 RF transceiver, with PCIe 2.0 support.

![FPGA](https://img.shields.io/badge/FPGA-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![Analog Devices](https://img.shields.io/badge/Analog%20Devices-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![PCIe](https://img.shields.io/badge/PCIe-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![RPi](https://img.shields.io/badge/RPi-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![Verilog](https://img.shields.io/badge/Verilog-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![RF](https://img.shields.io/badge/RF-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)

<br/>

**STMflow** - STM32-based reflow oven controller.

```
 temp ▲
      │            ▄▄▄ peak ▄▄▄
      │          ▄▀             ▀▄
      │   soak ▄▀                 ▀▄ cool
      │  ▄▄▄▄▀
      └──────────────────────────────▶ time
```

![STM32](https://img.shields.io/badge/STM32-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff) ![Power Electronics](https://img.shields.io/badge/Power%20Electronics-0a0e14?style=flat-square&labelColor=0a0e14&color=00e5ff)

## `> completed`

<div align="center">

<a href="https://github.com/nihcoc/EchoSign"><img src="https://github-readme-stats.vercel.app/api/pin/?username=nihcoc&repo=EchoSign&border_color=12414d&bg_color=0a0e14&title_color=00e5ff&icon_color=00e5ff&text_color=9fb8c0" alt="EchoSign"/></a>
<a href="https://github.com/nihcoc/WCIS"><img src="https://github-readme-stats.vercel.app/api/pin/?username=nihcoc&repo=WCIS&border_color=12414d&bg_color=0a0e14&title_color=00e5ff&icon_color=00e5ff&text_color=9fb8c0" alt="WCIS"/></a>
<a href="https://github.com/nihcoc/PCBCLOCK"><img src="https://github-readme-stats.vercel.app/api/pin/?username=nihcoc&repo=PCBCLOCK&border_color=12414d&bg_color=0a0e14&title_color=00e5ff&icon_color=00e5ff&text_color=9fb8c0" alt="PCBCLOCK"/></a>

</div>

| Project | Summary | Stack |
|---|---|---|
| **EchoSign** | Wearable glove that translates hand gestures into text and speech | KiCad, Machine Learning, UART, Arduino, Bluetooth |
| **WCIS** | ESP32-based irrigation controller with custom enclosure and plumbing integration | C/C++, ESP32, CAD, WiFi, Power Electronics |
| **PCBCLOCK** | STM32-based LED-matrix analog clock with a 32.768 kHz TCXO | C, STM32, Custom Matrix, RTC |

<div align="center">

```
 _____┐  ┌──┐  ┌─────┐  ┌┐ ┌──┐  ┌────────┐  ┌──┐  ┌┐ ┌─────
      └──┘  └──┘     └──┘└─┘  └──┘        └──┘  └──┘└─┘
```

</div>
