# Installing Node.js on Ubuntu VPS

Follow these steps to install Node.js on your Ubuntu VPS:

## 1. Update System Packages

Before installing Node.js, update your system's package index and upgrade existing packages.

```bash
sudo apt-get update
sudo apt-get upgrade
```

## 2. Add NodeSource Repository

To get the latest version of Node.js, you need to add the NodeSource repository.
Install curl (if not already installed)
```
sudo apt-get install curl
```
Download and Add NodeSource Repository

For Node.js version 18.x (LTS):
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
