# XMMS 1.2 Flatpak Packaging

This project provides a Flatpak package for XMMS 1.2, an older MP3 player for Linux. Please note that this application is quite old, and it is highly recommended to use more modern and actively maintained music players due to potential security issues.

## Why is it not on Flathub?

We do not publish this application on Flathub for age and security reasons, XMMS 1.2's last release was in 2007 and has not received updates ever since. Using outdated unmaintained software can pose security risks even if confined by the Flatpak sandbox.

## Preserving a Piece of History

The intent with this project is to preserve a working version of XMMS 1.2, allowing users to experience a slice of a past Unix era in a modern Linux system. XMMS was a beloved music player during its time, and by packaging it as a Flatpak, we aim to keep its memory alive in the Linux ecosystem.

![XMMS 1.2 Screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/XMMS_%281%29.png/350px-XMMS_%281%29.png)

## Building and Running the Flatpak

To build and run the XMMS 1.2 Flatpak from the command line, follow these steps:

```shell
 git clone https://github.com/aruiz/xmms-flatpak.git                         # 1. Clone this repo
 cd xmms-flatpak                                                             # 2. Enter repo directory
 flatpak-builder --user --install --force-clean build-dir org.xmms.XMMS.json # 3. Build and installthe Flatpak application
 flatpak run org.xmms.XMMS                                                   # 4. Run XMMS 1.2
```

Please note that the build process might require additional dependencies and setup. Refer to the [Flatpak documentation](https://flatpak.org/documentation.html) for more detailed information on building and running Flatpak applications.

## Disclaimer

Using XMMS 1.2 or any outdated software may expose your system to security risks. We strongly recommend using modern and actively maintained alternatives for a better and more secure user experience.

**Use this Flatpak at your own risk.**
