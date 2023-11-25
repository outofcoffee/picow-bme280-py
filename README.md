# BME280 on Raspberry Pi Pico W

A project for [Raspberry Pi Pico W](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) to read temperature, humidity and pressure from [BME280](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280/) sensor.

## Prerequisites

Follow instructions for MicroPython on Raspberry Pi Pico W at [Getting started with Raspberry Pi Pico](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf).

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run it

> **Note**
> Ensure your Pico W is connected to your computer via USB and you have flashed the MicroPython firmware.

```bash
mpremote soft-reset
mpremote run main.py
```
