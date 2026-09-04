# Xiaomi Poco X3 NFC (surya) Custom Kernel

This repository contains the custom kernel source code and releases for the Xiaomi Poco X3 NFC (device codename: surya). 

## Kernel Variants

This project provides two distinct kernel variants built from different base sources to accommodate various ROM requirements:

* **SuperCreepy**
  * **Base:** LineageOS
  * **Description:** Built upon the standard LineageOS kernel tree.

* **SuperPotato**
  * **Base:** Rethinking
  * **Description:** Built upon the rethinking kernel tree.

## Flashing Instructions

1. Reboot the device into a custom recovery.
2. Flash the selected kernel `.zip` package (SuperCreepy or SuperPotato).
3. Reboot the system.

*Note: It is highly recommended to back up your current `boot` and `dtbo` partitions before flashing.*

## Credits and Acknowledgments

* [LineageOS Project](https://github.com/LineageOS) for the base source.
* [Cilok-LAB](https://github.com/Cilok-LAB) for the rethinking kernel base.
* All open-source contributors and testers.
