# CryptoniXubuntu
Lock. Encrypt. CryptoniXubuntu.

# What?
This is a custom Xubuntu image with cryptographic utilities in mind.

Supposed to be used offline, airgapped, this distro disposes of GPG, PGP, KeePassXC, and VeraCrypt.

This image also disposes of the walletgenerator.net repository for airgapped Crypto wallet generation.

# How to use?
If you're on Linux (and you should), you can use Popsicle or other utilities to make a bootable flash drive.

  - Download: [ISO](https://drive.google.com/file/d/166SKabec8efgMazuyOwIyEiRcs6jkRs9/view?usp=sharing) - [MD5 Check](https://drive.google.com/file/d/1TBulCD54cQgiYfoVwXcW6-VnIJiWbAVz/view?usp=sharing)
  - Make a bootable drive
  - Disconnect any network from your computer
  - Boot
  - Generate / Encrypt / Decrypt
  - You're good to go.

If you're dependent on Windows, you can use Universal USB Installer or YUMI to generate a bootable USB drive.

https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/
https://www.pendrivelinux.com/yumi-multiboot-usb-creator/

# How was this created?
This image was created using CUBIC, a linux distro customizer.
The official PPA for KeePassXC was added:
https://keepassxc.org/blog/2017-10-25-ubuntu-ppa/

The Xubuntu community security ppa was added for VeraCrypt:
https://linuxhint.com/install-use-veracrypt-ubuntu-22-04/

The latest master of the walletgenerator.net was added to the desktop.

No other changes.
