# X-CUBE-SBSFU for STM32F746G-DISCOVERY

In this project, I have tried out X-CUBE-SBSFU (Secure Boot and Secure Firmware Update solution) on STM32F746G-DISCOVERY board.

I have used X-CUBE-SBSFU V2.8.0, so workaround from [https://community.st.com/stm32-mcus-security-36/x-cube-sbsfu-v2-8-0-compatible-with-stm32cubeide-v2-2-0-168610] was necessary.

## Changes from STM32F769I-DISCOVERY to STM32F746G-DISCOVERY

I have changed files in Linked_Common folder, because of different memory mapping (STM32F769NIH6 has 2 Mbytes of flash memory and 532 Kbytes of RAM, whereas STM32F746NGH6 has 1 Mbyte of flash memory and 320 Kbytes of RAM).

I have changed pin for UART1_TX, from Port A, Pin 10 --> to Port B, Pin 7
