# CODTECH-Task1
NAME: SRIKANTH GUJJALA
COMPANY : CODETECH IT SOLUTIONS 
ID : CT6WDS70
DOMAIN : EMBEDDED SYSYTEMS
DURATION : JUNE TO JULY 2024
OVERVIEW OF THE PROJECT:
Project : LED BLINKING WITH ARDUINO
OVERVIEW OF THE PROJECT:
Components:
Arduino board (Uno, Nano, etc.)
LED (Light Emitting Diode)
Resistor (220 ohm is common)
Breadboard (optional, for making connections)
Circuitry:
Connect the longer leg of the LED (positive) to the resistor's one end.
Connect the other end of the resistor to an Arduino digital pin (e.g., pin 13).
Connect the shorter leg of the LED (negative) to the Arduino's ground (GND) pin.
Code:
Setting Up:
Use pinMode(LED_PIN, OUTPUT); to define the LED pin as output.
Looping:
Inside the loop() function, use digitalWrite(LED_PIN, HIGH); to turn the LED on.
Use delay(DELAY_TIME); to pause for a duration (e.g., 1 second).
Use digitalWrite(LED_PIN, LOW); to turn the LED off.
Use another delay(DELAY_TIME); to pause again.
Explanation:
The resistor limits current to protect the LED.
pinMode configures the pin to control the LED.
digitalWrite sets the pin high (5V) to turn the LED on and low (0V) to turn it off.
delay pauses the program for a specified time to create the blinking effect.
Compiling and Uploading:
Use the Arduino IDE software to write and upload the code to your Arduino board.
Beyond the Basics:
This project lays the foundation for more complex Arduino projects. You can modify the code to change the blinking speed or create different LED patterns.

