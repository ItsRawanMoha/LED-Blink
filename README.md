# LED-Blink Project

Welcome to the LED-Blink project! This project provides a simple example of how to control an LED using a microcontroller. 

## Table of Contents

- [Introduction](#introduction)
- [How it Works](#how-it-works)
- [Getting Started](#getting-started)
- [Steps & Connection](#steps-&-Connection)
- [Output](#output)
- [Code](#code)
- [Pictures](#pictures)
- [Conclusion](#conclusion)

## Introduction

The LED-Blink project demonstrates how to blink an LED using a microcontroller. In this case, we'll be using an Arduino uno board, but the principles can be applied to other microcontroller platforms as well. The project is structured to be simple and easy to understand, making it ideal for beginners.

## How it Works

The project uses an Arduino board to control the LED. The Arduino is programmed to toggle a digital pin on and off, which in turn controls the LED. By adjusting the timing of the toggling, we can control the blinking pattern of the LED.

## Getting Started

To get started with this project, you'll need the following:

- An Arduino board (such as Arduino Uno)
- A USB cable to connect the Arduino to your computer
- An LED
- Jumper wires

## Steps & Connection

Follow these steps to set up the project:

1. Connect the anode (longer leg) of the LED to digital pin 2 on the Arduino.
2. Connect the cathode (shorter leg) of the LED to the ground (GND) pin on the Arduino.
3. Connect your Arduino board to your computer using the USB cable.

## Output

Once you've completed the setup and uploaded the code to your Arduino board, you should see the LED connected to pin 2 blinking on and off at regular intervals.

## Code
```
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(2, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(2, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(2, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
}
```

## Pictures
<img src="https://github.com/ItsRawanMoha/LED-Blink/blob/main/LED-BlinkP.jpeg" alt="Alt text" width="400" height="400">  ![screen-gif](https://github.com/ItsRawanMoha/LED-Blink/blob/main/LED-BlinkG.gif)
## Conclusion

The LED-Blink project provides a simple yet effective demonstration of controlling an LED using a microcontroller. It serves as a great starting point for learning about basic electronics and microcontroller programming.
