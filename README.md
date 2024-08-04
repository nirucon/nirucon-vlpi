# Nirucon-VLPI: Post-Installation script for Void Linux

## Overview
Nirucon-VLPI is a post-installation script designed for Void Linux. It automates the installation of essential and optional packages, as well as configuration files for a Suckless environment, including tools like `dwm`, `st`, `dmenu`, and more.

## Features
- Adds non-free repository.
- Installs core dependencies and essential packages for a minimal Xorg setup.
- Clones and installs [nirucon-suckless](https://github.com/nirucon/nirucon-suckless) configuration, including `dwm`, `st`, `dmenu`, and `slock`.
- Offers optional packages for installation, such as Firefox, Thunderbird, GIMP, and more.
- Installs custom Rofi and CMUS themes.

## Disclaimer and Warning
1. **No Responsibility**: Use this script at your own risk. The author does not take any responsibility for any changes or issues caused by this script.
2. **Not a Professional**: The author is not a professional programmer, hacker, or tech expert. This script is created by a Linux enthusiast (noob).
3. **Work in Progress**: Consider this script a work in progress but there is no guarantee of future updates or improvements.

## Dependencies
- Ensure you have an active internet connection.
- Additional dependencies are listed within the script.

## Related Scripts
- Main Post-Installation Script: [nirucon-linux-postinstall](https://github.com/nirucon/nirucon-linux-postinstall)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/nirucon/nirucon-vlpi
    cd nirucon-vlpi
    ```
2. Make the script executable:
    ```bash
    chmod +x nirucon-vlpi.sh
    ```
3. Run the script:
    ```bash
    ./nirucon-vlpi.sh
    ```

## Usage
The script will guide you through the following steps:
1. Checking for an internet connection.
2. Displaying a welcome message and disclaimer.
3. Confirming your intention to proceed.
4. Adding the non-free repository.
5. Installing core dependencies and essential packages.
6. Cloning and installing Suckless tools and configurations.
7. Installing optional packages based on your selection.
8. Installing custom Rofi and CMUS themes.
9. Prompting for a system reboot.

## Donations
Feel free to use and modify this script. Donations are welcome and appreciated: [PayPal](https://www.paypal.com/paypalme/nicklasrudolfsson)

## Contact
- **Author**: Nicklas Rudolfsson
- **GitHub**: [nirucon](https://github.com/nirucon)
- **Email**: [n@rudolfsson.net](mailto:n@rudolfsson.net)

---
This readme file provides a concise overview of the script's functionality, installation, usage, and disclaimers. For detailed script content, refer to the script file itself.
