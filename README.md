# Awesome-Embedded-Linux-Single-Board-Computers

<p align="center">
  <img src="./assets/banner.svg" alt="Top Embedded Linux & Single-Board Computers" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# 🖥️ Top Embedded Linux & Single-Board Computers

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Embedded Linux Build Systems, SBC Operating Systems, OTA Firmware Updates, Fleet Management & Edge Hardware Tooling*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Linux & Single-Board Computers (SBCs)**. These tools power custom embedded Linux distributions (`Yocto`, `Buildroot`, `Armbian`), A/B over-the-air (OTA) firmware updates, remote SSH/VPN device fleets, hardware observability, and Raspberry Pi / NVIDIA Jetson / BeagleBone / RISC-V SBC automation for embedded engineers, IoT developers, and hardware startups.

**Examples** include AWS IoT Greengrass, Azure IoT Edge, JFrog Connect, Edge Impulse (Qualcomm), Particle Cloud, BalenaCloud, Mender (Northern.tech), Memfault, Toradex Cloud (Torizon), and Upswift.

**🚀 Open-source emphasis**: This section includes the premier active open-source projects for embedded Linux build frameworks (`OpenWrt`, `Buildroot`, `Yocto Project / Poky`, `OpenEmbedded-Core`), official SBC kernel distributions (`Raspberry Pi Linux`, `Armbian`, `DietPi`, `BeagleBoard Linux`), open-source OTA update engines (`SWUpdate`, `RAUC`, `Mender Client`), bootloaders (`U-Boot`), and specialized embedded runtimes (`Home Assistant OS`, `Klipper`, `Raspberry Pi Imager`, `Sony Flutter Embedded Linux`, `meta-balena`).

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global Embedded Linux and Single-Board Computer (SBC) ecosystem represents an estimated **$4.5B–$6.0B SBC hardware market** and an estimated **$15B–$19B Embedded OS & IoT Fleet Management software sector in 2026**, expanding at ~11%–14% CAGR driven by edge AI, smart robotics, and ARM64/RISC-V deployments. The SaaS and device management landscape is **moderately fragmented**—divided between hyperscaler infrastructure (AWS Greengrass, Azure IoT Edge), focused OTA/observability pure-plays (balenaCloud, Mender, Memfault), and SoM/hardware-coupled ecosystems (Toradex Cloud, Particle)—while the foundational build and runtime layers remain **heavily consolidated around open-source standards** (Linux Kernel, Yocto, Buildroot, and U-Boot).

## ☁️ SaaS/Hosted Platforms

*Sorted descending by company scale (market valuation / annual revenue).*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier Pricing | Free Tier Limit / Free Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure IoT Edge](https://azure.microsoft.com/products/iot-edge/)** | Microsoft cloud-managed edge runtime deploying containerized modules, Azure AI models, and telemetry pipelines onto Linux & Windows SBCs. | **Part of Microsoft** (~$3.1T market cap; ~$85B+ Azure cloud revenue) | **$10 / month** (Azure IoT Hub S1 standard unit for up to 400,000 messages/day) | **Forever Free IoT Hub F1 Tier**: Up to **500 registered devices** and **8,000 messages/day** free forever (plus 30-day $200 Azure cloud trial credits) |
| **[AWS IoT Greengrass](https://aws.amazon.com/greengrass/)** | Edge runtime from Amazon enabling Linux SBCs and gateways to run local Lambda functions, Docker containers, stream data, and run ML inference locally. | **Part of Amazon / AWS** (~$2.1T market cap; ~$115B+ AWS annual revenue) | **$0.16 / active device / month** (plus standard AWS IoT Core messaging at $1.00/million messages) | **12-Month AWS Free Tier**: Up to **3 Greengrass core devices** free for 12 months (plus 250,000 IoT Core messages/month free) |
| **[Edge Impulse](https://edgeimpulse.com)** | Cloud ML engineering platform for training, optimizing, and deploying sensor and computer vision edge AI models directly onto Linux SBCs. | **Acquired by Qualcomm** (~$150M+ acquisition scale; ~$39B+ Qualcomm revenue) | **$20 / developer seat / month** (Professional tier; Enterprise custom volume contracts) | **Forever Free Developer Tier**: Free forever with unlimited personal projects, **20 min compute jobs**, 4 GB dataset storage, and full C++/Linux SDK exports |
| **[JFrog Connect](https://jfrog.com/connect/)** | Cloud-native Linux IoT device management platform providing micro-OTA updates, remote reverse-SSH/VNC terminals, and fleet monitoring. | **Part of JFrog Ltd.** (~$3.8B market cap; ~$430M+ annual revenue) | **$40 / month** (Artifactory/Connect cloud starter package with integrated device management) | **Forever Free Sandbox Tier**: Up to **5 connected Linux devices** free forever with remote shell and OTA scripting (or 14-day Enterprise trial with 50 devices) |
| **[Particle Cloud](https://particle.io)** | End-to-end IoT platform providing cellular/Wi-Fi hardware-to-cloud connectivity, fleet diagnostics, and remote OTA firmware management. | **~$150M–$250M Valuation** (~$35M+ ARR; $90M+ total venture funding) | **$49 / month** (Growth tier starting block; scale blocks available at $299/mo for 100+ cellular/Wi-Fi units) | **Forever Free Sandbox Tier**: Up to **100 devices** and **100,000 Data Operations/month** free forever with no credit card required |
| **[balenaCloud](https://balena.io)** | Container-based fleet management platform for Raspberry Pi, Jetson, and industrial SBCs featuring delta updates, VPN tunnels, and balenaOS. | **~$100M–$150M Valuation** (~$18M+ ARR; backed by OpenOcean and Balderton) | **$119 / month** (Pilot tier for up to 100 devices; additional devices billed at $2.00/device/month) | **Forever Free Starter / Prototype Plan**: Up to **10 devices** free forever with full container deployments, web terminal, and device URLs |
| **[Toradex Cloud (Torizon)](https://www.toradex.com/torizon)** | Industrial-grade embedded Linux OS and cloud fleet management platform built around Yocto/OSTree for Toradex SoMs and ARM-based SBCs. | **~$80M–$120M Revenue** (Privately held Swiss industrial embedded computer leader) | **$350 / month** (Torizon Cloud Team tier with advanced offline fleet management and multi-user RBAC) | **Forever Free Evaluation Tier**: Up to **5 devices** free forever with secure rootfs/container OTA updates and remote monitoring |
| **[Memfault](https://memfault.com)** | IoT and Linux reliability platform offering automated core dump analysis, device metrics telemetry, and staged OTA cohort updates. | **~$100M Valuation** (~$35M+ Series B funding led by Stripes) | **$250 / month** (Starting Team tier covering initial fleet monitoring and crash-analytics quotas) | **14-Day Full Access Free Trial**: Up to **50 evaluation devices** free for 14 days with full access to crash analytics, alerts, and OTA cohorts |
| **[Mender](https://mender.io)** | Robust open-source and hosted OTA software update management server supporting atomic dual-rootfs A/B rollback for Linux SBCs. | **~$50M–$80M Valuation** (Part of Northern.tech AS; ~$15M+ group ARR) | **$32 / month** (Mender Starter plan covering up to 10 active devices; add-on devices at $0.60–$1.20/device/month) | **12-Month Free Trial Plan**: Up to **10 devices** free for 12 months with production A/B dual-partition updates and hosted UI |
| **[Upswift (JFrog Connect Legacy)](https://jfrog.com/connect/)** | Lightweight embedded Linux agent and dashboard delivering fast container deployments, remote control, and hardware telemetry. | **Acquired by JFrog** (~$15M–$25M transaction scale) | **$40 / month** (Integrated within JFrog Connect cloud subscription) | **Forever Free Tier**: Up to **5 Linux SBCs** free forever for remote shell, file explorer, and OTA micro-updates |

## 💻 Open-Source GitHub Projects

*Sorted descending by GitHub star count. Star badges link directly to each project's stargazers page.*

| Project | Stars | Category / Scope | Description |
| :--- | :---: | :--- | :--- |
| **[OpenWrt](https://github.com/openwrt/openwrt)** | [![Stars](https://img.shields.io/github/stars/openwrt/openwrt?style=social&color=white)](https://github.com/openwrt/openwrt/stargazers) | Linux Router / Gateway OS | Extensible Linux distribution targeting embedded network devices and single-board computers with an efficient package manager (`opkg`) and web interface. |
| **[Raspberry Pi Linux Kernel](https://github.com/raspberrypi/linux)** | [![Stars](https://img.shields.io/github/stars/raspberrypi/linux?style=social&color=white)](https://github.com/raspberrypi/linux/stargazers) | Kernel Source / Drivers | The official Linux kernel source tree maintained by the Raspberry Pi Foundation, supporting all Raspberry Pi SBC models, Broadcom SoCs, and Device Trees. |
| **[Klipper](https://github.com/Klipper3d/klipper)** | [![Stars](https://img.shields.io/github/stars/Klipper3d/klipper?style=social&color=white)](https://github.com/Klipper3d/klipper/stargazers) | 3D Printer Embedded Control | High-performance 3D-printer firmware that offloads intensive kinematic computations and motion planning onto an embedded Linux SBC (Raspberry Pi/Allwinner). |
| **[Home Assistant Operating System](https://github.com/home-assistant/operating-system)** | [![Stars](https://img.shields.io/github/stars/home-assistant/operating-system?style=social&color=white)](https://github.com/home-assistant/operating-system/stargazers) | Appliance Linux OS / Buildroot | Purpose-built, minimal embedded Linux OS based on Buildroot and systemd-journald optimized for running Home Assistant Supervised on Raspberry Pi, ODROID, and x86 SBCs. |
| **[DietPi](https://github.com/MichaIng/DietPi)** | [![Stars](https://img.shields.io/github/stars/MichaIng/DietPi?style=social&color=white)](https://github.com/MichaIng/DietPi/stargazers) | Lightweight SBC OS / Debian | Extremely lightweight Debian-based operating system finely tuned and optimized to extract maximum performance and minimal RAM usage from 50+ single-board computers. |
| **[Armbian](https://github.com/armbian/build)** | [![Stars](https://img.shields.io/github/stars/armbian/build?style=social&color=white)](https://github.com/armbian/build/stargazers) | Universal ARM SBC OS & Build System | Linux distribution framework providing optimized Debian/Ubuntu kernel builds, device tree overlays, and rootfs images for hundreds of ARM and RISC-V SBC boards. |
| **[U-Boot ("Das U-Boot")](https://github.com/u-boot/u-boot)** | [![Stars](https://img.shields.io/github/stars/u-boot/u-boot?style=social&color=white)](https://github.com/u-boot/u-boot/stargazers) | Universal Bootloader | The ubiquitous universal bootloader for embedded systems and SBCs, initializing DDR, storage, network devices, and booting Linux kernel images across ARM, RISC-V, MIPS, and x86. |
| **[Buildroot](https://github.com/buildroot/buildroot)** | [![Stars](https://img.shields.io/github/stars/buildroot/buildroot?style=social&color=white)](https://github.com/buildroot/buildroot/stargazers) | Embedded Linux Build Framework | Fast, straightforward Makefile-based build system that compiles cross-compilation toolchains, bootloaders, kernels, and root filesystems in minutes for resource-constrained hardware. |
| **[Raspberry Pi Imager](https://github.com/raspberrypi/rpi-imager)** | [![Stars](https://img.shields.io/github/stars/raspberrypi/rpi-imager?style=social&color=white)](https://github.com/raspberrypi/rpi-imager/stargazers) | SBC Imaging & Provisioning Tool | Graphical utility to download, customize (Wi-Fi, SSH keys, user creation), and flash embedded Linux OS images directly onto SD cards and USB NVMe drives. |
| **[SWUpdate](https://github.com/sbabic/swupdate)** | [![Stars](https://img.shields.io/github/stars/sbabic/swupdate?style=social&color=white)](https://github.com/sbabic/swupdate/stargazers) | Dual-Copy A/B OTA Update Engine | Flexible software update framework for embedded Linux devices supporting dual-copy A/B partitions, encrypted image verification, streaming updates, and delta patching. |
| **[Sony Flutter Embedded Linux (eLinux)](https://github.com/sony/flutter-embedded-linux)** | [![Stars](https://img.shields.io/github/stars/sony/flutter-embedded-linux?style=social&color=white)](https://github.com/sony/flutter-embedded-linux/stargazers) | Embedded GUI & UI Framework | High-performance Flutter embedded runtime and Wayland/DRM display backend developed by Sony for running Flutter apps smoothly on embedded Linux SBCs. |
| **[RAUC](https://github.com/rauc/rauc)** | [![Stars](https://img.shields.io/github/stars/rauc/rauc?style=social&color=white)](https://github.com/rauc/rauc/stargazers) | Robust OTA Rootfs Updater | Lightweight C-based update client ensuring fail-safe A/B root filesystem updates on embedded Linux SBCs with cryptographic X.509 signature validation and hardware watchdog integration. |
| **[Mender Client](https://github.com/mendersoftware/mender)** | [![Stars](https://img.shields.io/github/stars/mendersoftware/mender?style=social&color=white)](https://github.com/mendersoftware/mender/stargazers) | Dual A/B Rootfs OTA Agent | Open-source client daemon for over-the-air software updates supporting atomic dual-rootfs rollbacks, delta payloads, and remote management on Yocto/Debian SBCs. |
| **[meta-balena](https://github.com/balena-os/meta-balena)** | [![Stars](https://img.shields.io/github/stars/balena-os/meta-balena?style=social&color=white)](https://github.com/balena-os/meta-balena/stargazers) | Yocto OS Layer for Containers | Collection of Yocto Project layers used to build balenaOS—a lightweight, container-optimized host OS engineered for running Docker containers reliably on edge SBCs. |
| **[Bootlin Embedded Linux Training](https://github.com/bootlin/training-materials)** | [![Stars](https://img.shields.io/github/stars/bootlin/training-materials?style=social&color=white)](https://github.com/bootlin/training-materials/stargazers) | Engineering Courseware & Labs | Comprehensive open-source training courseware, lab notebooks, and reference materials for embedded Linux, kernel driver development, Yocto, and Buildroot on SBC hardware. |
| **[BeagleBoard Linux Kernel](https://github.com/beagleboard/linux)** | [![Stars](https://img.shields.io/github/stars/beagleboard/linux?style=social&color=white)](https://github.com/beagleboard/linux/stargazers) | Hardware BSP & Kernel | Official kernel source tree and PRU (Programmable Real-Time Unit) drivers for BeagleBone Black, BeagleBone AI-64, BeagleV RISC-V, and TI Sitara AM335x SBCs. |
| **[The Yocto Project (Poky Reference)](https://github.com/yoctoproject/poky)** | [![Stars](https://img.shields.io/github/stars/yoctoproject/poky?style=social&color=white)](https://github.com/yoctoproject/poky/stargazers) | Industrial Linux Distro Builder | The official reference distribution and build environment of the Yocto Project (BitBake + metadata), enabling industrial teams to engineer reproducible, tailored embedded Linux distributions. |
| **[OpenEmbedded-Core](https://github.com/openembedded/openembedded-core)** | [![Stars](https://img.shields.io/github/stars/openembedded/openembedded-core?style=social&color=white)](https://github.com/openembedded/openembedded-core/stargazers) | Core Metadata & Recipe Base | The foundational core layer (`meta`) containing common BitBake recipes, architecture definitions, and toolchain configurations shared across all Yocto-compatible boards. |

## 🛠️ How to Contribute

We welcome additions, corrections, and improvements from the embedded systems and hardware communities!

1. **Fork the repository** to your GitHub account.
2. **Add or update an entry** adhering to these criteria:
   - **SaaS Products**: Add to the SaaS table with exact starting pricing tier, specific free tier limits (or trial terms), and parent company valuation/revenue scale.
   - **Open-Source Projects**: Must be an actively maintained, publicly accessible repository with an embedded Linux or SBC focus. Include the `shields.io` star badge pointing directly to the `/stargazers` URL and maintain descending star order.
3. **Commit your changes**:
   ```bash
   git checkout -b add-entry-name
   git commit -m "Add Entry Name to embedded Linux SBC list"
   ```
4. **Submit a Pull Request** with a concise description of why the tool is valuable for embedded Linux / single-board computer practitioners.

## ⚠️ Disclaimer

- All trademarks, logos, and product names are the property of their respective owners.
- Pricing, subscription tiers, free plan quotas, and feature sets are subject to vendor updates. Always check official provider websites for the most current terms.
- Market valuations and revenue estimates are compiled from reputable financial disclosures, investor releases, and market intelligence reports.

## 💖 Support & Thank You

If this curated reference saves you time building custom embedded Linux distros, provisioning SBC hardware, or managing edge fleets:
- ⭐ **Star this repository** to help other engineers discover it.
- 🔀 **Fork and contribute** your favorite embedded tooling and recipes.
- 📢 **Share** with colleagues across hardware, IoT, and embedded firmware communities.
