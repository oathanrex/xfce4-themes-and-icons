# Customizing XFCE4 Kali Theme and Icons for Termux GUI

This guide will walk you through the process of customizing the XFCE4 Kali theme and icons for Termux GUI, specifically using Kali-Dark, Kali-Light, Kali-Dark-xHiDPI, Kali-Light-xHiDPI, Flat-Remix-Blue-Dark, Flat-Remix-Blue-Light, Flat-Remix-Purple-Dark, and Flat-Remix-Purple-Light variants. These instructions assume you have Termux installed with XFCE4 and Whisker Menu.

## Prerequisites

- Termux installed on your device
- XFCE4 and Whisker Menu installed in Termux (`pkg install xfce xfce4-whiskermenu-plugin -y`)
- Access to Termux's filesystem

## Instructions

### 1. Installing Themes and Icons

- Download the Themes: Kali-Dark, Kali-Light, Kali-Dark-xHiDPI, Kali-Light-xHiDPI.
- Download the Icons Pack: Flat-Remix-Blue-Dark, Flat-Remix-Blue-Light, Flat-Remix-Purple-Dark, Flat-Remix-Purple-Light.
- Copy the theme files to `/usr/share/themes/` directory in Termux. You can use a file manager or the command line for this.
- Copy the icon files to `/usr/share/icons/` directory in Termux.

### 2. Customizing XFCE4 Settings

- Launch XFCE4 in Termux.
- Right-click on the desktop and select "Settings Manager."
- In the Settings Manager, navigate to "Appearance" and choose your desired theme from the list.
- Similarly, navigate to "Icons" and select your preferred icon pack.
- Adjust other settings such as fonts, mouse cursor, etc., according to your preferences.
- Replace Application Menu with Whisker Menu from Panel-1 settings item section.
- You can add more Xfce4 packages by typing `pkg list-all` you can see some packages that can help you to make look better.

### 3. Adjusting Resolution

- If you encounter resolution issues on your device (720p or 1080p), you may need to adjust the display settings within XFCE4.
- To change the resolution, navigate to the display settings in XFCE4 and select an appropriate resolution that fits your device's screen.

## Additional Notes

- Make sure to restart XFCE4 after applying theme and icon changes to see the effects.
- Feel free to experiment with different themes and icons to find the combination that suits your preferences best.

- If you find this project useful, consider supporting its development by [buying me a coffee](http://www.buymeacoffee.com/oathanrex).
- Full Icons and themes uploaded [here](https://www.pling.com/p/2147305/). and for all themes you can visit [here](https://github.com/oathanrex/flat-remix/).
