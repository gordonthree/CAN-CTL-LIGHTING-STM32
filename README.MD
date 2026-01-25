# Interior Lighting Controller
Compact lighting controller board intended to interface with three-channel PWM dimmable lighting modules. The controller works with other CANCTL modules using the robust CAN bus interface.

<img src="https://github.com/gordonthree/CAN-CTL-LIGHTING-STM32/blob/main/CAN-CTL-LIGHTING-STM32.png?raw=true" width=480 alt="3d rendering of circuit board">

# Multi-IO Node
* STM32G0B1RCT6 Microcontroller, 256k flash, 64mhz clock
* Automotive grade switch-mode power supply for 5v rail
* Automotive grade low-dropout linear supply for 3.3v rail
* 3-pin terminal block for CANBUS connection with drain
* Jumper selected CAN terminator resistor
* Four five position screw terminal connectors for 12v lighting modules
* 12 digital output channels in groups of 3, driven at 5v by hex schmitt line drivers
* Two LED indicators for status, controlled by the micro
* Bidirectional transient voltage protection diode for harsh environments
* Headers for USART1 serial port and SWD programming connector
  
