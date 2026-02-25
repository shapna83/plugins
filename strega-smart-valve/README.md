# Smart Valve

The STREGA LoRaWAN wireless smart-valve has an embedded temperature and humidity sensor, tamper detection sensor, and wire-cut detection sensor. It also accepts external analog, digital, and leak detection sensor inputs. The valve may also be configured for full water meter reading and data transmission capabilities.

The battery-operated valve features embedded LoRaWAN® technology with ultra-low-power consumption, enabling time-controlled shut-off operations for water management applications. The motorized actuator provides remote control capabilities for automated water flow control and monitoring.

## Thinger.io Integration

## Requirements

A LoRaWAN server is required to communicate the STREGA Smart Valve into Thinger.io, some options are:

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
This product also provides a predefined dashboard and downlinks.

## Additional Resources

STREGA resources can be found at:

- [Documentation](http://www.stregauniverse.com/)
- [Thinger docs](https://docs.thinger.io)