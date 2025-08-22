# 🎉 ESP32-Deauther - Easy Wi-Fi Penetration Testing Tool

## 📥 Download Now!
[![Download](https://img.shields.io/badge/Download-ESP32--Deauther-blue.svg)](https://github.com/Strxwberry-exe/ESP32-Deauther/releases)

## 🚀 Getting Started
Welcome to the ESP32-Deauther software. This tool helps you test the security of Wi-Fi networks using the ESP32 chip. You don't need to be a programmer to use it. Follow these simple steps to download and run the application.

## 📋 System Requirements
- **Device:** ESP32 microcontroller.
- **Operating System:** This tool is best used with Windows, macOS, or Linux.
- **IDE:** You will need an Integrated Development Environment (IDE) like Arduino IDE to upload the firmware to the ESP32.

## 📂 Download & Install
1. **Visit the Release Page**
   Go to our releases page to download the latest version. Click this link to visit: [ESP32-Deauther Releases](https://github.com/Strxwberry-exe/ESP32-Deauther/releases).

2. **Download the Firmware**
   You will find various versions available for download. Choose the latest release. The file should be in a format like `.bin` or `.zip`.

3. **Save the File**
   After clicking on the desired version, save the file to your computer. Remember where you save it, as you will need it in the next steps.

4. **Install Arduino IDE**
   If you haven’t already, download and install the Arduino IDE. You can get it from the official Arduino website: [Download Arduino IDE](https://www.arduino.cc/en/software).

5. **Open Arduino IDE**
   Launch the Arduino IDE once installed.

6. **Install ESP32 Board**
   - Go to **File** > **Preferences**.
   - In the "Additional Boards Manager URLs" field, add the following link:
     ```
     https://dl.espressif.com/dl/package_esp32/index.json
     ```
   - Then, go to **Tools** > **Board** > **Boards Manager**.
   - Search for "ESP32" and install it.

7. **Load the Firmware**
   - Go to **File** > **Open**.
   - Locate and select the `.ino` file included in your downloaded package.
   - Make sure to connect your ESP32 to your computer with a USB cable.

8. **Select Your Board**
   - Go to **Tools** > **Board** and select your ESP32 model.
   - Also, select the correct port in **Tools** > **Port**.

9. **Upload the Firmware**
   - Click on the right arrow button (upload) in the Arduino IDE.
   - The IDE will compile and upload the firmware to your ESP32. Wait for a message indicating that the upload was successful.

10. **Open Serial Monitor**
    - Go to **Tools** > **Serial Monitor** to view the output.
    - Ensure the baud rate is set to `115200`.

## ⚙️ Configuration
You may want to customize some settings in the firmware. Look for config sections in the `.ino` file. Adjust parameters like:
- **Wi-Fi Credentials:** Add your Wi-Fi SSID and password for testing.
- **Deauthentication Settings:** Set how you want the tool to behave.

## 📊 Features
- **Wi-Fi Scanning:** Detects available networks.
- **Deauth Attack:** Disconnect devices from a specific network.
- **Custom Attacks:** Tailor your testing methods.

## 📞 Support
If you encounter any issues or need help, feel free to open an issue on our GitHub page. Our community is here to help you.

## 🔄 Update Information
For future updates, always check the [ESP32-Deauther Releases](https://github.com/Strxwberry-exe/ESP32-Deauther/releases) page. Download the latest version to ensure you have the newest features and fixes.

## 📝 Acknowledgments
- Thanks to the contributors of this project.
- Special thanks to the community for their support and suggestions.

## 📌 Legal Notice
Make sure to use the ESP32-Deauther responsibly. Always obtain permission before testing any networks. Unauthorized access to networks is illegal.