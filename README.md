# ALK8266WIFI

ALK8266WIFI, the Practically Functional, High-Throughput, Stable WIFI module Solution, Very Sutiable for High-Speed 
and bulk data transmission in MCU System to achieve a fast, stable, and effective communication exceeding 1MBytes/s 
  
  https://www.ebay.com/itm/283536362871

1 What is ALK8266WIFI ?

ALK8266WIFI is a high-performance WIFI module with an effective transceiving throughput exceeding 1 Mega-Bytes per second(Mbytes/s), and verified by many mass and long-term deployments. It is a truly High-Speed WIFI module, practically functional, easy-to-integration, stable, and very suitable for MCU system with high-speed and block data transmission. 
Logically it is a converter between an SPI Slave Port and TCP/UDP WIFI packets.

2 What is Application Scenarios of ALK8266WIFI?

ALK8266WIFI module is suitable for “MCU High-Speed WIFI communication”, applications such as Audio/Video WIFI tranceiving, 
High-Speed ADC Sampling and transmission, SD card Bulk File data tranceiving etc. Especially for those MCU platforms which 
have no SDIO/USB but only SPI interface, or DO NOT expect a complex integration of those interfaces,  ALK8266 is a quite 
good choice. 

3 What are features of ALK8266WIFI ?

The solution is a result of the dedicated design with optimization covering module hardware, module firmware, and 
MCU host driver. The module firmware is customized from registers level other than base on Espressif standard SDK
which is mainly proper form slow-speed UART applications. Therefore, it does not have those problems present in 
some traditional modules(e.g. frequent unexpected disconnection, communication halt, missing packets, and lack of 
practical functions). Mass deployment of more than 3 years tells that it is a truly high-speed, stable, flexible, 
and practically functional module solution:

 (1) High Effective Speed, Efficient, and Short-Delay
     > Measured effective speed exceeds Mega Bytes Per secons, capable of fast transmission bulk data such as audio, 
       video, and some other big data.
     > Nealy-RealTime tranceiving with a gap interval less than 1ms or even 10us, in favor of some applications 
       requiring short-delay communications.
     
 (2) Stable with extreamly Low Packet Loss (Actually no packet loss)
     > Reference testing result #1:  In an ordinary office environment with a stable transmission speed of 1MBytes/s, 
       module could run at least 720 hours without any packet loss or errors, no halt and disconnections.
     > Reference testing result #2: In an ordinary office environment, with a stable TCP transmission speed of 
       1MBytes/s for more than 5 hours, then to compare the transmission side and reception side, there is no packet
       missing and the two sides have the same datagram.

  (3) Practically Functional, Versatile and Flexible

     > Flexible and Practical Solution of Wireless Communication
        1  Supporting Multiple Access Infrastructures
           (1) 3 modes: STA-Only, AP-Only, and/or STA+AP
           (2) Communication capability without 3rd-part Access point such as routers
        2  Supporting  Static IP configurations for either AP or STA
        3  Flexible and Practical Socket Capabilities
          (1) Supporting UDP, TCP Client, and TCP Server
          (2) Supporting DNS parsing and the target Socket could be in format of IP or domain
          (3) UDP Supporting Broadcasting , Multicasting, and Unicasting
        4、Supporting Multiple Link Channel and Multiple Clients
          (1) Each Link could be configured independently to be a UDP,  TCP Server, or TCP Client. 
              If configured as TCP Server, able to be connected by multiple clients simultaneously 
        5 Supporting transmission of bulk data (e.g. files) efficiently
        
     > Easy, Flexible and Diverse Network Access Configuration(User interface of STA Access to AP/Routers), 
       Adapted to Various Circumstance
        1 Configured via an on-module WEB Page
          (1) No necessity of additional APP, just use ordinary browser to input directly the SSID and 
              password with barely no prerequisite limitations.
        2 SmartConfig
          (1) Compatible with EspTouch SmartLink SmartConfig
          (2) In favor of WeChat Airkiss SmartConfig
          (3) Available with Configuration Stage Notice to increase the operational convenience and 
              success rate.
        3 Direct Configuration
          (1) Available with SPI Interface to Input SSID and password for access, no need of UART
          (2) Compatible with UART AT commands by Espressif to input the SSID and password directly
    > Available with an On-Module Web Server to extend convenience and flexibilities of some operations
        1 Operations with normal browser, no need of APP installation
        2 Operations on Mobile, Tablet, Laptop, or PC
        3 Adaptive Portal Supported
        4 Directly Network Access Configuration, AP configuration, Socket Configuration, etc.
    > Embedded Encryption and Signature Algorithm
        1 Help to signature MCU codes for anti-copy
    > Supporting Practical and Meaningful Low Power
        1 Low Power Solution with prerequisite of adequate transmission power for adequate distance/speed
        2 Sleep with manual or automatic wake-up, low power consumption to less than 1mA in deep-sleep
        3 Capability of Power-Off and Power-Down, low power consumption less than 1uA
        4 Associated Methods to support quick wake-up, and shorten the WIFI re-connect period, which leads 
          the WIFI Low Power Solution practical and meaningful
        5 Discussion with Customer to support Low Power from point of whole MCU system 

 (4) Dedicated Module Hardware Design

    > Design with Comprehensive Consideration and Technique of Signal Integrity, Power Integrity, and EMCompatibility,
      therefore, stable and no need of shield for a thin package with good heat release and verified by 
      EMC certifications.
    > Factory Radio Frequency Compensation and supporting Frequency auto Calibration.
    > On-Module PCB Antenna in optimized Design, capable to transmission in 100+ meters distance without extern antenna
    > IPEX socket available for an external antenna to extern the communication distance and performance

 (5) Adaptive Package in Small-size
    > Stamp-Style Pins with Full-hole and Half-Hole, standard 2.0-mm pitch
    > Assembly adaptive in Plug-In or SMT
    > Very Small Dimension, Close to the smallest coin
      - With PCB Antenna  L x W = 21 x 18 mm
      - Without PCB Antenna: L x W = 18 x 16 mm

  (6) Ordinary SPI Interface to MCU Host, Easy Integration and very Limited MCU resource occupation

    > Standard SPI Slave Interface to MCU Host, adaptive to most normal MCU chip, providing a wide range of 
      MCU solution selection.
       1 Easy interconnection, only SPI bus required for all operations of configuration, query, and tranceiving, 
        without necessity of UART Port
       2 MCU Host Access WIFI Module in an ordinary SPI manner
    > TCI/IP Protocol Stack already integrated on-module
       1 No need of TCP/IP Protocol Stack or OS integration on MCU Anymore
       2 Therefore Easy Integration of the WIFI module to MCU system with very limited host resources requirement

  (7) Available with many SPI APIs inside the Driver Library
   
    > MCU could call these APIs to configure, query the module and perform high-speed data transmission
    > MCU Host driver integrated with high-speed, high-efficiency, fault-tolerant, failure-correction, 
      environment-adaptive and stable SPI access algorithm, to achieve a high-speed communication with very stable 
      and efficient performance
       1. High-Speed and High-Efficiency Algorithm in favor of a faster tranceiving performance faster than DMA
       2. Balance Algorithm, based on analysis to the local parameters and RF environment, adaptive performing access 
          balance and failure correction to ensure the performance and stalility

  (8) Compatible with Espressif Standard AT Command, and providing Anylinkin extended AT commands
    > UART Baud Rate exceeding 2Mbps

  (9) Available with MCU reference Code Projects Documentations of Datasheet, Integration Reference Manual etc. 

    >  Verified MCU Reference Code Projects
       1 Easy integration, Debug, and Optimization
       2 Scalability Design in levels and easy for Platform
  
    > Lists of MCU Reference Project(Maybe more)

       -------------------------------------------------------------------------------
       |  MCU Vendor                     |                    MCU Part No            |
       |---------------------------------|-------------------------------------------|
       |                                 |  1  STM32 Serials including               |
       |                                 |     - STM32F0xx                           |
       | STMicroelectronics              |     - STM32F1xx                           |
       |                                 |     - STM32F2xx                           |
       |                                 |     - STM32F3xx                           |
       |                                 |     - STM32F4xx                           |
       |                                 |     - STM32F7xx                           |
       |                                 |     - STM32L1xx                           |
       |                                 |     - STM32L4xx                           |
       |                                 |     - STM32H7xx                           |
       |                                 |     - etc.                                |
       |                                 |  2 STM8 Serials                           |
       |---------------------------------|-------------------------------------------|
       |                                 |  1 LPC11xx /LPC17xx                       |
       | NXP / Freescale                 |  2 K27/K28 Serials                        |
       |                                 |  3 K60/KV58 Serials                       |
       |                                 |  4 i.MX RT105x/RT106x Serials             |
       |---------------------------------|-------------------------------------------|
       | TI                              |  1 MSP430 Serials                         |
       |                                 |  2 C2000 Serials e.g. TMS320F28335        |
       |---------------------------------|-------------------------------------------|
       | Holtek                          |  1 HT32 Serials, e.e.HT32F16xx            |
       |---------------------------------|-------------------------------------------|
       | Nuvoton                         |  1 NUC123xx Serials                       |
       |                                 |  2 M45x Serials e.g. M453VE6AE            |
       |---------------------------------|-------------------------------------------|
       | Zhuhai Jieli                    |  1 AD200                                  |
       |---------------------------------|-------------------------------------------|
       | C8051 Serials                   |  1 C8051F12x/ C8051F13x                   |
       |                                 |  2 C8051F34x Serials                      |
       |---------------------------------|-------------------------------------------|
       | More are Comming ....           |                                           |
       |---------------------------------|-------------------------------------------|

   > Measured effective Speeds for Reference

       ---------------------------------------------------------------------------------
       |             | CPU System | SPI Communication |     Measured Speed(Bytes/s)     |
       | MCU Part    |  Frequency |     Frequency     |---------------------------------|
       |             |   (MHz)    |       (MHz)       |      UDP       |     TCP        | 
       |--------------------------------------------------------------------------------|
       | STM32F7xx   |   216      |        27         |   1.4M-1.6M    |    1.2M-1.3M   |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32F4xx   |   168      |        21         |   1.0M-1.2M    |     0.9M-1.0M  |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32F2xx   |   60       |        15         |   750K-800K    |    700K-750K   |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32F1xx   |   72       |        18         |   700K-800K    |    650K-750K   |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32F0xx   |   48       |        12         |   450K-550K    |    400K-500K   |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32L1xx   |   30       |        16         |   600K-700K    |    550K-650K   |
       |-------------|------------|-------------------|----------------|----------------|
       | STM32L4xx   |   80       |        20         |   850K-950K    |    800K-900K   |
       |-------------|------------|-------------------|----------------|----------------|
       | LPC17xx     |   96       |        24         |   800K-900K    |    750K-850K   |
       |-------------|------------|-------------------|----------------|----------------|  
       | iMX RT1502  |   600      |        24         |   1.3M-1.5M    |    1.1M-1.2M   |
       |-------------|------------|-------------------|----------------|----------------|       
       | HT32F16xx   |   72       |        18         |   650K-750K    |    600K-700K   |
       |-------------|------------|-------------------|----------------|----------------|       
       | NUC123xx    |   72       |        18         |   650K-750K    |    600K-700K   |
       |-------------|------------|-------------------|----------------|----------------|       
       | NuMicro M45x|   72       |        18         |   800K-900K    |    750K-850K   |
       |-------------|------------|-------------------|----------------|----------------|       
       | C8051F120   |   98       |        12.25      |   550K-650K    |    500K-600K   |
       --------------|------------|-------------------|----------------|-----------------
       
 (9) Verified by 3+ years Mass Deployment
