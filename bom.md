# BOM for the TempScreen Project/PCB

## Sensor
DHT22 or DHT11 Digital thermometer/humidity sensor 
the pinouts for the DHT22 and DHT11 are the same, but the DHT22 has better performence and is more accurate
Pins with the "intake" to the front
Pin 1 to VCC
Pin 2 to Data
Ignore pin 3
Pin 4 to Ground/GND
## Display
SSD1306 128x64 or 128x32 pixel i2c OLED as a Display that can be mounted in the head or in the eyes
(Most come with 4 pinheaders that can be desoldered and replaced with wires)

## Computing 
Pro Micro, NiceNano! or simular Pro Micro footprint boards 
(!Pro Micro USB C boards are a bit longer and will not fit in the case!)

## PCB, resistor and case 
You will need one PCB, one 10kOhm resistor and a 3D printed case (for convenience and to avoid ESD that could damage the parts)

## Wire/Power
You should use semi-thin and flexible wire to connect the DHT22/11 and SSD1306 to the PCB
The Pro Micro takes 5V, you can use a normal small powerbank for it