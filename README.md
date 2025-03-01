# PIR Motion Sensor LED Control with ESP32

This project demonstrates how to use a **PIR motion sensor** to control an **LED** with an ESP32. When motion is detected, the LED turns **ON**; otherwise, it remains **OFF**. The system also prints the motion detection status on the **Serial Monitor**.

## Features
- Uses a **PIR sensor** to detect motion.
- Controls an **LED** based on motion detection.
- Displays **motion status** on the **Serial Monitor**.
- Simple and efficient **digitalRead()** based implementation.

## Components Used
- **ESP32**
- **PIR Motion Sensor** (connected to GPIO 4)
- **LED** (connected to GPIO 2)

## Circuit Connections
| Component | ESP32 Pin |
|-----------|-----------|
| LED | GPIO 2 |
| PIR Sensor | GPIO 4 |

## Installation & Setup
### 1. Upload the Code
1. Open the **Arduino IDE**.
2. Copy and paste the provided code.
3. Connect the ESP32 and upload the sketch.

### 2. Open Serial Monitor
- Set baud rate to **115200**.
- Observe motion sensor interactions and LED status.

## How It Works
1. When the **PIR sensor** detects motion, ESP32 receives a **HIGH** signal and turns the **LED ON**.
2. When no motion is detected, ESP32 receives a **LOW** signal and turns the **LED OFF**.
3. The **Serial Monitor** displays the motion detection status.

## Example Output
```
Motion Detected!
Motion Detected!
```

## Future Enhancements
- Add a **buzzer** to alert when motion is detected.
- Implement **WiFi or Bluetooth** to send notifications.
- Use **low-power mode** to optimize energy consumption.

## License
This project is open-source under the MIT License.

