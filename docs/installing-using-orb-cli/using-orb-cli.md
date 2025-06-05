---
title: Using Orb CLI
shortTitle: Using CLI
metaDescription: Step-by-step guide for using the Orb CLI.
section: Installing & Using Orb CLI
---

# Using the Orb CLI

This guide will walk you through the process of installing the Orb app on your Windows PC.

## Orb CLI Commands 
The Orb CLI provides a set of commands to manage your Orb sensors and interact with your Orb account. Below are some common commands you can use:
  orb [command]
Available Commands:
  sensor      Run the Orb sensor
  listen      Connect to a running Orb service
  link        Link this Orb to an account
  version     Current version of Orb
  summary     Show the latest summary for this Orb
  help        This screen
Flags:
  -h, --help     help for example
  -r  --remote   connect to remote host

## Uninstalling Orb CLI
To uninstall the Orb CLI, you can use the following command in your terminal:
```bash
orb uninstall
```
This will remove the Orb CLI from your system.

## Updating Orb CLI
To update the Orb CLI to the latest version, you can use the following command:
```bash
orb update
```
This will check for updates and install the latest version of the Orb CLI.

## Auto-Starting the Orb CLI Service

### At Boot
To start the Orb CLI service at boot, you can use the following command:
```bash
orb start --boot
```
This will ensure that the Orb CLI service starts automatically when your system boots up.

### At login
To start the Orb CLI service at login, you can use the following command:
```bash
orb start --login
```
This will ensure that the Orb CLI service starts automatically when you log in to your system.
