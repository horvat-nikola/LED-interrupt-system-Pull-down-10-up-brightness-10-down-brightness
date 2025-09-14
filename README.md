# LED-interrupt-system-Pull-down-10-up-brightness-10-down-brightness

## LED Interrupt System – Adjustable Brightness

This project demonstrates an **interrupt-based LED control system** with brightness adjustment. The LED brightness is managed using a **pull-down button input** and is modified in steps of **±10%**.

### Features

* **Interrupt-driven control** – No constant polling; the LED reacts instantly to button presses.
* **Pull-down configuration** – Ensures stable input and avoids floating pin issues.
* **Brightness adjustment** – Increase or decrease LED brightness in **10% increments**.
* **Bounded values** – Brightness is clamped between **0% (OFF)** and **100% (MAX)**.

### How It Works

* **Button press (UP)** → Brightness increases by 10%.
* **Button press (DOWN)** → Brightness decreases by 10%.
* Uses **PWM (Pulse Width Modulation)** to adjust LED brightness smoothly.

### Applications

* Simple introduction to **interrupts and PWM** on microcontrollers (e.g., Arduino, STM32, ESP32).
* Can be extended into **dimmer systems**, **LED fading effects**, or **multi-input lighting controls**
