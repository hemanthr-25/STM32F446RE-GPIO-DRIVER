Welcome to the GPIO driver development project for the STM32F446RE microcontroller.
This project demonstrates low-level driver development for GPIO peripherals without
using any HAL libraries directly accessing STM32 registers.

Features
1) GPIO Pin Initialization
2) GPIO Pin Read/Write
3) GPIO Port Configuration
4) Input/Output Modes
5) Pull-up/Pull-down settings
6) Output speed and type configuration
7) Interrupt configuration- Rising/Falling triggering

There are 3 sample projects in this which can be used to demonstrate 
1) main.c -> this toggles the user LED on board
2) 002_userButton.c -> this demonstrates both input and ouput modes using pooling method
3) 003_GPIOinterrupt.c -> this demonstrates both input and output modes using Interrupt method

## 🎥 Project Demo

Watch the project demo on YouTube:  
[![Watch the video](https://img.youtube.com/vi/7cqDdvCFqHc/maxresdefault.jpg)](https://youtu.be/7cqDdvCFqHc)
