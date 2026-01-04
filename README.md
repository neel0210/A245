![Tanjiro Kernel Banner](https://github.com/neel0210/IMG_WALL/blob/main/Tanjoro.png)

# Tanjiro Kernel

_Precision, stability, and power. A modern Android 15 kernel with KernelSU support for Samsung Galaxy A24._

#### Tanjiro kernel source for the Samsung Galaxy A24

Supports the following devices:

- Samsung Galaxy A24 (`SM-A245F`)
- Samsung Galaxy A24 (`SM-A245M`)

---

## Kernel Information

- **Kernel Name:** Tanjiro
- **Linux Version:** 5.10.226
- **Android Base:** Android 15
- **Root Solution:** KernelSU (KSU) enabled
- **Architecture:** arm64

---

## About

Tanjiro is a custom kernel built specifically for the **Samsung Galaxy A24**, based on **Android 15 kernel sources**.  
The primary goals of Tanjiro are **stability**, **performance**, and **modern root support**, while maintaining compatibility with One UI–based and custom ROMs.

The kernel is designed to be clean, minimal, and reliable, avoiding unnecessary hacks while still offering meaningful enhancements for power users and developers.
---

## KernelSU (KSU)

Tanjiro Kernel includes **KernelSU** for modern, kernel-level root management.

KernelSU provides:
- Systemless root access
- Kernel-level security model
- Module support
- Improved compatibility compared to traditional root solutions

> **Note:** KernelSU Manager is required to manage root permissions and modules.

---
## Download

<p align="left">
  <a href="https://github.com/neel0210/android_kernel_samsung_a245M/releases">
    <img src="https://img.shields.io/badge/Download_Tanjiro_Kernel-Releases-blue?style=for-the-badge&logo=github" alt="Download Tanjiro Kernel">
  </a>
</p>

## How to Install

**Requirements:**
- Unlocked bootloader
- Custom recovery (TWRP / SHRP / OrangeFox or equivalent) or Odin

### Installation Steps

1. Download the latest Tanjiro Kernel ZIP or tar from Releases.
2. Copy the ZIP file to your device storage - (To flash using recovery) | use .tar for Odin in AP section.
5. Reboot to **System**.
6. Enjoy.

---

## Building Locally

To build Tanjiro Kernel locally, simply run:

```bash
bash build.sh
