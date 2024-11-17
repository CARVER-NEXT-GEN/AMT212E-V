## AMT212E-V Encoder Integration
This repository provides resources and guidelines for interfacing the AMT212E-V absolute encoder with an STM32 microcontroller. The AMT212E-V encoder offers high-resolution position feedback using RS485 communication, making it suitable for precise control applications.

 ### Key Features
- High Accuracy: Reliable absolute position feedback with resolutions up to 14-bits.
- RS485 Communication: Robust and noise-resistant communication protocol ideal for industrial environments.
- Compact Design: Easy integration into various mechanical assemblies.
### Project Scope
The encoder is configured to communicate with an STM32G474RE microcontroller over RS485. Micro-ROS is used to process and publish data via USB or UART interfaces. This setup enables seamless integration into ROS2-based robotics projects or other control systems requiring high-precision feedback.

For detailed implementation, refer to the sub-directory README files.
