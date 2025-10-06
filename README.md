# SI4735Android

An Android library for ion-based communication with si4735-arduino projects.

SI4735Android enables Android applications to control SI473X radio receiver chips connected to Arduino devices. The library uses ion's remote procedure call protocol to communicate with iota code running on the Arduino, allowing remote control of AM, FM, SW, and LW radio reception.

## Dependencies

This library builds on several foundational libraries from the Operator Foundation ecosystem:

- **TransmissionAndroid** - Provides USB serial communication with Arduino devices
- **SignalBridge** - Handles USB audio device management for Android
- **ion-kotlin** - Implements the ion data transport protocol and RPC functionality

## Prerequisites

- An Android device
- An Arduino with a SI473X radio receiver chip
- The si4735-arduino library installed on your Arduino
- A communication channel between your Android device and Arduino (USB, Bluetooth, etc.)

## Status

This library is currently under development. More detailed documentation, examples, and implementation details will be added as development progresses.

## Related Projects

- [si4735-arduino](https://github.com/OperatorFoundation/si4735) - iota bindings for the SI473X radio receiver chips
- [pu2clr/SI4735](https://github.com/pu2clr/SI4735) - The underlying C++ driver library
- [TransmissionAndroid](https://github.com/OperatorFoundation/TransmissionAndroid) - USB serial communication library
- [SignalBridge](https://github.com/OperatorFoundation/SignalBridge) - USB audio device management
- [ion-kotlin](https://github.com/OperatorFoundation/ion-kotlin) - ion protocol implementation for Android
