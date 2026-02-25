# Smart Emitter

The STREGA LoRaWAN Time-controlled Emitter remotely actuates an irrigation valve. With its ultra-low-power consumption, the Smart-Emitter can trigger Open or Close operations of any irrigation valve equipped with a DC latching solenoid. Watering schedulers can be programmed directly at the zone level, avoiding the necessity to use an irrigation controller.

## Features

- Battery-operated wireless device with embedded LoRaWAN technology
- Remote actuation of irrigation valves with DC latching solenoids
- Ultra-low-power consumption for extended battery life
- Time-controlled scheduling at zone level
- IP67 enclosure rating for outdoor installations
- Compact dimensions: 26 x 34 x 77 mm
- Operating temperature range: -30°C to 85°C
- Supports LoRaWAN Class A (battery operated) and Class C (external power supply)
- Available in EU868, US915, and AS923 frequency bands

## Use Cases

- Precision irrigation systems
- Agricultural water management
- Smart farming applications
- Remote irrigation control
- Zone-based watering schedules
- Landscape irrigation automation

## Thinger.io Integration

This device integrates with Thinger.io through a LoRaWAN network server, enabling remote monitoring and control of irrigation valves. The integration allows for automated scheduling, real-time valve status updates, and efficient water management through the Thinger.io platform.

## Requirements

A LoRaWAN server is required to communicate the Smart Emitter into Thinger.io, some options are:

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
This product also provides a predefined dashboard and downlinks for controlling valve operations.

## Additional Resources

STREGA resources can be found at:

- [Device Repository](https://www.thethingsnetwork.org/device-repository/devices/strega/smart-emitter/)
- [Official Website](http://www.stregauniverse.com/)
- [Thinger docs](https://docs.thinger.io)