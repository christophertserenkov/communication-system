# A two-way communication system with Raspberry Pi Pico W

### Preview:
![IMG_4340 2](https://github.com/user-attachments/assets/54cb0f8f-b817-43e1-9c3b-2ea681c330c6)

### Description
This project is a two-way communication system built with a Supabase backend. On one side, a React web app allows users to send messages from a computer. On the other side, a Raspberry Pi Pico with Wi-Fi connects to the backend to both send and receive messages.

Inspired by The Martian by Andy Weir, the hardware setup includes a keypad for typing messages in hexadecimal ASCII format. These messages are sent to the Supabase backend. The Pico then fetches incoming messages and displays them on an OLED screen. A joystick allows the user to scroll through the messages on the display.


## Hardware Setup

### Required Components
- Raspberry Pi Pico W
- SSD1306 OLED
- Keypad
- Joystick Module 
- Limit Switches or Buttons (x2) 
- Jumper Wires


### Connections

**Display:**
| SSD1306  | Raspberry Pi Pico W |
|----------|----------|
| GND    | GND     |
| VCC    | 3V3  |
| SCL    | GP17  |
| SDA    | GP16  |

**Joystick:**
| Joystick Module  | Raspberry Pi Pico W |
|----------|----------|
| GND    | GND     |
| +5V    | 3V3  |
| VRx    | GP26 |
| VRy    | GP27  |

**Switch/Button:**
| Limit Switch 1  | Raspberry Pi Pico W |
|----------|----------|
| GND    | GND     |
| VCC    | 3V3  |
| Data    | GP0  |

**Switch/Button:**
| Limit Switch 2  | Raspberry Pi Pico W |
|----------|----------|
| GND    | GND     |
| VCC    | 3V3  |
| Data    | GP1  |

**Keypad:**
| Keypad  | Raspberry Pi Pico W |
|----------|----------|
| 1    | GP9     |
| 2    | GP8  |
| 3    | GP7  |
| 4    | GP6  |
| 5    | GP5  |
| 6    | GP4  |
| 7    | GP3  |
| 8    | GP2  |

