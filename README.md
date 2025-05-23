# OpenBook

<img width="563" alt="image" src="https://github.com/user-attachments/assets/102450b4-6cf1-49df-a531-43487337a72f" />


## Prezentare generala

Proiectul a fost realizat in cadrul disciplinei _Testarea Sistemelor de Calcul_ si isi propune crearea unui model 3D detaliat pentru o tableta E-Book Reader. Am proiectat atat la nivel de circuit, cat si la nivel de design al produsului, folosind programul _Fusion360_ de la Autodesk.

## Block Diagram
<img width="482" alt="Screenshot 2025-04-14 210347" src="https://github.com/user-attachments/assets/94e36bda-335d-41fa-b137-9727f6364365" />


## Bill of Materials
| Device | Description | Datasheet | Price per Unit | Link |
|----------------------|--------------------------------------|-----------|-----------|------|
| ADAFRUIT_LEDCHIP-LED0603 | LED | [datasheet](https://ro.mouser.com/datasheet/2/423/LSM0603412V-1379745.pdf) | 1,50 RON | [link](https://ro.mouser.com/ProductDetail/VCC/LSM0603412V?qs=sGAEpiMZZMt82OzCyDsLFG1ehM2%252BdxqbAopHlSxILTc%3D) |
| SJ | SMD solder JUMPER | [datasheet](https://www.farnell.com/datasheets/2813407.pdf) | 0,01 RON | [link](https://ro.farnell.com/panasonic/erj3gey0r00v/res-0r0-0-1w-0603-thick-film/dp/2059527) |
| ESP32_WROVER_EAGLE-LTSPICE_RR0402 | RESISTOR, European symbol | [datasheet](https://www.vishay.com/doc?28700) | 0,941 RON | [link](https://ro.mouser.com/ProductDetail/Vishay-Beyschlag/MCS04020D9101BE000?qs=sGAEpiMZZMvdGkrng054twKDKoBh%252BscnK%2FuqkNk9X%252BqO%2Fz5%2F0u93Ow%3D%3D) |
| 112A-TAAR-R03_ATTEND | Micro SD Card Socket, Push-Push Type, Top Mount, SMT, H=1.83mm, 10u | [datasheet](https://www.attend.com.tw/data/download/file/112A-TAAR-R03.pdf) | 1,54 RON | [link](https://www.soselectronic.com/ro-ro/products/attend/112a-taar-r03-116052) |
| EAGLE-LTSPICE_CC0402 | CAPACITOR, European symbol | [datasheet](https://ro.mouser.com/datasheet/2/40/Accu_P-3077555.pdf) | 5,74 RON | [link](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/04025J0R5ZBSTR?qs=k4kUdCzLgS7v2DzbDWDPRw%3D%3D) |
| ESP32_WROVER_SPARKFUN-DISCRETESEMI_MOSFET_PCH-DMG2305UX-7 | P-channel MOSFETs | [datasheet](https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf) | 0,941 RON | [link](https://ro.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7?qs=L1DZKBg7t5F%2FNBHrjfxC%252Bg%3D%3D) |
| 744043680IND_4828-WE-TPC_WRE | | [datasheet](https://www.we-online.com/components/products/datasheet/744043680.pdf) | 6,44 RON | [link](https://ro.mouser.com/ProductDetail/Wurth-Elektronik/744043680?qs=PGXP4M47uW6VkZq%252BkzjrHA%3D%3D)|
| BD5229G-TR | Voltage Detector with Adjustable Delay Time | [datasheet](https://datasheet.datasheetarchive.com/originals/distributors/Datasheets_SAMA/f2b9741ef86007909f138d561a359946.pdf) | 3,72 RON | [link](https://ro.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR?qs=4kLU8WoGk0vvnhrrYwdszw%3D%3D) |
| CPH3225A | Cap 0.011F 3.3V 1210 Flat | [datasheet](https://ro.mouser.com/datasheet/2/360/Seiko_Instruments_MicroBattery_E_20230330_2024Jan_-3561061.pdf) | 11,04 RON | [link](https://ro.mouser.com/ProductDetail/Seiko-Semiconductors/CPH3225A?qs=3etwrb1wR%252BhUOph6lAO7eg%3D%3D) | 
| DS3231SN# | Real Time Clock Serial 16-Pin SOIC W T/R | [datasheet](https://ro.mouser.com/datasheet/2/609/DS3231-3421123.pdf) | 73,80 RON | [link](https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/DS3231SN?qs=1eQvB6Dk1vhUlr8%2FOrV0Fw%3D%3D) |
| ESP32-C6-WROOM-1-N8 | | [datasheet](https://ro.mouser.com/datasheet/2/891/Espressif_ESP32_C6_WROOM_1__Datasheet_V0_1_PRELIMI-3239987.pdf) | 14,70 RON | [link](https://ro.mouser.com/ProductDetail/Espressif-Systems/ESP32-C6-WROOM-1-N8?qs=8Wlm6%252BaMh8ST02Gmwp74cw%3D%3D) |
| ESP32_WROVER_AVX---SD0805S020S1R0_AVX_ SD0805S020S1R0_0_0AVX_SD0805S020S1R0_0_0 | Schottky Barrier Rectifier Diode | [datasheet](http://datasheets.avx.com/schottky.pdf) | 1,46 RON | [link](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) |
| ESP32_WROVER_BME680_BME680 | Integrated Environmental Unit | [datasheet](https://ro.mouser.com/datasheet/2/783/BST_BME680_DS001-1509608.pdf) | 40,69 RON | [link](https://ro.mouser.com/ProductDetail/Bosch-Sensortec/BME680?qs=v271MhAjFHjo0yA%2FC4OnDQ%3D%3D) |
| ESP32_WROVER_SPARKFUN-IC-POWER_MCP73831 | MCP73831T Li-Ion, Li-Pol Controller | [datasheet](https://ro.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf) | 3,57 RON | [link](https://ro.mouser.com/ProductDetail/Microchip-Technology/MCP73831T-4ADI-OT?qs=hH%252BOa0VZEiBTiqxSV9eepQ%3D%3D) |
| FH34SRJ-24S-0.5SH_99_ |  (0.50mm) Surface Mount, Right Angle | [datasheet](https://ro.mouser.com/datasheet/2/185/FH34SRJ_24S_0_5SH_99__CL0580_1255_6_99_2DDrawing_0-1615044.pdf) | 12,87 RON | [link](https://ro.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH99?qs=vcbW%252B4%252BSTIpKBl5ap9J8Fw%3D%3D) |
| MAX17048G+T10 |  | [datasheet](https://ro.mouser.com/datasheet/2/609/MAX17048_MAX17049-3469099.pdf) | 21,19 RON | [link](https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G%2bT10?qs=D7PJwyCwLAoGnnn8jEPRBQ%3D%3D) |
| MBR0530 | ON SEMICONDUCTOR - MBR0530 - DIODE, SCHOTTKY, 0.5A, 30V, SOD-123 | [datasheet](https://www.onsemi.com/PowerSolutions/product.do?id=MBR0530T3G) | 0,89 RON | [link](https://ro.mouser.com/ProductDetail/onsemi/MBR0530T3G?qs=3JMERSakebpEmdUS6GetdQ%3D%3D) |
| PGB1010603MR |  | [datasheet](https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321) | 1,98 RON | [link](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) |
| QWIIC_CONNECTORJS-1MM | SparkFun I2C Standard Qwiic Connector | [datasheet](https://ro.mouser.com/datasheet/2/813/Qwiic_Connector_Datasheet-1223982.pdf) | 2,75 RON | [link](https://ro.mouser.com/ProductDetail/SparkFun/PRT-14417?qs=wd5RIQLrsJhgdz%2FpmZ%2F3GQ%3D%3D) |
| SAMACSYS_PARTS_USB4110-GF-A | CONN USB 2.0 TYPE-C R/A SMT | [datasheet](https://ro.mouser.com/datasheet/2/837/GCT_USB4110_Product_Drawing___20k_cycles-3455479.pdf) | 5,84 RON | [link](https://ro.mouser.com/ProductDetail/GCT/USB4110-GF-A?qs=KUoIvG%2F9IlYiZvIXQjyJeA%3D%3D) |
| SI1308EDL-T1-GE3 | MOSFET N-Ch 30V 1.5A TrenchFET SC70 Vishay Si1308EDL-T1-GE3 N-channel MOSFET Transistor, 1.5 A, 30 V, 3-Pin SC-70 | [datasheet](https://www.vishay.com/doc?63399) | 2,07 RON | [link](https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/SI1308EDL-T1-GE3?qs=bX1%252BNvsK%2FBramh9tgpOaEw%3D%3D) |
| USBLC6-2SC6Y | Low Cap. ESD Protection Auto SOT-23-6 STMicroelectronics  | [datasheet](https://ro.mouser.com/datasheet/2/389/usblc6_2sc6y-1852505.pdf) | 2,16 RON | [link](https://ro.mouser.com/ProductDetail/STMicroelectronics/USBLC6-2SC6Y?qs=gNDSiZmRJS%2FOgDexvXkdow%3D%3D) |
| W25Q512JVEIQ |  | [datasheet](https://ro.mouser.com/datasheet/2/949/Winbond_W25Q512JV_Datasheet-3240039.pdf) | 28,91 RON | [link](https://ro.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ?qs=l7cgNqFNU1jw6svr3at6tA%3D%3D) |
| XC6220A331MR-G | LDO Voltage Regulators | [datasheet](https://ro.mouser.com/datasheet/2/760/xc6220-3371556.pdf) | 7,23 RON | [link](https://ro.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G?qs=AsjdqWjXhJ8ZSWznL1J0gg%3D%3D) |

## Functionalitate hardware
Componentele principale ale circuitului sunt:

+ USB C Connector + ESD Protection
  
 > destinat alimentarii E-Book, se conecteaza prin interfata USB
 
+ SD Card
 
 > Secure Digital Card este folosit ca si mediu de stocare pentru cartile in format electronic; lucreaza la 3.3V si se conecteaza cu microcontrollerul prin interfata SPI
 
+ E-Paper Display, impreuna cu modulele aferente - E-Paper Drive Circuit, E-Paper Display Header, EPD Power
  
> EPD Header se conecteaza prin interfata SPI la microcontroller, si realizeaza legatura intre celelalte componente
> EPD Power furnizeaza tensiuni multiple, iar E-Paper Drive Circuit genereaza semnalele necesare pentru controlul display-ului E-Paper
>
> display-ul consuma cel mai mult la refresh, 30mA daca este alb-negru si pana la 60mA pentru display color, iar in modul inactiv, dupa ce a afisat imaginea, consumul este chiar zero
 
+ Environmental Sensor BME688
  
 > este un senzor de mediu ce poate masura temperatura, umiditatea, presiunea atmosferica si calitatea aerului, care functioneaza la 3.3V si se conecteaza prin interfata I2C
>
> are un consum redus, in standby sub 1uA, iar pentru masurare foloseste intre 1-2mA

+ RTC Module DS3231SN
  
 > este un modul Real-Time Clock care are rolul de a pastra data si ora curenta atunci cand microcontroller-ul este oprit; poate functiona pe baterie, si are un cristal de 32KHz integrat; se conecteaza la ESP32-C6 prin I2C, folosind pinii SCL si SDA
>
> consumul sau tipic variaza de la 150uA, atunci cand este alimentat de la sursa principala, si scade la 1uA la trecerea pe baterie

+ External NOR Flash 64MB
  
> extinde memoria microcontroller-ului, aici se stocheaza date suplimentare, se poate face si o stocare temporara; foloseste interfata SPI
> 
> contributia sa la consumul energetic total este foarte mica; cel mai mult se consuma la stergerea din flash (in jur de 50mA), respectiv la scriere (30-50mA); in standby se consuma numai 10-20uA

+	LDO Voltage Regulator
  
> este un stabilizator de tensiune liniar, care asigura tensiunea de iesire constanta la valoarea de 3.3V pentru microcontroller;
>
> are un consum energetic foarte mic (in jur de 8uA atunci cand este activ), ceea ce il face ideal pentru dispozitive alimentate pe baza de baterie, precum cel de fata

+ Voltage Supervisor
  
> folosit pentru monitorizeaza nivelului tensiunii, si pentru a asigura ca sistemul nu poate porni atunci cand avem o tensiune instabila sau mult prea mica

+ Qwiic/Stemma QT
  
> simplifica atasarea senzorilor si perifericelor la microcontroller, facand posibila conectarea mai multor dispozitive in lant, fara a fi nevoie de fire distincte pentru fiecare semnal; functioneaza pe baza protocolului I2C

+ Li-Po Battery Controller

> gestioneaza incarcarea/descarcarea bateriei, regland constant tensiunea si curentul;  la alimentarea bateriei, previne supraincarcarea , iar la descarcare monitorizeaza tensiunea pentru a evita descarcarea profunda; este conectat la sursa de alimentare si la baterie

## Microcontroller - ESP32-C6
Intreg circuitul a fost conceput in jurul microcontrollerului ESP32-C6-WROOM, care este un modul preasamblat, si principalul consumator energetic al circuitului. Consumul mediu se situeaza undeva intre 100uA si 2mA, avand in vedere ca in modul _Activ_ se consuma in jur de 100-120mA, in _Idle_ 10-15mA iar atunci cand se afla in _Deep Sleep_ doar 10-20uA. In mod evident, consumul depinde cel mai mult de durata sesiunilor active.
> Placa ESP-WROOM-32 dispune de o varietate de interfete pentru conectarea altor componente si senzori, inclusiv pini de I/O, SPI, I2C si UART. Aceastea faciliteaza integrarea si extind gama de aplicatii posibile. Placa foloseste WiFi 6 2.4 GHz, are integrat Bluetooth 5 si antena.
>> <img width="600" alt="ESP32_C6" src="https://github.com/user-attachments/assets/733b906e-1500-4ca2-ba0b-447412d6c4e2" />
> ESP32-C6 se leaga de cele mai importante module ale circuitului prin intermediul pinilor sai:
> - **Alimentare si reset**
>> **3V3** asigura alimentrea modulului, **GND** legatura la masa, **EN** trebuie sa fie pe pozitia _HIGH_ pentru ca modulul sa functioneze (EN va fi controlat de catre butonul RESET)
> - **USB C Connector**
>> deoarece ESP32-C6 are USB nativ, conexiunea se realizeaza direct prin liniile de date **USB_D+** si **USB_D-**, la pinii **GPIO13** si **GPIO14** ai modulului; nu mai este deci nevoie de un convertor serial extern
> - **SD Card**
>> pentru a comunica cu dispozitive rapide precum SD Card se foloseste interfata SPI(Serial Peripheral Interface), folosind pinii **GPIO27(MISO)** - pentru transfer de la card la ESP, **GPIO7(MOSI)** - pentru transfer invers, **GPIO6(SCK)** -semnalul de ceas care asigura sincronizarea, respectiv **GPIO4(SS_SD)** - chip select
> - **E-Paper Display**
>> pentru conexiunea si controlul ecranului dispozitivului se folosesc pinii **GPIO11(EPD_CS)** - Chip Select pentru display-ul EPD, **GPIO5(EPD_DC)** - pentru controlul display-ului, **GPIO21(EPD_RST)** - pentru resetarea display-ului, respectiv **GPIO26(EPD_BUSY)**
> - **Environmental Sensor BME688**
>> avand in vedere ca se face comunicatia cu senzorul prin intermediul protocolului I2C, pentru stabilirea legaturii se vor folosi pinii **GPIO19(SDA)**, **GPIO20(SCL)** si **GPIO17(I2C_PW)** de pe microcontroller
> - **UART(Serial Communication)**
>> ESP32-C6 are si interfete seriale, utile pentru debugging sau conexiuni cu alte dispozitive; pinii aferenti comunicarii UART sunt **TXD0** -pentru transmisia datelor respectiv **RXD0** - pentru receptie de date
> - **Restul pinilor**
>> - **FLASH_CS** este un pin Chip Select pentru selectarea chipului flash extern (pentru comunicarea SPI cu External NOR Flash)
>> - **IO/BOOT** folosit pentru a intra in boot mode – legatura cu butonul de _boot_
>> - **RTC_PWM** pentru semnale Pulse Width Modulation trimise catre Real Time Clock
>> - **RTC_RST** pentru resetarea ceasului
>> - **INT_RTC** destinat semnalelor de intrerupere de la modulul RTC, de exemplu in cazul iesirii din moduri de functionare (sleep), pentru executarea unor sarcini periodice, cum ar fi un refresh al display-ului etc.

## Amplasarea componentelor / Reguli de design

La design-ul PCB-ului am tinut cont de cateva aspecte importante in ceea ce priveste amplasarea componentelor pe placuta. Astfel:

+ **Microcontroller-ul ESP32** se afla in marginea de sus a PCB-ului, cu antena inspre exterior si cu PCB-ul decupat in aceasta zona, pentru ca antena sa nu fie blocata si pentru a se evita orice interferente
+ **Conectorul USB** se afla in partea de jos a placutei, centrat astfel incat sa se alinieze cu orificiul din carcasa si sa permita conectarea mufei USB-C
+ **E-Paper Display Header** este pozitionat pe lateral, iar in dreptul sau exista un decupaj in PCB - acesta este spatiul in care se va introduce ribbon-ul display-ului nostru
+  **Conectorul Qwiic** e amplasat pe marginea PCB-ului, si s-a lasat suficient spatiu in jurul sau, pentru a permite conectarea facila a unor cabluri suplimentare
+  PCB-ul este decupat intr-o zona suficient de mare in care sa incapa si bateria device-ului
## Errors

La editarea PCB-ului in Fusion 360 am intampinat urmatoarele erori:
<img width="600" alt="errors" src="https://github.com/user-attachments/assets/13f76178-e6c5-4af7-bdd7-0c7c476f3f09" />

Erorile au aparut din cauza dimensiunii gaurilor din mufa USB, asa ca le-am aprobat pe amandoua.



