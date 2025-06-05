---
title: Linking the Orb CLI to an Account
shortTitle: Linking Orb CLI
metaDescription: Step-by-step guide for linking the Orb CLI to your Orb Account
section: Installing & Using Orb CLI
---

# Linking the Orb CLI to Your Account

This guide will walk you through the process of linking the Orb CLI to your Orb account. This is necessary to access all features of the Orb CLI, including sensor management and data retrieval.

## Prerequisites
- Ensure you have created an Orb account and have the app installed on at least one device on the local network.

## Automatic Discovery (Recommended)

If your new Orb sensor is on the same local network as a device already signed in to your Orb account:

1. Start the app and wait for the automatic discovery process
2. On your already-linked device, you'll receive a notification about the new sensor
3. Tap "Link to my account" to connect the sensor

<img src="../../images/orb-app/auto-discovery-link.png" alt="Auto Link" width=60% style="margin-left: 2em;">

## Manual Linking of Orb CLI Sensor

If the newly started Orb sensor is not automatically discovered, you can link it manually using the command line interface:

1. Open a terminal on the device
2. Run the `orb link` command
  Note: this command needs to be run as the same user that runs the Orb Sensor.
  You could use `su` to switch to that user before running the command, or you can use  `sudo` to run the command as that user directly. 
  On most systems (Debian, Redhat, Alpine), this is typically the `orb` user. For OpenWRT variants, it is typically the `root` user.
 
  For example, if you are using Debian or Redhat, you can run:
  ```bash
  sudo -u orb orb link
  ```
3. The output of that command will include a short URL to link to your account
4. Copy that URL into a browser on any machine, and login to your account at the prompt
5. That Orb will now show up in any app where you’re logged in

## Troubleshooting
If you encounter issues during the linking process, consider the following:
- Ensure that the Orb sensor is connected to the same network as your device running the Orb CLI.
- Verify that your Orb account is active and accessible.