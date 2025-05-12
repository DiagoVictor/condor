# 🧠 Aviónica del Cohete Sonda

## 🎯 Objetivo

Diseñar un sistema de control y adquisición de datos usando una Raspberry Pi Pico, con sensores y telemetría para recopilar información durante el vuelo.

## 📦 Componentes

- **Microcontrolador:** Raspberry Pi Pico (RP2040)
- **Sensores:**
  - IMU (acelerómetro + giroscopio)
  - GPS
  - Sensor de presión barométrica
  - Temperatura interna
- **Almacenamiento:** microSD (logging local)
- **Transmisión:** LoRa o RF a estación base
- **Energía:** LiPo 7.4V + regulador

## 🧪 Funcionalidades

- Lectura y almacenamiento de sensores
- Control de eventos (ej. eyección paracaídas)
- Transmisión de datos en tiempo real
- Registro en tierra post-recuperación
