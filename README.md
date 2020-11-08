# Water-Touch Detector

A simple circuit which detects water or touch by utilizing two 2n2222 transistors, an LED, and a piezoelectric speaker.

## Materials

- Breadboard
- 2 2n2222 transistors
- A power source (I used the 5V pin from the arduino, but feel free to use something else)
- Around 10 jumper wires
- Piezoelectric speaker
- 100 ohm resistor
- One LED

## Schematic

![design image](https://github.com/angelina-tsuboi/Simple_Water-Detector/blob/main/images/design.png)

## How It Works

This project utilizes two 2n2222 transistors in order to detect the touch/water and light up/play the piezoelectric speaker. A 2N2222 transistor is one of the most popular NPN (negative-positive-negative) Bipolar Junction Transistor (BJT) available as of today. Transistors today have many use cases (ie. amplifiers, switches, etc). For this project, we wil being using both transistors as switches. The 2n2222 has three leads (base, emitter, and the collector). There is a wire connecting the emitters of both of the transistors. A second wire is also connected to the emitter of the first transistor. This will send a current to the emitters of both transistors when the second wire meets up with some current. Furthermore, another wire connects the bases of both emitters and a 100 ohm resistor connects to the base of the first transistor. This provides a stable current to both transistors. Also, I attached one end of a jumper wire to the base of the first transistor. This will let both transistors detect the current passing through the jumper wire attached to the base and the other jumper wire connected to the emitter of the first transistor. Finally, a jumper wire connects the collector of the first transistor to one leg of the piezoelectric speaker and another wire connects the collector of the second transistor to the anode of the LED.
By connecting the other leads of the LED and the speaker to ground, you should be able to produce a fully functioning water/touch detector circuit! The water and/or touch are detected by the jumper wires connected to the base and emitter of the first transistor.

## Completed Project

![project photo](https://github.com/angelina-tsuboi/Simple_Water-Detector/blob/main/images/final.jpg)

## Sources

[transistor info source](https://www.theengineeringprojects.com/2017/06/introduction-to-2n2222.html)
[DroneBot Workshop's fantastic explaination of transistors and MOSFETs](https://www.youtube.com/watch?v=IG5vw6P9iY4)