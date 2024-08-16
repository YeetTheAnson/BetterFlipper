The gerber files can be found [here](https://github.com/YeetTheAnson/BetterFlipper/tree/main/GerberFiles/yeettheanson-betterflipperzero-Gerbers-Versiond79e3345)
the 3d view can be found [here](https://www.flux.ai/yeettheanson/betterflipperzero?editor=pcb_3d)

## Pictures

![Picture1](https://github.com/YeetTheAnson/BetterFlipper/raw/main/1.png)
![Picture2](https://github.com/YeetTheAnson/BetterFlipper/raw/main/2.png)


## Features

- **ESP32-S3-WROOM-1** for processing and connectivity
- **MFRC522** for RFID and NFC operations
- **NRF24L01** for 2.4GHz wireless communication
- **CC1101 Transceiver** for sub-1GHz communication
- **IR Blaster and Receiver** for infrared copy and retransmitting
- **Passive Buzzer** for audio feedback
- **OLED Screen** for easy interaction 

## Wiring

The following table lists the wiring connections for the main components:

| Component       | Pin | Connection  |
|-----------------|-----|-------------|
| **NFC Module**  | 3   | IRQ         |
|                 | 9   | SDA         |
|                 | 10  | MISO        |
|                 | 11  | MOSI        |
|                 | 12  | SCK         |
| **NRF24L01**    | 13  | CE_NRF      |
|                 | 14  | CSN_NRF     |
|                 | 21  | SCK_NRF     |
|                 | 47  | MOSI_NRF    |
|                 | 48  | MISO_NRF    |
|                 | 4   | IRQ_NRF     |
| **OLED Screen** | 5   | DIN         |
|                 | 6   | CLK         |
|                 | 7   | CS          |
|                 | 15  | DC          |
|                 | 16  | RST         |
| **IR Transmitter**| 17| LED         |
| **IR Receiver** | 18  | OUT         |
| **Buzzer**      | 8   | BUZZER      |
| **CC1101**      | 43  | SCLK        |
|                 | 44  | CSN         |
|                 | 42  | SI          |
|                 | 41  | SO/DOI      |
|                 | 40  | GD02        |
|                 | 39  | GDO0/ATEST  |

## NOTE

This project does not include the code required to run this




