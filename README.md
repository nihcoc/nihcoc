```
┌─ alfred@vipin:~$ whoami ─────────────────────────────────────
│
│  Alfred Vipin
│  Embedded Systems  /  RF  /  FPGA
│  Custom hardware, firmware and PCB development
│
│  github      github.com/nihcoc
│  instagram   instagram.com/alf.rde
│
└──────────────────────────────────────────────────────────────
```

[GitHub](https://github.com/nihcoc) | [Instagram](https://www.instagram.com/alf.rde/)

---

## $ ls projects/ --status

```
  NAME        STATUS    DOMAIN
  ────────────────────────────────────────────────
  PeriR       active    FPGA / RF / PCIe
  STMflow     active    STM32 / Power Electronics
  EchoSign    done      Wearables / ML
  WCIS        done      ESP32 / Irrigation
  PCBCLOCK    done      STM32 / RTC
```

---

## $ cd active/

```
┌─ PeriR ───────────────────────────────────────────── [active]
│
│  Software-defined radio for the Raspberry Pi CM4.
│  Artix-7 50T FPGA, AD9364 RF transceiver, PCIe 2.0.
│
│   AD9364 ──── data ────▶ Artix-7 50T ──── PCIe 2.0 ────▶ CM4
│    RF                     FPGA / DSP                      host
│
│  stack   FPGA  Analog Devices  PCIe  RPi  Verilog  RF
│
└───────────────────────────────────────────────────────────────
```

[github.com/nihcoc/PeriR](https://github.com/nihcoc/PeriR)

```
┌─ STMflow ─────────────────────────────────────────── [active]
│
│  STM32-based reflow oven controller.
│
│   temp ▲
│        │            ▄▄▄ peak ▄▄▄
│        │          ▄▀             ▀▄
│        │   soak ▄▀                 ▀▄ cool
│        │  ▄▄▄▄▀
│        └──────────────────────────────▶ time
│
│  stack   STM32  Power Electronics
│
└───────────────────────────────────────────────────────────────
```

---

## $ cd completed/

```
┌─ EchoSign ────────────────────────────────────────────── [done]
│
│  Wearable glove that translates hand gestures into text and speech.
│
│   sensors ──▶ Arduino ──▶ ML model ──▶ text + speech
│                   UART / Bluetooth
│
│  stack   KiCad  Machine Learning  UART  Arduino  Bluetooth
│
└───────────────────────────────────────────────────────────────
```

[github.com/nihcoc/EchoSign](https://github.com/nihcoc/EchoSign)

```
┌─ WCIS ────────────────────────────────────────────────── [done]
│
│  ESP32-based irrigation controller with custom enclosure
│  and plumbing integration.
│
│  stack   C/C++  ESP32  CAD  WiFi  Power Electronics
│
└───────────────────────────────────────────────────────────────
```

[github.com/nihcoc/WCIS](https://github.com/nihcoc/WCIS)

```
┌─ PCBCLOCK ────────────────────────────────────────────── [done]
│
│  STM32-based LED-matrix analog clock with a 32.768 kHz TCXO.
│
│  stack   C  STM32  Custom Matrix  RTC
│
└───────────────────────────────────────────────────────────────
```

[github.com/nihcoc/PCBCLOCK](https://github.com/nihcoc/PCBCLOCK)

---

```
 main  │  5 projects  │  2 active  │  3 done  │  nihcoc
```
