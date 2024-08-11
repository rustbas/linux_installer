# Linux installer

Simple install script with following features:
1. BIOS install (maybe UEFI later)
2. `8GB` swap
3. Encrypted root dir

# Install checklist

1. Internet.
2. `fdisk`.
3. `cryptsetup`.
4. Locale, timezone, hostname and hosts.
5. Grub and UUIDs.

# Installation Guide

1. Connect to Internet
2. Run 
    ```bash
    curl -LO https://raw.githubusercontent.com/rustbas/arch_installer/master/install_sys.sh
    ```
3. Run 
    ```bash
    bash install_sys.sh
    ```

# TODO
