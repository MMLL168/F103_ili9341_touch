## STM32 to ILI9341 Pin Connections

| **STM32 Pin** | **ILI9341 Pin** | **功能**        |
|---------------|-----------------|-----------------|
| PA8           | T_IRQ          | 觸控中斷        |
| PB14          | T_DO           | 觸控數據輸出    |
| PB15          | T_DIN          | 觸控數據輸入    |
| PB12          | T_CS           | 觸控片選        |
| PB13          | T_CLK          | 觸控時鐘        |
| PB4           | LED            | 背光控制        |
| 3.3V          | 3.3V           | 電源供應        |
| PB3           | SCK            | SPI 時鐘        |
| PB5           | SDI (MOSI)     | SPI 數據輸入    |
| PB7           | D/C            | 數據/命令切換   |
| PB8           | RESET          | 重置            |
| PB9           | CS             | SPI 片選        |
| GND           | GND            | 接地            |
| 3.3V          | VCC            | 電源供應        |

<img width="655" height="415" alt="image" src="https://github.com/user-attachments/assets/943a46e9-cc4b-4df9-9d8d-bdbf48357a99" />
