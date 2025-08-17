🪄 MagiQuest Wand Home Automation Trigger
Turn magical moments into smart home actions!

📖 Overview
This project lets kids continue the magic of their visit to Great Wolf Lodge by using their MagiQuest wand (an IR transmitter) to trigger smart home devices. Using an ESP32-C3 microcontroller and ESPHome, the wand's IR signal is captured and used to toggle a smart socket via Home Assistant.

🧠 How It Works
The wand sends IR signals.
An ESP32-C3 board listens for IR signals via a connected IR receiver.
When a signal is received (with a cooldown to prevent rapid toggling), a script is triggered.
The script calls a Home Assistant service to toggle a smart socket.
🛠️ Hardware
ESP32-C3 DevKitM-1
IR Receiver (connected to GPIO5)
MagiQuest Wand (IR transmitter)
Smart Socket (configured in Home Assistant)
