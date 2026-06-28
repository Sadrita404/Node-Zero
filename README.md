| Title | Node Zero |
| :-- | :---|
|Author |Sadrita Neogi|

## What's this?

Node Zero is an  rp2040 based micro-controller unit that consist of the rp2040 micro processor, the 16Mbit SPI NOR Flash, a crystal oscillator that synchronizes communication in the board between the USB abd rp2040, a voltage regulator, reset and boot switch.

## Why I built it ?

This is the starter project of stasis and I have not make any dev board ever before, so this is my the first time I am making an dev board so I am very excited to build this. That's why I am making the PCB whole custom thing. I have also get help from the detailed guide that is provided on the stasis website.

<div align="center">

| | PCB Designing | |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/759fe6fd-2cbe-497b-bc1d-d9d64e6fac41" width="250" alt="Design 1" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/d0556f03-84be-48b9-a0e8-1394d569a171" width="250" alt="Design 2" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/218c5e27-fa63-4ae4-8647-1121e0d25065" width="250" alt="Design 3" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/82201565-5987-4f3b-b76d-23958360d7ba" width="250" alt="Design 4" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/49a3e565-4683-4525-ad50-877e70e4a111" width="250" alt="Design 5" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/ebe2ae68-f09d-427b-bc5a-9074a557210c" width="250" alt="Design 6" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/f573de86-7bc7-421c-b44a-c3fcfd97c42e" width="250" alt="Design 7" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/74e4c471-734a-4565-bbba-f1cfa434d7ec" width="250" alt="Design 8" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/34bc1832-c449-4a9c-8f76-36aa2b15dab2" width="250" alt="Design 9" style="border-radius: 12px;" /> |


<div align="center">
  <h2> Final Look </h2>
  <table border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
    <tr>
      <!-- FRONT SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/af85351f-b034-4527-8365-58a60c583a66" width="100%" alt="Front Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Front Side View
        </div>
      </td>
      <!-- SPACER FOR GITHUB MOBILE DEGRADATION -->
      <td width="2%">&nbsp;</td>
      <!-- BACK SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/bf988556-9e94-4161-88da-0bdb663d82c2" width="100%" alt="Back Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Back Side View
        </div>
      </td>
    </tr>
  </table>
</div>
</div>

| Name | Purpose | Qty | Total (USD) | Link | Distributor |
| :--- | :--- | :---: | :---: | :---: | :--- |
| C9,C12 | 1uF 10V X5R ±10% 0402 MLCC | 20 | 0.1220 | [Link](https://lcsc.com/product-detail/C14445.html) | JLCPCB |
| C10,C11,C5,C8,C3,C2,C7,C6,C4,C17,C1,C20,C18 | 0.1uF (100nF) 16V X7R ±10% 0402 MLCC | 75 | 0.5775 | [Link](https://lcsc.com/product-detail/C1525.html) | JLCPCB |
| C13,C14 | 10uF 25V X5R ±10% 0805 MLCC | 20 | 4.3840 | [Link](https://lcsc.com/product-detail/C15850.html) | JLCPCB |
| C16,C15 | 33pF 50V C0G ±5% 0402 MLCC | 20 | 0.1160 | [Link](https://lcsc.com/product-detail/C1562.html) | JLCPCB |
| C19 | 10nF 50V X7R ±10% 0402 MLCC | 20 | 0.1740 | [Link](https://lcsc.com/product-detail/C15195.html) | JLCPCB |
| C21 | 2.2uF 6.3V X5R ±20% 0402 MLCC | 20 | 0.1660 | [Link](https://lcsc.com/product-detail/C12530.html) | JLCPCB |
| D3,D1,D2 | Red Water Clear 0603 LED Indication | 25 | 0.1800 | [Link](https://lcsc.com/product-detail/C2286.html) | JLCPCB |
| J1 | USB Type-C Receptacle 16P Female SMD R/A | 5 | 0.9170 | [Link](https://lcsc.com/product-detail/C165948.html) | JLCPCB |
| R2,R1 | 5.1kΩ 50V 62.5mW Thick Film Resistor ±1% 0402 | 20 | 0.0200 | [Link](https://lcsc.com/product-detail/C25905.html) | JLCPCB |
| R4,R3 | 30Ω 50V 62.5mW Thick Film Resistor ±5% 0402 | 20 | 0.0240 | [Link](https://lcsc.com/product-detail/C137883.html) | JLCPCB |
| R5,R7 | 1kΩ 50V 62.5mW Thick Film Resistor ±1% 0402 | 20 | 0.0820 | [Link](https://lcsc.com/product-detail/C11702.html) | JLCPCB |
| R6 | 10kΩ 50V 62.5mW Thick Film Resistor ±1% 0402 | 20 | 0.0640 | [Link](https://lcsc.com/product-detail/C25744.html) | JLCPCB |
| R10,R9,R8 | 470Ω 50V 62.5mW Thick Film Resistor ±1% 0402 | 25 | 0.0300 | [Link](https://lcsc.com/product-detail/C25117.html) | JLCPCB |
| SW1 | Tactile Switches 12V 50mA Black Button SMD SPST | 9 | 0.4950 | [Link](https://lcsc.com/product-detail/C720477.html) | JLCPCB |
| U1 | RP2040 Microcontroller (MCU) 133MHz LQFN-56 | 5 | 4.9045 | [Link](https://lcsc.com/product-detail/C2040.html) | JLCPCB |
| U2 | MCP1700T-3302E/TT Fixed 3.3V 250mA Linear LDO | 5 | 2.1595 | [Link](https://lcsc.com/product-detail/C39051.html) | JLCPCB |
| U3 | W25Q16JVUXIQ 16Mbit 133MHz SPI NOR FLASH USON-8 | 5 | 7.8745 | [Link](https://lcsc.com/product-detail/C2843335.html) | JLCPCB |
| U4 | ICM-20608-G 6-Axis IMU Accel + Gyro LGA-16 | 2 | 26.3282 | [Link](https://lcsc.com/product-detail/C78569.html) | JLCPCB |
| Y1 | 12MHz 20pF Crystal Oscillator SMD3225-4P | 7 | 0.6972 | [Link](https://lcsc.com/product-detail/C9002.html) | JLCPCB |
| PCB Fabrication (Node_Zero)	| 2-layer PCB — the board itself| 	5	| $2.00 |	—	 | JLCPCB |
| PCBA SMT Assembly|	SMT assembly of all SMD components| 	2| 	$90.95	| —	| JLCPCB |
| Shipping PCB	| E- Post (Cheapest) | 	- |	$11.74	| — | 	JLCPCB |
| Total |    |     |     |   $104.69 |    |   |
