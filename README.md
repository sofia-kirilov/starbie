# Starbie

My version of Starbie, a little desk pet PCB from the Half-Life Week 1 guide.

It runs on a XIAO ESP32-C3 and has an OLED screen, two buttons, an MPU6050 motion sensor, and a DHT11 temperature and humidity sensor. The board is star-shaped.

Wiring: the DHT11 is on D1, the buttons are on D2 and D3, and the screen and motion sensor share I2C on D4 (SDA) and D5 (SCL).
<img width="753" height="357" alt="Screenshot 2026-10-11 at 8 37 19 PM" src="https://github.com/user-attachments/assets/83b5cc09-a6af-4c5a-a3cb-574b6e038bbc" />
