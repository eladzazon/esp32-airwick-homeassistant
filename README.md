# esp32-airwick-homeassistant

Make your Airwick spray smart using an ESP32 and integrate it with Home Assistant.

## Overview

This project automates an Airwick air freshener using an ESP32 microcontroller and connects it to Home Assistant for smart control. The result is a more efficient, customizable, and environmentally aware air freshening system.

## Motivation

- **Battery Drain**: Traditional Airwick sprayers use AA batteries that often die without warning.  
- **Lack of Smart Control**: They spray at fixed intervals (5, 18, or 36 minutes), regardless of whether anyone is home — even during the night.
- **Simplified Power**: With this setup, both the ESP32 and the Airwick sprayer are powered via a single USB-C port.

## Features

- ✅ Integration with Home Assistant  
- ✅ Smart automation with time-based and presence-based conditions  
- ✅ Remote toggling of the spray schedule  
- ✅ USB-powered for convenience and reliability  

## Example Automation

You can configure Home Assistant to activate the sprayer only when someone is home and at specific times — reducing waste and maximizing efficiency.

## Components Required

| Item                  | Link                                                                 |
|-----------------------|----------------------------------------------------------------------|
| Airwick Sprayer       | Available at your local supermarket                                  |
| ESP32-WROOM           | [AliExpress](https://s.click.aliexpress.com/e/_DnLCAnX)             |
| 3V Relay Module       | [AliExpress](https://s.click.aliexpress.com/e/_Dk7tKI9)             |

## Notes

- Ensure safe handling when working with electrical components.
- Make sure the relay module is properly rated and isolated for your specific sprayer.
