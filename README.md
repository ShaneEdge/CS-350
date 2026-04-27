# CS 350 Portfolio: Smart Thermostat Project

### Project Summary
For this project, I built a prototype for a smart thermostat. The goal was to solve a problem for a company called SysTec that needed a way to control room temperature and send that data to a server. I used a Raspberry Pi 4, a temperature sensor, and a small LCD screen. The system can switch between heating and cooling modes and lets the user change the target temperature with buttons.

### What I Did Well
I think I did a great job setting up the "state machine." This is the part of the code that tells the thermostat exactly what to do when it is in "Off," "Heat," or "Cool" modes. I also got really good at troubleshooting hardware. At first, my sensor wouldn't talk to the computer, but I learned how to use tools to find and fix the wiring issues.

### Areas for Improvement
If I had more time, I would like to make the hardware setup cleaner. Right now, there are a lot of wires on a breadboard. I would also like to add a more advanced screen that could show a graph of the temperature over time instead of just the current numbers.

### New Tools and Resources
During this project, I added some great tools to my skill set. I learned how to use VS Code to work on a Raspberry Pi remotely. I also started using the "gpiozero" and "adafruit" libraries, which are very helpful for making software interact with the real world.

### Transferable Skills
The most important thing I learned is how a state machine works. This is a skill I can use in almost any kind of software, not just hardware projects. Learning how different parts of a computer communicate through things like "I2C" and "Serial" will also help me in future engineering classes.

### Maintainability and Readability
To make sure other people can understand my code, I used clear names for all my functions and added comments to explain what each section does. I used a "class" structure to keep the code organized. This makes it easier to update the code later without breaking the whole system.
