# LW-5 LoRaWAN Soil Moisture, Temperature | Air temperature/humidity | boosted 12v output from battery

The Tinovi LW-5 is a versatile LoRaWAN IO module designed for agricultural and environmental monitoring applications. It features optional soil moisture and temperature sensors, air temperature and humidity measurement capabilities, and a boosted 12v reversible polarity output specifically designed for controlling latching valves. This compact device enables remote monitoring and control of irrigation systems and environmental conditions over long-range LoRaWAN networks.

## Features

- LoRaWAN v1.0.3 Class A device
- Activation methods: OTAA (Over-The-Air Activation) or ABP (Activation By Personalization)
- Soil moisture and temperature sensing capability
- Air temperature and humidity measurement with optional lux sensor
- Boosted 12v reversible polarity output from battery for latching valve control
- Battery-powered operation with voltage measurement
- Configuration via AT UART or Bluetooth using Android adapter
- Long-range wireless communication
- Low power consumption optimized for battery operation

## Use Cases

- Agricultural irrigation monitoring and control
- Smart farming and precision agriculture
- Soil condition monitoring
- Automated valve control for water management
- Environmental data collection
- Remote greenhouse monitoring
- Water conservation systems

## Thinger.io Integration

The LW-5 integrates seamlessly with Thinger.io through standard LoRaWAN network servers, enabling real-time data visualization, device management, and remote valve control capabilities.

## Requirements

A LoRaWAN server is required to communicate the Tinovi LW-5 into Thinger.io, some options are:

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
This product also provides a predefined dashboard and downlinks for valve control.

## Additional Resources

Tinovi resources can be found at:

- [Tinovi Official Website](https://tinovi.com/)
- [The Things Network Device Repository](https://www.thethingsnetwork.org/device-repository/devices/tinovi/pm-io-5-sm/)
- [Thinger docs](https://docs.thinger.io)