# MIPSDomaci

# STM32 Projekat - Blikanje LED Diodom

## Pregled
Ovaj projekat demonstrira osnovne principe programiranja STM32 mikrokontrolera koristeći integrisano razvojno okruženje STM32CubeIDE. Uključuje jednostavan primer blikanja LED diode.

## Detalji Projekta
- **IDE (Integrisano Razvojno Okruženje)**: STM32CubeIDE
- **Simulator**: Proteus
- **MCU (Mikrokontroler)**: STM32F1xx

## Pravila Konfiguracije
Projekat koristi sledeća pravila za konfiguraciju GPIO porta i pina:
- Ako je broj samoglasnika u imenu i prezimenu veći od broja suglasnika, koristi se `GPIOA` kao port.
- U suprotnom, koristi se `GPIOB` kao port.
- GPIO pin se određuje modulom zbira dužina imena i prezimena.
  
Ime i prezime KRISTINA TRAJKOVIC:
6 samoglasnika i 10 suglasnika odabran je PORTB.
PIN: 17mod6 = 5

## Šema Blikanja LED Diodom
LED dioda blinka prema sledećem obrascu:
- Širina impulsa (LED UPALJENA) je jednaka dužini imena u milisekundama.
- Širina pauze (LED UGASENA) je jednaka dužini prezimena u milisekundama.

## Struktura Projekta
- **main.c**: Sadrži glavnu logiku programa.
- **stm32f1xx_hal.h**: Header fajl za STM32 Hardware Abstraction Layer.
- **main.h**: Header fajl za main.c.
- **README.md**: Dokumentacija projekta.


