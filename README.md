# Morse Code Generator using LPC2148 and Proteus

This project implements a **Morse Code Generator** using the **LPC2148 microcontroller**, designed to convert text input into Morse code signals. The system features:
- A **keypad** for user input
- An **LCD** for displaying both the entered text and its Morse code equivalent
- An **LED** or **buzzer** to output the Morse code signals

---

## 🔍 Introduction

The Morse Code Generator project aims to develop an embedded system that converts text input into Morse code signals.  
It utilizes:
- **LPC2148 microcontroller**
- **Keypad** for text input
- **LCD** for displaying the input text and corresponding Morse code
- Either an **LED** or **buzzer** for generating Morse code signals  
🎛️💡

---

## ✅ Objectives

- Interface a **keypad** with the LPC2148 microcontroller to input text characters in **Proteus Software**
- Display the **input text** and **corresponding Morse code** on an LCD 📺
- Develop a **software algorithm** to convert text characters into Morse code accurately 🔣➡️🔊
- Generate Morse code signals through **visual (LED)** outputs with correct timing for dots, dashes, and spaces 🔴🔔
- Implement **I2C protocol** to facilitate communication between the microcontroller and LCD or other I2C-enabled peripherals 🔗
- Utilize **Keil uVision 4** for developing, debugging, and testing the microcontroller firmware 💻🐞

---

## 🛒 Components Required

1. **LPC2148 Microcontroller Development Board** 🖥️  
2. **Keypad** 🎹  
3. **LCD** (LM018L, LM016L, or I2C extender PCF8574A) 📺  
4. **LED (RED)** 🔴  
5. **Transistor (BC547)** 🔌  
6. **Resistors (10K ohm)** 🔌  
7. **Power Supply** (5.5V, 5V, and 3.3V) ⚡  

---

## 🛠️ Tools & Software Used

- **Keil uVision 4** – IDE for firmware development  
- **Proteus Design Suite** – Circuit simulation  
- **Flash Magic / USB Bootloader** – For flashing code to LPC2148  

---


---

## 📷 Preview

![image](https://github.com/user-attachments/assets/6aceddae-c9fb-4091-9f64-4633da2cd355)


---

## 📁 Folder Structure Suggestion

```bash
Morse-Code-Generator/
│
├── Code/
│   └── morse_code_generator.c
│
├── Schematics/
│   └── Proteus_design.dsn
│
├── Media/
│   └── screenshots/
│
└── README.md

