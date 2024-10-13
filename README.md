# picologger

# Description:
In this project, a Raspberry Pi Pico is converted into a Rubber Ducky-style USB device that functions as a keylogger. Using Ducky Script, the device executes pre-defined keystroke commands, simulating keyboard input to gather and log data in real-time. This setup demonstrates the Raspberry Pi Pico's potential as a compact, programmable HID (Human Interface Device), highlighting security concerns in USB devices while showcasing offensive cybersecurity techniques and the impact of HID-based attacks.



![WhatsApp Image 2024-10-14 at 00 13 07_c0c9a114](https://github.com/user-attachments/assets/0809ee1f-fd9a-44cf-8b82-7dd945400d82)


# Features
1. Keystroke Injection: Executes sequences of commands using Ducky Script to simulate rapid typing.
2. Data Logging: Captures and stores keystrokes for analysis.
3. Lightweight and Portable: The Pico is small and can operate independently as a USB device.
4. Customizable Payloads: Modify Ducky Script to execute various commands for different test cases.


# Prerequisites
1. Raspberry Pi Pico
2. Micro-USB cable
3. CircuitPython installed on the Raspberry Pi Pico
4. Ducky Script knowledge
5. Python 3.x for additional scripting needs

# Installation
Install CircuitPython on Raspberry Pi Pico

1. Download the CircuitPython .uf2 file for the Pico from the official website.
   . Connect the Pico to your computer while holding down the BOOTSEL button.
   . Drag and drop the CircuitPython .uf2 file onto the Pico.
3. Upload Scripts and Libraries
   . Copy necessary Python libraries and the Ducky Script interpreter file to the Pico's storage.

4.  Edit Ducky Script Payloads
   . Write and modify your payloads using Ducky Script syntax and save them to the Pico.

# Usage
1. Connect the Pico to any USB-enabled device.
2. The Pico will automatically start executing the keystroke commands based on the loaded Ducky Script.
3, Data will be captured and logged as specified in the payload script.
4. Change the <REMOTE_IP> <REMOTE_PORT> with the attacker's ip and port.
5. use a listener like netcat.


# Applications and Ethical Use
. Security Testing: Use this device to demonstrate potential vulnerabilities in USB interfaces and raise awareness about physical access security.


# Educational Purposes:
Experiment with keystroke injection for training and research in cybersecurity.
⚠️ Disclaimer: This project is intended for educational and authorized testing purposes only. Unauthorized use of keylogging or USB injection is illegal and unethical.

# Resources
1. https://circuitpython.org/
2. https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript
