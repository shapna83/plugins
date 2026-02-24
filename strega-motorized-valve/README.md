# Wireless LoRaWAN Motorized Smart Valve

The STREGA LoRaWAN wireless motorized smart-valve is a battery-operated wireless valve controller with embedded LoRaWAN® technology and industrial-grade design. It features an embedded temperature and humidity sensor, tamper detection sensor, and wire-cut detection sensor. The valve accepts external analog, digital, and leak detection sensor inputs, and may also be configured for full water meter reading and data transmission capabilities. With its ultra-low-power consumption, the valve can operate on batteries for 10-15+ years and communicate through extreme long distances with exceptional obstacle penetration, even inside buildings or urban areas.

## Features

- **Long-Range LoRaWAN Connectivity**: Multi-kilometer range even in dense urban areas with deep indoor signal penetration
- **Ultra-Low Power Consumption**: Battery life of 10-15+ years on Lithium batteries, or unlimited runtime with external power
- **Embedded Sensors**: Temperature, humidity, tamper detection, and wire-cut detection
- **External Sensor Inputs**: Analog, digital, and leak detection sensor compatibility
- **Water Meter Integration**: Full water meter reading and data transmission capabilities
- **Secure Communication**: Unique AES128 encryption key per device
- **Real-Time Monitoring**: Transmits valve status (Open/Close), device ID, battery level, signal strength, enclosure tampering, alarms, leak detection, pressure level, ambient temperature, and counter values
- **DN20 Solenoid Valve**: 3/4'' pipe size compatibility
- **Network Flexibility**: Compatible with private and public LoRaWAN networks
- **LoRaWAN Class Support**: Operates on Class A, B, and C communication modes

## Use Cases

- Remote water flow control and monitoring
- Leak detection and automatic shut-off
- Smart building water management
- Agricultural irrigation control
- Industrial process control
- Utility metering and billing
- Water conservation and usage optimization
- Tamper detection and security monitoring

## Thinger.io Integration

This device integrates seamlessly with Thinger.io through LoRaWAN network servers, enabling centralized management, real-time monitoring, and remote control of valve operations.

## Requirements

A LoRaWAN server is required to communicate the STREGA Wireless LoRaWAN Motorized Smart Valve into Thinger.io. Some options are:

- [The Things Stack](https://www.thethingsindustries.com/stack/)
- [LORIOT](https://loriot.io/)
- [ChirpStack](https://www.chirpstack.io/)

Alongside, the corresponding plugin for the selected LoRaWAN server needs to be installed in your Thinger.io instance.

## Get Started

### Installation

Look for the plugin in the [Thinger.io Plugin Store](https://marketplace.thinger.io/) and install it in your Thinger.io instance. Once the plugin is installed, a new Product will be created for this device.

### Configuration

The Product is already preconfigured. Check that the auto provision prefix matches the one selected in your LoRaWAN server plugin in Thinger.io, or change it to your preference.

### Usage

Start sending uplinks for autoprovisioning devices and buckets. This product also provides a predefined dashboard and downlinks for remote valve control and monitoring.

## Additional Resources

STREGA resources can be found at:

- [Product Page](https://www.stregatechnologies.com/products/wireless-smart-valve/)
- [Documentation](https://www.stregauniverse.com/)
- [Thinger.io Documentation](https://docs.thinger.io)