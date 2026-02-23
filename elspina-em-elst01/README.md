# EM-ELST01 LoRaWAN State Change Sensor

The EM-ELST01 is a LoRaWAN sensor node designed to capture state changes through its integrated accelerometer and switch sensor. Manufactured by Elspina VEINZ Inc., this device is engineered to reliably detect structural state changes in harsh environmental conditions.

## Features

- **Accelerometer sensor** for motion and vibration detection
- **Conductivity sensor** for environmental monitoring
- **Temperature sensor** for ambient temperature measurement
- **Switch sensor** for digital state detection
- **Wide operating temperature range**: -40°C to 85°C
- **Compact form factor**: 70 x 140 x 50 mm
- **LoRaWAN connectivity** for long-range wireless communication

## Use Cases

- Structural health monitoring
- Asset tracking and condition monitoring
- Industrial equipment state detection
- Environmental monitoring in harsh conditions
- Predictive maintenance applications

## Thinger.io Integration

The EM-ELST01 can be integrated with Thinger.io through LoRaWAN network servers, enabling real-time monitoring and data visualization of accelerometer events, switch states, and environmental parameters.

## Requirements

A LoRaWAN server is required to communicate the EM-ELST01 into Thinger.io, some options are:

- [The Things Stack](https://www.thethingsindustries.com/stack/)
- [LORIOT](https://loriot.io/)
- [ChirpStack](https://www.chirpstack.io/)

Alongside, the corresponding plugin for the selected LoRaWAN server needs to be installed in your Thinger.io instance.

## Get Started

### Installation

Look for the plugin in the [Thinger.io Plugin Store](https://marketplace.thinger.io/) and install it in your Thinger.io instance. Once the plugin is installed a new Product will be created for this device.

### Configuration

The Product is already preconfigured, check that the auto provision prefix matches the one selected in your LoRaWAN server plugin in Thinger.io, or change it to your desire.

### Usage

Start sending uplinks for autoprovisioning devices and buckets.
This product also provides a predefined dashboard for monitoring accelerometer events, switch states, temperature, and conductivity readings.

## Additional Resources

Elspina VEINZ resources can be found at:

- [Device Repository](https://www.thethingsnetwork.org/device-repository/devices/elspina/em-elst01/)
- [Thinger docs](https://docs.thinger.io)