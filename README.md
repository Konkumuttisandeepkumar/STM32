# STM32 Embedded Peripheral Examples

Peripheral firmware examples on two STM32 boards using 
STM32CubeIDE and HAL library.

## Boards

### STM32F401RBT6 (ARM Cortex-M4, 84MHz, 128KB flash)
| Example | Peripheral | Description |
|---------|-----------|-------------|
| Led_Blink | GPIO | Basic output toggle |
| ADC_Multichannel | ADC | Multi-channel analog read |
| PWM | TIM + PWM | PWM signal generation |
| Timers_PWM | TIM + PWM | Timer-based PWM control |
| UART_Transmit | USART | Serial data transmission |

### NUCLEO-G0B1RE (ARM Cortex-M0+, 64MHz, 512KB flash)
| Example | Peripheral | Description |
|---------|-----------|-------------|
| LED_Blink | GPIO | Basic output toggle |
| ADC_Multichannel | ADC | Multi-channel analog read |
| CAN_Receive | bxCAN | CAN bus frame reception |
| CAN_Transmit | bxCAN | CAN bus frame transmission |
| PWM_Generation | TIM + PWM | PWM signal generation |

## Tools
- STM32CubeIDE
- HAL Library
- ST-Link debugger

## Notes
CAN bus examples (Receive + Transmit) written during 
early embedded learning — later applied to 3 years of 
production EV charger firmware development on 
Infineon XMC4400 with CAN protocol.
