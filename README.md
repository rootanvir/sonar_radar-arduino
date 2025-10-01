# Arduino Radar Project Wiring
## [Download](https://processing.org/download) processing for Radar view
## Components Needed
- Arduino Uno (or compatible)
- Servo Motor
- HC-SR04 Ultrasonic Sensor
- Jumper wires
- Breadboard (optional)

---

## Servo Motor Wiring

| Servo Pin | Arduino Pin |
|-----------|-------------|
| VCC       | 5V          |
| GND       | GND         |
| Signal    | 12          |

---

## HC-SR04 Ultrasonic Sensor Wiring

| HC-SR04 Pin | Arduino Pin |
|-------------|-------------|
| VCC         | 5V          |
| GND         | GND         |
| TRIG        | 10          |
| ECHO        | 11          |

---

## Notes
- In processing code change your com number [example : mine is com7]
- If using a high-torque servo, consider an **external 5V supply** instead of Arduino 5V.
- Connect **all GNDs together** if using external power.
- TRIG pin sends a pulse from Arduino; ECHO pin receives the reflected signal.
- The servo delay (30ms per step) allows smooth movement and accurate distance readings.
