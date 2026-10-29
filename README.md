# LoraModule-Project-PCB
An ultra cheap pcb I created for combining an ESP32S3 Supermini and a wide variety of Lora SMD chips such as the RA-01SH, this design is not meant to be used as a relay/Transmission node for extended periods of time due to the strain on the esp32s internal voltage converter, while it will function and do so quite decently, my other project is much better built for this while being only mildly more expensive. 

WARNING- DO NOT USE WITH RA-01SH-P, The P model is a higher drain edition of the module im using specially made for transmiting, it draws about 1A (at +31 Dbm) and would fry the esp if used with this pcb and it also has a different pinout, it includes a vccpa pin which accepts 5v directly for a higher transmit power. In summary, check the max draw and ensure its around 300-400 Milliamps at most.

I ordered my pcb from pcbway, it cost me around 5 euro for 5 of them and delivery was quite cheap, so if anyone wants to replicate it, its not too expensive.

The RA chips can be found on aliexpress for around 3 euro each and the s3 supermini is around 2 euro if bought directly from the maker on aliexpress

## Compatibility Notes
* **LoRa Modules:** Many other RA-xxx chips share the same footprint but ensure to check this for yourself

* **Microcontrollers:** Along with this, the supermini s3 shares a footprint with many other superminis, but once again this is at user discretion and some code modification may be needed, but as far as i know they should be similar enough to work almost without any issues.

<img width="1724" height="938" alt="esp32s3_lora" src="https://github.com/user-attachments/assets/712de768-6e0d-4332-83fa-d5160585e3b4" />


<img width="742" height="551" alt="image" src="https://github.com/user-attachments/assets/94ee744a-619b-44a4-ade6-f37950b56372" />

<img width="1210" height="386" alt="image" src="https://github.com/user-attachments/assets/15b2e362-31d6-468a-bb6b-b00448c778b6" />
