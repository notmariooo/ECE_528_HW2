# ECE 528/L - Homework 2

## Section I: Review Questions


### Question 1

#### What is a hardware timer? What kinds of tasks do embedded systems commonly use hardware timers for?

A hardware timer is a dedicated counter peripheral that increments or decrements on each edge of a clock signal, independently of the CPU. Once it is configured, it runs on its own and can set flags or generate interrupts when it reaches specific count values.

Embedded systems commonly use hardware timers for:
- Creating precise delays and timeouts
- Generating periodic interrupts to schedule tasks
- Generating PWM signals for motors, servos, and LEDs
- Capturing input events to measure pulse widths, frequencies, or motor speed
- Timestamping events
- Watchdog timers that reset the system if the software stops responding
