# lobox
a emulator that let's you run windows programs 64 or 32 bit on your Android phone for more information please check the README.md file

---

# Lobox

Lobox is a lightweight emulator designed to run Windows applications on Android devices. By leveraging Wine and Box64 in conjunction with Termux and Termux X11, Lobox allows you to run both 32-bit and 64-bit Windows applications seamlessly on ARM-based Android devices.

## Features

- Run 32-bit and 64-bit Windows applications on Android
- Uses Wine WoW64 in combination with Box64 for improved compatibility
- Optimized for ARM-based devices
- Integrates with Termux and Termux X11 for an efficient and smooth experience

## Prerequisites

Before installing Lobox, make sure you have the following prerequisites:

- A device running Android 7.0 (Nougat) or higher
- Termux installed from F-Droid
- Termux X11 installed (for GUI applications)
- Sufficient storage space for Wine, Box64, and Windows applications

## Installation

To install Lobox on your Android device, follow these simple steps:

1. Open Termux and run the following command to update your package list and install `wget` and the `x11-repo`:

   ```bash
   pkg update && pkg upgrade && pkg install wget x11-repo
   ```

2. Download and run the Lobox installation script:

   ```bash
   wget https://github.com/capt-dev/lobox/releases/download/v1.0.0/install.sh && bash install.sh
   ```

This script will automatically download and set up everything needed to run Lobox on your device.

## Usage

Once Lobox is installed, you can start running Windows applications through the Wine interface. For GUI applications, ensure that Termux X11 is installed and running to display the Windows application interface.

## Troubleshooting

If you encounter any issues during installation or usage, consider the following tips:

- Ensure all prerequisites are met, including Termux X11.
- Verify that your device has enough storage space and processing power.
- Check for any errors during the installation process and re-run the installation script if necessary.
- Refer to the [Wine](https://www.winehq.org/) and [Box64](https://github.com/ptitSeb/box64) documentation for additional support.
## additional notes
it is recommended to install `xserver xsdl` because it is required for the audio to work you just have to go into app and wait 5 to ,6 don't change any settings because we will not be using this for display,now don't close it just put it in your recent's and now just run lobox as normal the sound will only work if `xserver xsdl` is in recent's and you did not change any settings and just waited  5 to 6 to 8 seconds.it can be installed from [here](https://xserver-xsdl.en.uptodown.com/android/download)
also installing inputbridge is possible just make a installer like in /sdcard/installer using the app and navigate to it in wine using cmd and then just run install.bat and after that ib.exe you will need to run this exe file every time you want input bridge control here is a video for better explanation
[here](https://youtu.be/8PIvorq1OwU?si=EHM41j6hgzZrvZ7y)
another one for even better explanation if you have not understood anything from the previous one
[here](https://feji.us/lmzqf8)
also in your termux-x11 config make sure that the screen size is 800x600
## Contributing

Contributions are welcome! If you'd like to contribute to Lobox, please fork the repository and submit a pull request.

## License

Lobox is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Wine](https://www.winehq.org/)
- [Box64](https://github.com/ptitSeb/box64)
- [Termux](https://termux.com/)
- [Termux X11](https://github.com/termux/termux-x11)
- [unknown](https://feji.us/lmzqf8)

---
