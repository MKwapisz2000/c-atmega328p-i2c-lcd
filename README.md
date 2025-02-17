# c-atmega328p-i2c-lcd

**Project Description - English**

This project demonstrates how to control an LCD display via the I2C bus using the PCF8574T expander on an ATmega328P. The implementation is done in pure C without Arduino libraries, allowing full control over I2C communication.

Features:

- Communicating with an LCD via I2C (PCF8574T expander)

- Basic LCD functions: initialization, clearing, cursor positioning, text display

- I2C communication implemented in pure C, without Arduino libraries

- Low-level ATmega328P register handling

Hardware Requirements:

- ATmega328P microcontroller (e.g., Arduino Nano or standalone AVR)

- PCF8574T I2C expander for LCD communication

- HD44780-compatible LCD display

- Connecting wires

- 5V power supply

Usage Instructions:

- Compile the code in an AVR C-compatible environment (e.g., Atmel Studio, PlatformIO, AVR-GCC).

- Connect the PCF8574T expander to the I2C bus (SDA – PC4, SCL – PC5).

- Connect the LCD to the PCF8574T according to the chip documentation.

- Upload the program to the microcontroller using an ISP programmer.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5️⃣ The LCD screen will display "Hello World!".
