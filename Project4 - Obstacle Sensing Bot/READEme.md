Creatong a distance-based obstacle sensing bot, where the ultrasonic sensor detects objects, and LEDs or the buzzer provide feedback.

The components required are:
1. Arduino Uno R3 - Microcontroller board
2. Ultrasonic Distance Sensor (4-pin) - Used for distance measurement
3. Red LED - Indicator light
4. Green LED - Indicator light
5. Yellow LED - Indicator light
6. 330Ω Resistor (x3) - Current limiting resistors for LEDs
7. Piezo - Likely a buzzer for sound alerts

The working is:
There is a moving obstacle;
% if speed of obstacle (0cm/s - 20cm/s) Red led blinks.
% if speed of obstacle (20cm/s - 50cm/s) Yellow led blinks.
% if speed of obstacle (>50cm/s) Green led blink + the Buzzer sounds.
