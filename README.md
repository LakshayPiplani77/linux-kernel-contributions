# linux-kernel-contributions
This repository serves as a technical portfolio of my Linux kernel development and upstream contribution journey.

I worked primarily in the areas of:

- Linux Kernel Device Drivers
- Linux I3C Subsystem
- MFD Subsystem
- Regulator Subsystem
- HWMON Subsystem
- RTC Subsystem
- Counter Subsystem
- Industrial I/O (IIO) Subsystem
- Device Tree Bindings
- Embedded Linux BSP Development

This repository documents my **mainlined contributions**, **accepted patchsets**, **ongoing upstream development**, and **learnings from the Linux kernel review process**.

---

## 🚀 Featured Work

### NXP P3H2x4x I3C Hub Driver

Ongoing upstream development for the **NXP P3H2x4x I3C Hub family**.

Highlights:

- Generic Linux I3C Hub Framework
- Virtual I3C Controller Architecture
- MFD Driver
- Regulator Driver
- Device Tree Bindings

🔗 Patch Series:  
https://lore.kernel.org/linux-i3c/20260525064209.2263045-1-lakshay.piplani@nxp.com/T/#t

📄 Detailed Notes:  
[i3c/p3h2x4x-i3c-hub.md](i3c/p3h2x4x-i3c-hub.md)

---

## ✅ Mainlined Contributions

| Subsystem | Contribution | Link | Details |
|---|---|---|---|
| HWMON | P3T1750 Temperature Sensor Driver | [Mainline Commit](https://github.com/torvalds/linux/commit/83b3354a4ad9a784a3335a2c303c693f521d1e47) | [Read More](hwmon/p3t1750.md) |

---

## 📨 Reviewed & Ongoing Contributions

| Subsystem | Contribution | Link | Details |
|---|---|---|---|
| RTC | PCF85363 Oscillator Offset Calibration Support | [Patchwork](https://patchwork.ozlabs.org/project/rtc-linux/patch/20251121121137.3043764-4-lakshay.piplani@nxp.com/) | [Read More](rtc/pcf85363.md) |
| RTC | PCF85053A RTC Support | [Patchwork](https://patchwork.ozlabs.org/project/rtc-linux/patch/20251127120456.1849177-2-lakshay.piplani@nxp.com/#3643179) | [Read More](rtc/pcf85053a.md) |

---

## 🔍 Additional Upstream Contributions

| Subsystem | Contribution | Link | Details |
|---|---|---|---|
| Counter | PCF85263 Counter Driver | [LKML](https://lkml.org/lkml/2025/9/16/13) | [Read More](counter/pcf85263.md) |
| IIO | P3T1755 IIO Driver | [Patchew](https://patchew.org/linux/20251008100713.1198461-1-lakshay.piplani@nxp.com/20251008100713.1198461-2-lakshay.piplani@nxp.com/) | [Read More](iio/p3t1755.md) |

---

## 🔗 Quick Navigation

- 🌡️ [P3T1750 HWMON Driver](hwmon/p3t1750.md)
- 🕒 [PCF85363 RTC Calibration](rtc/pcf85363.md)
- ⏰ [PCF85053A RTC Support](rtc/pcf85053a.md)
- ⚡ [P3H2x4x I3C Hub Driver](i3c/p3h2x4x-i3c-hub.md)
- 🔄 [PCF85263 Counter Driver](counter/pcf85263.md)
- 📈 [P3T1755 IIO Driver](iio/p3t1755.md)

---

## 📁 Repository Structure

```text
linux-kernel-contributions/
├── README.md
├── hwmon/
│ └── p3t1750.md
├── rtc/
│ ├── pcf85363.md
│ └── pcf85053a.md
├── i3c/
│ └── p3h2x4x-i3c-hub.md
├── counter/
│ └── pcf85263.md
└── iio/
    └── p3t1755.md
