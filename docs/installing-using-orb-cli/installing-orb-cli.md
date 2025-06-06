---
title: Installing Orb CLI
shortTitle: Install Orb CLI
metaDescription: Step-by-step guide for installing the Orb CLI on macOS, Windows, FreeBSD, and Linux.
section: Installing & Using Orb CLI
---

# Installing Orb on macOS, Windows, FreeBSD, and Linux

This guide will walk you through the process of installing the Orb CLI on various platforms. Note, that if you have already installed the Orb app on your device, you can not run the Orb CLI and the Orb App at the same time.

## macOS CLI Installation

### Prerequisites
- Ensure you have Homebrew installed on your Mac. If not, you can install it by running the following command in your terminal:
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

### Step 1: Download the Orb CLI for macOS

1. On your Mac, download the [Orb CLI for macOS](https://pkgs.orb.net/earlyaccess/orb-osx-universal.zip)
2. Wait for the zip file to download completely
3. Once downloaded, locate the zip file in your Downloads folder
4. Double click the zip file to extract its contents

### Step 2: Open your Favorite Terminal Application

1. Open the Terminal app on your Mac
2. Install the Orb CLI by running the following command in your terminal:
```bash 
brew tap orbforge/orb
brew install orb
```
3. Wait for the installation to complete
4. Once the installation is complete, you can start the Orb service by running:
```bash
brew services start orb
```

## Windows CLI Installation

### Prerequisites
- Ensure you have a compatible version of Windows (Windows 10 or later)
- Make sure you have administrative privileges to install software

### Step 1: Download the Orb CLI for Windows

1. On your Windows machine, download the [Orb CLI for Windows](https://pkgs.orb.net/earlyaccess/orb-windows-amd64.zip)
2. Wait for the zip file to download completely
3. Once downloaded, locate the zip file in your Downloads folder
4. Double click the zip file to extract its contents

### Step 2: Open your Favorite Terminal Application

1. Open the Terminal app on your Windows machine (e.g., Command Prompt, PowerShell, or Windows Terminal)
2. To verify that the Orb CLI installed correctly, run the following command:
   ```bash
   orb version
   ```
3. If the command returns the version number, the installation was successful

## FreeBSD CLI Installation

### Prerequisites
- Ensure you have FreeBSD installed on your machine
- Make sure you have administrative privileges to install software

### Step 1: Download the Orb CLI for FreeBSD - This section needs work for after we have packaged FreeBSD
1. On your FreeBSD machine, download the [Orb CLI for FreeBSD AMD64](https://pkgs.orb.net/earlyaccess/orb-freebsd-amd64.zip) or [Orb CLI for FreeBSD ARM64](https://pkgs.orb.net/earlyaccess/orb-freebsd-arm64.zip)
1. Download the appropriate zip file based on your architecture:
   - For AMD64 architecture:
   ```bash orb-freebsd-amd64.zip
   ```
   or
   ```bash
   unzip orb-freebsd-arm64.zip
   ```
2. Wait for the zip file to download completely
3. Once downloaded, locate the zip file in your Downloads folder
4. Extract the contents of the zip file using the following command:
   ```bash
   unzip orb-freebsd-amd64.zip
   ```
   or
   ```bash
   unzip orb-freebsd-arm64.zip
   ```

### Step 2: Open your Favorite Terminal Application
1. Open the Terminal app on your FreeBSD machine
2. Install the Orb CLI by running the following command in your terminal:
   ```bash
   sudo orb install
   ```
3. Wait for the installation to complete  

## Linux CLI Installation

### Prerequisites
- Ensure you have a compatible version of Linux (Ubuntu, Debian, Fedora, etc.)
- Make sure you have administrative privileges to install software

### Step 1: Download the Orb CLI for Linux
1. Install Linux CLI with the following command:
   ```curl -fsSL https://pkgs.orb.net/install.sh | sh```
2. Wait for the script to download and execute
3. The script will automatically download the appropriate Orb CLI for your Linux distribution and install it
4. Once the installation is complete, you can verify it by running:
   ```bash
   orb version```
5. If you encounter any issues, you can refer to the [Orb Linux documentation](https://orb.net/docs/setup-sensor/linux) for more detailed installation instructions

## Troubleshooting

If you encounter any issues during the installation process, here are some common troubleshooting steps:
- **Check Permissions**: Ensure you have the necessary permissions to install software on your machine.
- **Network Issues**: Make sure you have a stable internet connection while downloading the Orb CLI.
- **Re-download**: If the download was interrupted or corrupted, try downloading the Orb CLI again.
- **Consult Documentation**: Refer to the [Orb documentation](https://orb.net/docs) for additional help and troubleshooting tips.
