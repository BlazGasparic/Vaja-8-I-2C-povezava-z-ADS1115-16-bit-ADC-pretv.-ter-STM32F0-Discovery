# Vaja-8-I-2C-povezava-z-ADS1115-16-bit-ADC-pretv.-ter-STM32F0-Discovery

Vprašanja in odgovori


c) V kategoriji Connectivity izberite in omogočite I2C komunikacijo. Kateri pini se aktivirajo? Koliko različnih I2C komunikacij vaša razvojna plošča omogoča?

pina PB6 in PB7, to omogoča 2 rezlični komunikaciji 


e) Sedaj ADS1115 modul povežite z ustreznimi pini na STM32F0. Ne pozabite na upore in kondenzator. 
Katere pine ste izbrali?

SCL -> SCL   
SDA -> SDA
ADDR -> GND
ALRT -> ni povezan
VDD -> 5 V ali 3.3 V


f) V Parameter Settings protokola I2C spremenite Speed Mode na Fast. Koliko znaša sedaj frekvenca?

400 kHz


b) Pretvorite binarni naslov 1001000 v šastnajstiškega:

48 HEX

e) ADS pretvorniku moramo programsko nastaviti vhodno ojačanje v konfiguracijskem registru
(programmable gain amplifier configuration). Ker so naše vrednosti na potenciometru do 3.3 V, moramo 
ustrezno postaviti 16 bitni register tako, da bo lahko meril to vrednost. Bite od 11:9 postavimo na 000, 
zato je max. napetost ± __.____V. 

±6.144V





