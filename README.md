# STM32 Projects

A collection of projects exploring various features of the STM32 microcontroller.

## LCD1602 Display Integration

### Overview

This sub-project demonstrates the integration of the LCD1602 display module with an STM32 microcontroller.

### Key Resources & Files
- **Tutorial Reference:** The implementation is majorly based on [Nizar's Youtube tutorial](https://www.youtube.com/watch?v=_tosXa3da-g). The tutorial showcases the setup using a potentiometer to adjust the LCD's contrast.
  
- **Modification:** Unlike Nizar's method, which employs a potentiometer, I've used a 330-ohm resistor to set the display contrast to an optimal value.
  
- **Files:** 
  - [lcd.h - Header File](LCD1602/Core/Inc/lcd.h)
  - [lcd.c - Source File](LCD1602/Core/Inc/lcd.c)
  - [main.c - Main Application Source](LCD1602/Core/Src/main.c)

### Visual

Here's the final result of the LCD1602 display after integration:
  
![Final Result](LCD1602/LCD.jpg)
