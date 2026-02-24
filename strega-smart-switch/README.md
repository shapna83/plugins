# Smart Switch

The STREGA time-controlled switch for the valve actuators is a battery operated wireless switch to remote control your butterfly valves. With the ultra-low-power consumption, the smart-switch can be triggered for remote OPEN/CLOSE operations.

## Features

- Battery-operated wireless control for valve actuators
- LoRaWAN® communication protocol
- Ultra-low-power consumption
- Remote OPEN/CLOSE valve operations
- Time-controlled switching capability
- Extreme long-range connectivity
- Deep indoor signal penetration
- Direct actuator piloting for butterfly valves

## Thinger.io Integration

The Smart Switch integrates with Thinger.io through LoRaWAN connectivity, enabling remote monitoring and control of valve actuators from the cloud platform.

## Requirements

A LoRaWAN server is required to communicate the Smart Switch into Thinger.io, some options are:

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
This product also provides a predefined dashboard and downlinks for remote valve control operations.

## Additional Resources

STREGA resources can be found at:

- [Product Information](https://www.stregatechnologies.com/products/smart-switch-for-valve-actuator/)
- [Datasheet](http://www.stregatechnologies.com/wp-content/uploads/2020/05/Datasheet-Smart-Switch-for-Valve-Actuator-UK.pdf)
- [Thinger docs](https://docs.thinger.io)