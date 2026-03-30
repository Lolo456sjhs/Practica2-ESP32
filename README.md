# Práctica 2 — Pantalla LCD Nokia 5110 y Sensor DHT11 con ESP32

Este repositorio contiene dos sketches para ESP32: uno que muestra texto
en una pantalla LCD Nokia 5110, y otro que además integra un sensor DHT11
para mostrar temperatura y humedad en tiempo real.

## Archivos

- `actividad1.ino` — Muestra el texto "HOLA" y "MUNDO" en la pantalla Nokia 5110.
- `actividad2.ino` — Lee temperatura y humedad del sensor DHT11 y los muestra
  en la pantalla Nokia 5110 y en el monitor serial.

## Librerías necesarias

- Adafruit GFX Library
- Adafruit PCD8544 Nokia 5110 LCD library
- DHT sensor library (de Adafruit)

Para instalarlas ve a Arduino IDE → **Herramientas** → **Administrar librerías**
y busca el nombre de cada una.
