LC sense example using LESENSE.

This example project uses the EFM32 CMSIS and demonstrates the use of 
the LESENSE peripheral on the board.

This demo has two different modes.
To change between them, press PB0. In Mode0 (default). The LESENSE
module will wake up whenever a metal object is passed above the LC
sensor in the bottom right of the STK. In Mode 1, the EFM32 will only
wake up every fifth time the metal object is passed over the sensor.

Board: Silicon Labs EFM32TG_STK3300 Development Kit
Device: EFM32TG840F32
