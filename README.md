# proot-distro-nethunter

## Description
The Proot-Distro NetHunter Installer is a Bash script that automates the integration of Kali NetHunter (official version) with the proot-distro tool. This script simplifies the setup and management of NetHunter distributions within a proot-based environment.

providing security professionals with an easy-to-use setup and management solution for NetHunter distributions.

[![GUI](https://sagar040.github.io/archives/data/proot-distro-nethunter/images/gui.gif)](https://sagar040.github.io/archives/data/proot-distro-nethunter/images/gui.gif)

# version 1.6

## Notes
- alias name `BackTrack-linux`
- login shortcut  `nethunter [user]`

## What's New

- Fixed some known issues
- Removed customize zsh prompt from the blank installation

## What is proot-distro?
<a href="https://github.com/termux/proot-distro/" style="text-decoration: none;color:royalblue;">PRoot Distro</a> is a powerful utility that allows you to run a full Linux distribution on an Android device without the need for root access. It uses proot, a userspace implementation of chroot, to create a lightweight virtualized environment where you can install and run various Linux distributions.


## Features

The script provides the following key features:

1. Automated integration of Kali NetHunter into proot-distro, eliminating manual configuration steps.
2. Calculation of the SHA256 checksum of the NetHunter rootfs to ensure data integrity during installation.
3. Facilitation of the installation process, providing a straightforward setup experience.
By using this script, users can benefit from:

1. Easy setup and management of Kali NetHunter distributions within a proot-based environment.
2. Swift installation process, reducing manual effort and saving time.


## Prerequisites

Android device with Termux installed

## Get latest version of Termux from f-droid

<a href="https://f-droid.org/en/packages/com.termux/">![download termux](https://f-droid.org/assets/fdroid-logo-text_S0MUfk_FsnAYL7n2MQye-34IoSNm6QM6xYjDnMqkufo=.svg)</a>


## Installation

Run the following command to install Git (if not already installed):

```bash
pkg install git
```

Clone the repository:
```bash
git clone https://github.com/sagar040/proot-distro-nethunter.git
```

Navigate to the project directory:
```bash
cd proot-distro-nethunter

```

## Usage

Install Kali Nethunter on proot-distro:
```bash
bash install-nethunter.sh --install
```

## Login to NetHunter

1. Run the following command to log in to the NetHunter environment:
    ```bash
    nethunter [user]
    ```
    or
    ```bash
    proot-distro login BackTrack-linux
    ```
## Accessing the NetHunter GUI

2. Once you are logged in, you can start the GUI session by running the following command:
    ```bash
    sudo kgui
    ```

It is important to remember that the NetHunter GUI is optional. If you prefer to use only the command-line interface, you can choose the "nethunter terminal" option.
