# XMMS 1.2 Flatpak Packaging

This project provides a Flatpak package for XMMS 1.2, an older MP3 player for Linux. Please note that this application is quite old, and it is highly recommended to use more modern and actively maintained music players due to potential security issues.

## XMMS 1.2 Information

- **Last Release:** XMMS 1.2 was last released on [Date of Last Release] (Please replace with the actual release date if available).

## Why is it not on Flathub?

We do not publish this application on Flathub for age and security reasons, XMMS 1.2 is an outdated application that has not received updates for a significant period of time. Using outdated unmaintained software can pose security risks even if somewhat confined by the Flatpak sandbox.

## Preserving a Piece of History

The intention of this project is to preserve a reproducible version of XMMS 1.2, allowing users to experience a slice of a past Unix era. XMMS was a beloved music player during its time, and by packaging it as a Flatpak, we aim to keep its memory alive in the Linux ecosystem.

![XMMS 1.2 Screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/XMMS_%281%29.png/350px-XMMS_%281%29.png)

## Building and Running the Flatpak

To build and run the XMMS 1.2 Flatpak from the command line, follow these steps:

```shell
 git clone [repository_url]                                 # 1. Clone this repository
 cd [repository_directory]                                  # 2. Navigate to the repository directory
 flatpak-builder build-dir org.xmms.XMMS.json --force-clean # 3. Build the Flatpak application
 flatpak --user install build-dir/org.xmms.XMMS.flatpak     # 4. Install the built Flatpak
 flatpak run org.xmms.XMMS                                  # 5. Run XMMS 1.2
```

Please note that the build process might require additional dependencies and setup. Refer to the [Flatpak documentation](https://flatpak.org/documentation.html) for more detailed information on building and running Flatpak applications.

## Disclaimer

Using XMMS 1.2 or any outdated software may expose your system to security risks. We strongly recommend using modern and actively maintained alternatives for a better and more secure user experience.

**Use this Flatpak at your own risk.**
