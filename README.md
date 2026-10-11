# Smart Zone Vehicle Speed Control (IoT)

An IoT-based intelligent vehicle speed control system that automatically regulates vehicle speed in designated zones using **ESP8266** and **RFID** technology.

---

## Project Overview

This system detects when a vehicle enters a restricted or speed-controlled zone (school zone, hospital zone, etc.) using RFID and automatically limits the maximum speed of the vehicle. It demonstrates practical application of IoT in road safety and smart transportation.

---

## Key Features

- Automatic zone detection using RFID tags
- Real-time speed control of the vehicle
- Wireless communication via ESP8266 (Wi-Fi)
- Suitable for school zones, hospital areas, accident-prone zones, etc.
- Low-cost and scalable design

---

## Hardware Components

| Component              | Purpose                          |
|------------------------|----------------------------------|
| ESP8266 (NodeMCU)      | Main microcontroller + Wi-Fi     |
| RFID Reader + Tags     | Zone identification              |
| Motor Driver (L298N)   | Control vehicle motors           |
| DC Motors              | Vehicle movement                 |
| Power Supply           | System power                     |

---

## How It Works

1. RFID tags are placed at the entry of restricted zones.
2. When the vehicle approaches, the RFID reader detects the tag.
3. ESP8266 identifies the zone and applies the corresponding speed limit.
4. Motor driver reduces or maintains the speed accordingly.
5. When the vehicle exits the zone, normal speed is restored.

---

## Skills Demonstrated

- IoT System Design
- Embedded Programming (ESP8266 / Arduino)
- RFID Technology
- Motor Control
- Real-time Decision Making
- Wireless Communication

---

## Future Enhancements

- Cloud dashboard for monitoring vehicles in zones
- GPS integration for location tracking
- Mobile app alerts for drivers / authorities
- Multiple speed limit profiles per zone type

---

## Author

**Vinay Adabala**  
GitHub: [vinayadabala05](https://github.com/vinayadabala05)  
LinkedIn: [vinay-adabala05](https://www.linkedin.com/in/vinay-adabala05/)

---

## License

This project is open source and available under the MIT License.
