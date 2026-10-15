# STM32F411 IMU Board (Altium Designer)
Motion-sensing board built around an STM32F411 Cortex-M4 MCU and an MPU-6050 6-axis IMU, with micro-USB power and SWD debug. Designed in Altium Designer

<img width="682" height="702" alt="image" src="https://github.com/user-attachments/assets/0dee7e77-5b9e-494b-9c93-fa9f5855c0fd" />

## Specifications
- MCU: STM32F411 (UFQFN48)
- Sensor: MPU-6050 over I2C
- Power: micro-USB, ferrite-filtered VBUS, AMS1117-3.3 regulator
- Debug: Tag-Connect TC2030 SWD header
- 4-layer board, about 1.6 mm, stackup: Signal / GND / GND / Signal

## Design notes
- Two solid ground planes on L2 and L3 give continuous return paths.
- Net classes: signals at 0.2 mm, power at 0.3 mm, 0.2 mm clearance.
- 0.3 mm drill / 0.6 mm pad vias.
- Differential pair rule applied to the USB data lines.

## Status
Designed only
