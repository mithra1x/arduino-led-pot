# LED Brightness Control with Potentiometer (Arduino)

This is a simple Arduino project that allows you to control the brightness of an LED using a potentiometer.

## 🔧 Components Used

- 1x Arduino Uno
- 1x LED
- 1x 220Ω resistor
- 1x Potentiometer (10kΩ recommended)
- Jumper wires
- Breadboard

## ⚙️ Circuit Diagram

- Connect the LED to PWM pin (e.g., D9) through a resistor.
- Connect the middle pin of the potentiometer to A0.
- Connect the other two potentiometer pins to 5V and GND.

## 💡 How It Works

- The potentiometer sends an analog signal (0–1023) to pin A0.
- The Arduino reads this value and maps it to PWM range (0–255).
- The LED brightness is updated accordingly via `analogWrite()`.

## 📂 Code File

See the code in [`ledBrightness.ino`](ledBrightness.ino)

## 📝 License

MIT License
