# LRS20310 - Water Leak Sensor

The LRS20310 is a LoRaWAN water leak sensor designed to provide a simple and cost-effective solution for monitoring water leakage and flooding in premises and assets. The device features a stainless steel 2-pin water probe that detects the presence of water and transmits alerts via LoRaWAN connectivity, enabling real-time monitoring and early detection of potential water damage.

## Features

- **Water Detection**: Stainless steel 2-pin water probe for reliable leak detection
- **LoRaWAN Connectivity**: Long-range wireless communication using LoRaWAN protocol
- **Battery Operation**: Extended battery life for maintenance-free operation
- **Durable Enclosure**: IP65-rated housing for protection against dust and water ingress
- **Compact Design**: 112 x 70 x 39 mm dimensions for easy installation
- **Wide Operating Temperature**: -20°C to 70°C temperature range
- **Analog Measurement**: 0-100 analog measurement resolution for precise detection

## Use Cases

- **Data Centers**: Monitor server rooms and equipment areas for water leaks
- **Commercial Buildings**: Detect flooding in basements, storage areas, and mechanical rooms
- **Industrial Facilities**: Protect critical infrastructure and machinery from water damage
- **Residential Applications**: Monitor water heaters, washing machines, and plumbing systems
- **Healthcare Facilities**: Early detection of leaks in hospitals and medical centers
- **Warehouses**: Protect inventory and goods from water damage

## Thinger.io Integration

The LRS20310 integrates with Thinger.io through LoRaWAN network servers, enabling centralized monitoring, data visualization, and alerting capabilities for water leak detection applications.

## Requirements

A LoRaWAN server is required to communicate the LRS20310 into Thinger.io, some options are:

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

Device resources can be found at:

- [Device Repository](https://www.thethingsnetwork.org/device-repository/devices/arwin-technology/lrs20310/)
- [Thinger docs](https://docs.thinger.io)