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

- The LCD screen will display "Hello World!".

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Opis projektu - Polski**

Ten projekt demonstruje obsługę wyświetlacza LCD poprzez magistralę I2C z wykorzystaniem ekspandera PCF8574T na ATmega328P. Implementacja odbywa się w czystym C bez bibliotek Arduino, co pozwala na pełną kontrolę nad komunikacją I2C.

Funkcjonalność:

- Komunikacja z LCD przez interfejs I2C (PCF8574T)

- Obsługa podstawowych funkcji LCD: inicjalizacja, czyszczenie ekranu, ustawianie kursora, wyświetlanie tekstu

- Implementacja sterowania I2C w czystym C, bez bibliotek Arduino

- Obsługa mikrokontrolera ATmega328P na niskim poziomie (rejestry)

Wymagania sprzętowe:

- Mikrokontroler ATmega328P (np. Arduino Nano lub standalone AVR)

- Ekspander PCF8574T do komunikacji LCD przez I2C

- Wyświetlacz LCD kompatybilny z HD44780

- Przewody połączeniowe

- Zasilanie 5V

Instrukcja użytkowania:

- Skompiluj kod w środowisku obsługującym AVR C (np. Atmel Studio, PlatformIO, AVR-GCC).

- Podłącz ekspander PCF8574T do magistrali I2C (SDA – PC4, SCL – PC5).

- Podłącz LCD do PCF8574T zgodnie z dokumentacją układu.

- Wgraj program do mikrokontrolera za pomocą programatora ISP.

- Na ekranie LCD pojawi się tekst "Hello World!".
