# SubGHz

<img width="1536" height="864" alt="lora_hardware_blueprint" src="https://github.com/user-attachments/assets/42fbd375-ed9f-4830-8b6a-24c4737156e4" />


A project for my own Real - timing chatting Infrastructure And it's P2P !
This project is a way to send text messages without using the internet, Wi-Fi, or phone signals. It uses two handheld devices that talk directly to each other using radio waves.

✨ Main Features
No Internet Needed: You don't need a router or a cell tower. The devices connect to each other.

Easy Setup: The devices find each other automatically. You will see a "Searching..." message until they connect.

Simple Screen: A small screen shows your messages and if you are connected.

Mini Keyboard: It has a small keyboard so you can type just like on a phone.

🛠️ The Hardware (Parts List)
To build this, you need:

ESP32: The "brain" of the device.

LoRa Radio: The part that sends and receives signals over long distances.

CardKB: A tiny keyboard for typing.

LCD Screen: A 4-line screen to read your chat.

🚀 How do you use it?
Turn it on: The device looks for a partner. When it finds one, it says "Connected!"

Type a message: Use the keyboard to write a short note (up to 15 letters).

Send: Press Enter.

Wait: You must wait about 10 seconds before sending another message. This keeps the connection stable.

# The Current Components : (I Bought None Of them)
2x ESP32 Development Boards

2x Lora SX1278 Modules

2x LCD 2004 with I2C Backpack

2x M5Stack CardKB

2x 18650 Battery Shields + 2x 18650 Lithium Batteries

# For Wiring and Prototyping : 

2x Breadboards (400 tie-points)

4x 4.7kΩ Resistors

Jumper Wires (Dupont Cables): * Male-to-Female + * Male-to-Male

