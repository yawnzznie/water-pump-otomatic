🔌 Komponen utama:
Arduino Uno

Sensor tanah (soil) → A0

Sensor hujan → A1

Relay module (aktif LOW)

Pompa air DC 12V

Buzzer → pin 7

LCD I2C → SDA ke A4, SCL ke A5

Baterai 12V (buat pompa)

Kabel jumper

💡 Cara sambung:
1. Sensor tanah
VCC → 5V Arduino

GND → GND Arduino

AO → A0 Arduino

2. Sensor hujan
VCC → 5V Arduino

GND → GND Arduino

AO → A1 Arduino

3. Relay module
VCC → 5V Arduino

GND → GND Arduino

IN → pin 8 Arduino

COM → (+) dari baterai 12V

NO → (+) dari pompa

4. Pompa air
(+) dari pompa → NO (relay)

(–) dari pompa → (–) dari baterai

5. Buzzer
(+) buzzer → pin 7 Arduino

(–) buzzer → GND Arduino

6. LCD I2C
VCC → 5V Arduino

GND → GND Arduino

SDA → A4 Arduino

SCL → A5 Arduino

7. Ground baterai dan Arduino disambung
Kabel dari (–) baterai → GND Arduino
(Ini penting supaya pompa dan Arduino punya acuan ground yang sama)
