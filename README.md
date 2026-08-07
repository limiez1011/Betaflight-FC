# yecnod F405 V1.1

## Description

open-source (not that anyone would want to use it) 40x40 F405 Flight controller using betaflight software.
## Features

- 3 Universal UARTS
- Dedicated pads for analog VTX
- 9V and 5V Buck converters
- 2x 3.3V LDOS
- Integrated barometer
- LDO and Buck converter status LEDS
- 16MB Blackbox flash
- Full betaflight support
- ICM 42688-P (kind of a flex with how hard they are to get nowadays)
- 4V5 Pads for RX

This is the first revision of the yecnodF405 so expect more features on the 2nd.

[Schematic PDF](https://github.com/user-attachments/files/29501861/20x20.fc.pdf)

## COST

- AROUND 60 USD PER PCB
- AROUND 30 USD FOR 5 PCBS

On my next revision I will try to cut the costs by atleast 40%

## BOM

|   | NAME        | PURPOSE                                | QTY | PRICE  | LINK                                                                                                                                                                                                                                                                                        |
|---|-------------|----------------------------------------|-----|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | LCSC        | PASSIVES/ALL IC'S                      | 1   | $73.43 | [LINK](https://www.lcsc.com)                                                                                                                                                                                                                                                                |
| 2 | HOT AIR GUN | SOLDERING                              | 1   | $35    | [LINK](https://www.emag.ro/fier-de-lipit-torta-cu-aer-cald-yihua-8858-iv-a5dc-582e4/pd/D3JM2VYBM/?ref=graph_profiled_similar_fallback_1_5&provider=rec&recid=rec_49_08c7c992410847fca068c8fe31b8623d8bb9a36b783f82e050163eaf2f512421_1786099721&scenario_ID=49)                             |
| 3 | MP4420      | BUCK CONVERTER (NOT AVAILABLE ON LCSC) | 10  | $7.7   | [LINK](https://www.aliexpress.com/item/1005009928983923.html?spm=a2g0o.cart.0.0.2e1938damlvGFl&mp=1)                                                                                                                                                                                        |
| 4 | TWEEZERS    | HELP FOR SOLDERING TINY 0402           | 2   | $16.5  | [LINK](https://www.aliexpress.com/item/1005007691201333.html?spm=a2g0o.cart.0.0.2e1938damlvGFl&mp=1&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D) [LINK](https://www.aliexpress.com/item/1005008389644631.html?spm=a2g0o.cart.0.0.2e1938damlvGFl&mp=1) |
| 5 | FLUX        | SOLDERING                              | 1   | $11.2  | [LINK](https://www.aliexpress.com/item/1005008666080401.html?spm=a2g0o.cart.0.0.2e1938damlvGFl&mp=1)                                                                                                                                                                                        |
| 6 | C245 TIP    | SOLDERING                              | 1   | $7     | [LINK](https://www.aliexpress.com/item/1005008666080401.html?spm=a2g0o.cart.0.0.2e1938damlvGFl&mp=1)                                                                                                                                                                                        |
| 7 | JLCPCB      | PCBS                                   | 5   | $12.71 | [LINK](https://jlcpcb.com/)                                                                                                                                                                                                                                                                 |
| 8 | TARIFFS     | dumb eu laws                           | 1   | $41    |                                                                                                                                                                                                                                                                                             |

## Notes

- This is my 2nd ever electronics project (Although I made another 3 during the break I took on this project) so don't expect everything to be electrically sound, this has been a great learning experience though, even with all the headaches it gave me.
- The jlcpcb BOM is only partly complete since I've decided to not use PCBA (use at you own risk some parts may not be right)

## Photos
<img width="1228" height="852" alt="Screenshot 2026-06-30 133439" src="https://github.com/user-attachments/assets/946c2508-b674-4126-abb3-77c46141a56d" />
<img width="1051" height="777" alt="Screenshot 2026-06-30 133509" src="https://github.com/user-attachments/assets/cd058bd5-a491-46fc-a592-ff07f0b2fe1c" />
<img width="641" height="654" alt="image" src="https://github.com/user-attachments/assets/d846d424-fab3-4289-895c-4f54548c8789" />
<img width="1140" height="1072" alt="image" src="https://github.com/user-attachments/assets/e5eff88b-3744-4156-a4e1-31f9d1a22271" />
<img width="1950" height="1370" alt="image" src="https://github.com/user-attachments/assets/596ec015-b1d5-4080-9dd2-f341188171a8" />
