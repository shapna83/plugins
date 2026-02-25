# Arduino MKR WAN 1310

The Arduino MKR WAN 1310 is a development board that provides a practical and cost-effective solution to add LoRaWAN® connectivity for projects requiring long-range, low-power wireless communication. Sensors and actuators can be connected to the board through the analog, digital, UART, SPI, and I2C pins. The MKR WAN 1310 comes complete with an ATECC508 secure element, a battery charger, 2MByte SPI Flash, and power consumption as low as 104 uA.

## Features

- **Microcontroller**: SAMD21 Cortex-M0+ 32-bit low power ARM MCU
- **Radio Module**: Murata CMWX1ZZABZ (based on Semtech SX1276)
- **Operating Voltage**: 3.3V
- **Input Voltage**: 5V (via USB/VIN)
- **Secure Element**: ATECC508 cryptographic co-processor
- **Memory**: 2MB SPI Flash
- **Power Consumption**: As low as 104 µA
- **Battery Charger**: Integrated Li-Po charging circuit
- **Connectivity**: LoRaWAN®, I2C, SPI, UART
- **I/O**: Analog and digital pins

## Use Cases

- Long-range IoT sensor networks
- Remote environmental monitoring
- Smart agriculture applications
- Asset tracking
- Smart city deployments
- Industrial IoT solutions
- Battery-powered remote sensors

## Thinger.io Integration

The Arduino MKR WAN 1310 can be integrated with Thinger.io through LoRaWAN network servers, enabling remote device management, data visualization, and bidirectional communication.

## Requirements

A LoRaWAN server is required to communicate the Arduino MKR WAN 1310 into Thinger.io, some options are:

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

Arduino resources can be found at:

- [Arduino MKR WAN 1310 Documentation](https://docs.arduino.cc/hardware/mkr-wan-1310)
- [Arduino Store](https://store.arduino.cc/products/arduino-mkr-wan-1310)
- [Thinger docs](https://docs.thinger.io)