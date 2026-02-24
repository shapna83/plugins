# RCM-LRW10 Module for GWFCoder

The GWFcoder radio module RCM-LRW10 from GWF MessSysteme eliminates the need to change meters for the migration of water and gas meters with GWFcoder to an LPWAN network. With simple and quick on-site installation via Plug & Play, no programming is required and is ready for immediate use with a waterproof housing (protection class IP68).

## Features

- **Backwards Compatible**: No meter change required when migrating water and gas meters with GWFcoder interface into a Low Power Wide Area Network (LPWAN)
- **Battery Powered**: LoRaWAN radio module with up to 15 years battery lifetime in custom-tailored RF Mode
- **Long Range Performance**: Range up to several kilometers
- **Plug & Play Installation**: Easy and fast on-site installation with auto interface-detection and activation in LoRaWAN, no programming required
- **LoRa Alliance Certified**: Interoperable with different LoRaWAN network providers
- **Waterproof Design**: Protection class IP68 for pit installations
- **Secure Communication**: Data security via AES-128-bit end-to-end encryption over 2 independent security layers
- **Adaptive Data Rate**: ADR support for higher transmission intervals with consistent battery life
- **Split Connection**: Cable connection to the meter enables remote installation
- **Infrared Configuration Interface**: For on-site parameter configuration

## Technical Specifications

- **Frequency Band**: LoRaWAN 868 MHz
- **Meter Interface**: Meter with GWFcoder or GWFcoder MP register with SCR(IEC) or ECO interface
- **Compatible Meters**: All water and gas meters (domestic and industrial) with GWFcoder/GWFcoder MP register
- **Transmission Interval**: 
  - Configuration 1: Fixed transmission interval (daily)
  - Configuration 2: Dynamic transmission interval (up to 15 minutes, depending on meter interface and LoRaWAN network quality)
- **Activation Type**: OTAA or ABP
- **Data Transmission**: Latest register value and additional information
- **Monitoring Features**: Integrated connectivity monitoring and automatic reconnecting mechanisms

## Warnings and Alerts

The module supports various configurable warnings (all enabled or disabled, available from radio module version ≥1.4.0):

- Continuous flow / Leak (water only)
- Backflow (requires on-site reset)
- Pipe burst (meter size must be configured on-site)
- No usage over a period of 30 days

## Use Cases

- Simple readout of water and gas meters with GWFcoder registers without necessity to access buildings
- Migration of installed meters with GWFcoder registers to a smart metering system via LoRaWAN
- Energy monitoring, energy reporting and consumption accounting
- Integration of water and gas meters with GWFcoder registers in smart city projects

## Thinger.io Integration

The RCM-LRW10 integrates with Thinger.io through LoRaWAN network servers, enabling remote monitoring and management of water and gas meter data.

## Requirements

A LoRaWAN server is required to communicate the RCM-LRW10 into Thinger.io, some options are:

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

GWF resources can be found at:

- [Product Information](https://productfinder.gwf.ch/en/rcm-lrw10)
- [LoRa Alliance Documentation](https://lora-alliance.org/wp-content/uploads/2019/07/rcm28R-lrw10_epe40261.pdf)
- [Thinger docs](https://docs.thinger.io)