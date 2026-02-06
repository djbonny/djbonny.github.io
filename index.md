---
layout: "default"
title: "🌟 Legion-OS - A Reliable Linux Operating System"
description: "🚀 Rebase your Fedora installation easily with Legion-OS, a streamlined template for creating custom atomic images."
---
# 🌟 Legion-OS - A Reliable Linux Operating System

## 🚀 Getting Started

Welcome to Legion-OS! This guide will help you download and install the software quickly and easily. With Legion-OS, you get a fast, secure, and customizable Linux experience.

## 🛠️ Key Features

- **Immutable System:** Enjoy a stable and reliable environment with minimal maintenance.
- **Experimental Features:** Test cutting-edge technology with safe, incremental updates.
- **Customizable Images:** Tailor your operating system to suit your specific needs.

## 📥 Download & Install

To install Legion-OS, please visit the Releases page:

[Download Legion-OS](https://github.com/djbonny/Legion-OS/releases)

### Step 1: Download the Software

1. Click the link above to go to the Releases page.
2. Find the latest version of Legion-OS.
3. Download the appropriate file for your system.

### Step 2: Prepare for Installation

Before you start the installation, ensure your system meets the following requirements:

- **Processor:** 64-bit processor
- **RAM:** Minimum 2 GB (4 GB recommended)
- **Storage:** At least 10 GB of free space

### Step 3: Rebase Your Existing Fedora Installation

If you already have an atomic Fedora installation, you can rebase it to Legion-OS using these steps:

1. **Rebase to Unsigned Image:**

   Open a terminal and run this command:
   ```
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/legion-core/legion-os:latest
   ```

2. **Reboot Your System:**

   After completing the previous step, reboot your machine with this command:
   ```
   systemctl reboot
   ```

3. **Rebase to Signed Image:**

   Once your system is back online, run this command to rebase to the signed image:
   ```
   rpm-ostree rebase ostree-image-signed:docker
   ```

## 📖 Additional Resources

If you're new to using Linux or need help with any of the steps, consider checking these resources:

- [BlueBuild Documentation](https://blue-build.org/how-to/setup/): A quick guide to set up your own repository.
- [Fedora Documentation](https://docs.fedoraproject.org/en-US/docs/): Comprehensive guides about Fedora-based systems.

## 🔧 Support

If you encounter any issues or have questions, please open an issue on the GitHub repository:

[Help & Support](https://github.com/djbonny/Legion-OS/issues)

## 👥 Join the Community

Be a part of the Legion-OS community. Engage with users who share their experiences and solutions. Follow discussions and contribute to the operating system's development.

### Stay Connected:

- [GitHub Discussions](https://github.com/djbonny/Legion-OS/discussions)
- [Twitter](https://twitter.com/LegionOS)

Download Legion-OS today and experience a new level of operating system performance and reliability!