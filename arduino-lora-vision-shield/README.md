# Portenta Vision Shield LoRa®

The Arduino Portenta Vision Shield LoRa® consists of a 320x320 pixels camera sensor and two onboard microphones for directional sound detection. It allows you to run embedded computer vision applications. The Vision Shield LoRa® has been designed to work with the Arduino Portenta H7.

## Features

- **Camera Sensor**: 320x320 pixels with high sensitivity 3.6μ BrightSense™ pixel technology
- **Audio Capture**: 2x MP34DT05 microphones for directional sound detection
- **LoRaWAN Connectivity**: 868/915 MHz ABZ-093 LoRa module
- **Power Supply**: 3.3V supplied by Portenta H7/C33
- **Embedded Computer Vision**: Optimized for AI and machine learning applications at the edge

## Use Cases

- Visual inspection and quality control
- Predictive maintenance with image and audio analysis
- Security and surveillance applications
- Industrial automation with computer vision
- Environmental monitoring with image capture
- Edge AI applications combining vision and sound

## Thinger.io Integration

The Portenta Vision Shield LoRa® can be integrated with Thinger.io through LoRaWAN connectivity, enabling remote monitoring and control of computer vision applications with cloud-based data management.

## Requirements

A LoRaWAN server is required to communicate the Arduino Portenta Vision Shield LoRa® into Thinger.io, some options are:

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

- [Portenta Vision Shield Documentation](https://docs.arduino.cc/tutorials/portenta-vision-shield/user-manual)
- [Datasheet](https://docs.arduino.cc/resources/datasheets/ASX00021-ASX00026-datasheet.pdf)
- [Thinger docs](https://docs.thinger.io)