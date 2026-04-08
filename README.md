# STM32 Water Level Control System

## 📌 Project Description
This project is developed using STM32F072 microcontroller.

- Water level is read using ADC (0–4095)
- Converted to percentage
- UART receives "AC" command from PC
- If level exceeds threshold by 25%, outputs activate
- Emergency button triggers interrupt for 30 seconds
- TIM2 is used for time counting
- PWM is used for control

## ⚙️ Technologies Used
- STM32 HAL Library
- ADC
- UART (Interrupt)
- PWM (TIM3)
- Timer Interrupt (TIM2)
- GPIO

## 🎯 Features
- Real-time monitoring
- Interrupt-based control
- Embedded system design

## 👨‍💻 Author
Sevsen# STM32_ADC_PWM_Project
STM32 project using ADC and PWM to control fan speed
