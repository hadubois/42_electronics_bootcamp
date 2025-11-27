> The goal of this project was to explore pcb desing.
>
> For this we had to :
> . create our own symbol and footprint library
> . reproduce a given schematic
> . desing a pcb using a professional approach

#### BOM

| Reference  | Qty | Value         | Footprint |
| ---------- | --- | ------------- | --------- |
| C1, C2     | 2   | 12pF          | Hadubois_Footprint_Library:Capacitor_12pF_SAMSUNG_CL10C120JB8NNNC |
| C3, C4, C7 | 3   | 100nF         | Hadubois_Footprint_Library:Capacitor_100nF_YAGEO_CC0603KRX7R9BB104 |
| C6         | 1   | 1uF           | Hadubois_Footprint_Library:Capacitor_1uF_SAMSUNG_CL10A105KB8NNNC |
| D1         | 1   | Green         | Hadubois_Footprint_Library:Diode_Green_TUOZHAN_TZ-P2-0603YGTCS1-0.6T |
| D2         | 1   | Red           | Hadubois_Footprint_Library:Diode_Red_XINGLIGHT_XL-1608SURC-06 |
| J3         | 1   | ~             | Hadubois_Footprint_Library:PinHeae_1x06_P2.54mm |
| R1         | 1   | 330           | Hadubois_Footprint_Library:Resistor_330Ω_ROYALOHM_0603WAF3300T5E |
| R2, R3     | 2   | 10K           | Hadubois_Footprint_Library:Resistor_10kΩ_YAGEO_RC0603FR-0710KL |
| SW1        | 1   | SW_Push       | Hadubois_Footprint_Library:Switch_OMRON_B3U-1000P |
| U1         | 1   | ATmega328P-AU | Hadubois_Footprint_Library:MCU_MICROCHIP_ATMEGA328P-AU |
| Y1         | 1   | ~             | Hadubois_Footprint_Library:Crystal_Oscillator_YXC_X322516MLB4SI |

#### Pinout

Pinout for U1 (ATmega328P-AU):

| Pin number | Pin name     | Pin net                  |
|------------|--------------|--------------------------|
| 1          | PD3          | D3                       |
| 2          | PD4          | D4                       |
| 3          | GND          | GND                      |
| 4          | VCC          | RAW                      |
| 5          | GND          | GND                      |
| 6          | VCC          | RAW                      |
| 7          | XTAL1/PB6    | Net-(U1-XTAL1{slash}PB6) |
| 8          | XTAL2/PB7    | Net-(U1-XTAL2{slash}PB7) |
| 9          | PD5          | D5                       |
| 10         | PD6          | D6                       |
| 11         | PD7          | D7                       |
| 12         | PB0          | D8                       |
| 13         | PB1          | D9                       |
| 14         | PB2          | D10                      |
| 15         | PB3          | MOSI                     |
| 16         | PB4          | MISO                     |
| 17         | PB5          | SCK                      |
| 18         | AVCC         | RAW                      |
| 19         | ADC6         | NC                       |
| 20         | AREF         | Net-(U1-AREF)            |
| 21         | GND          | GND                      |
| 22         | ADC7         | NC                       |
| 23         | PC0          | A0                       |
| 24         | PC1          | A1                       |
| 25         | PC2          | A2                       |
| 26         | PC3          | A3                       |
| 27         | PC4          | NC                       |
| 28         | PC5          | NC                       |
| 29         | ~{RESET}/PC6 | DTR                      |
| 30         | PD0          | RXI                      |
| 31         | PD1          | TXO                      |
| 32         | PD2          | D2                       |
