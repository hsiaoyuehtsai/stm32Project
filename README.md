# STM32 Projects

This repository contains various STM32CubeIDE projects demonstrating different functionalities using the STM32 microcontroller. Each project builds upon previous ones to showcase the capabilities of GPIO, interrupts, USART communication, I2C, timers, PWM, and more.

## Project 1: Light

**Description**: Utilize GPIO pins to configure red, green, and blue LEDs to create a breathing light effect by transitioning between colors.

## Project 2: Button Light

**Description**: Use GPIO to read two buttons to control the LEDs. The buttons can toggle the lights on and off and switch between different colors.

## Project 3: Interrupt Light

**Description**: Based on Project 2, implement an interrupt on a specified red LED that blinks at a fixed delay. Use button interrupts to control the toggling of a green LED.

## Project 4: Serial Communication

**Description**: Use USART to transmit commands that control the LEDs to turn on or off specific colors. Redefine callback functions to implement DMA interrupt reception.

## Project 5: Bluetooth (BLE)

**Description**: Learn to use the BT24 Bluetooth module to transmit data via USART to control the LEDs. Implement checksum verification to ensure data integrity.

## Project 6: I2C Communication

**Description**: Use the I2C protocol to read temperature and humidity data from the AHT20 sensor. Transmit the data via USART to display it on a serial port monitor on the computer.

## Project 7: OLED Display

**Description**: Learn how to control an OLED display by lighting up pixels to render content.

## Project 8: AHT20 Sensor with OLED Display

**Description**: Similar to Project 6, read temperature and humidity data from the AHT20 sensor, but display the data on the OLED screen instead.

## Project 9: Timer

**Description**: Use a timer to automatically increment a counter and display the value on the computer.

## Project 10: Timer External Input

**Description**: Use a line-tracking sensor to trigger the timer counter increments and display the count on the OLED screen.

## Project 11: Slave Mode

**Description**: Learn the three modes of timer slave mode: reset mode, gate mode, and trigger mode.

## Project 12: Timer Input Capture

**Description**: Use the HC-SR04 ultrasonic distance measurement module to measure distances.

## Project 13: PWM Light

**Description**: Control the brightness of LEDs by adjusting the PWM frequency.

## Project 14: Timer Encoder

**Description**: Use a rotary encoder to control the brightness of an LED and display the brightness value on the OLED screen.

## Project 15: Servo Control

**Description**: Use the timer's counter to read values from a rotary encoder and transmit these values to control a servo motor (SG90), adjusting its rotation angle.

## Project 16: DC Motor Control Using Encoder
**Description**: Utilize a timer to read values from a rotary encoder, allowing precise control of a DC motor’s direction (forward/reverse). Additionally, adjust the motor's speed by varying the PWM (Pulse Width Modulation) duty cycle.