# nRF52-Beta

Thank you for supporting [RedBear nRF52832 Kickstarter](https://www.kickstarter.com/projects/redbearinc/bluetooth-5-ready-ble-module-nano-2-and-blend-2) campaign.

This private repository is for beta testing, you are invited to join this program and you will be able to try our new materials before we are going to release to the public.

## nRF52832

![image](./docs/images/nRF52832.png)

The nRF52832 BLE SoC combines its ARM processor with a 2.4GHz multiprotocol radio featuring -96 dB RX sensitivity, 512 kB Flash memory, 64 kB RAM and NFC-A tag for “Touch-to-Pair” capability. You can read all [nRF52832 advanced features](https://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF52832) on Nordic's website.

### nRF52 vs nRF51

The nRF51822 runs at 16 MHz only, it is only a Cortex-M0 MCU without DSP and FPU for complicated applications. You will not be able to develop Apple HomeKit projects using nRF51.

## BLE Module (MB-N2)

At the heart of all the new products is our new BLE Module model# MB-N2. It houses the Nordic nRF52832, an on-board antenna and other components special tuning for great performance and low power consumption.

The module provides all GPIO pins and supports all advance features offer by Nordic nRF52832.

With your support, we will get our module certified for CE, FCC and Bluetooth. If you use this module for your own products, not only you have the assurance, you will also save some cost on your own product certifications.

![image](./docs/images/MB-N2/MB-N2.jpg)

If you have a great project idea using this Datasheet for module MB-N2.

## BLE Nano 2

![image](./docs/images/Nano2/Nano2.png)

We launched our first BLE Nano in 2014 and it is our most popular product. We design Nano 2 as a ‘drop-in’ replacement, with exactly the same form factor, and in most instances no need to change firmware code. In addition, the new development board also offers a U.FL connector for an external NFC antenna, while users will benefit from the extra processing power and hardware resources of the nRF52832 SoC.

![image](./docs/images/Nano2/Nano2_Pinout.png)

### DAPLink

This board has an ARM Cortex-M3 MCU and is used to program and debug an application running on Nano 2 via SWD. DAPLink is an open source project by ARM mbed team, more about DAPLink.

![image](./docs/images/DAPLink/DAPLink_Pinout.jpg)

### Proto Board

![image](./docs/images/Nano2/ProtoBoard.jpg)

We design this new Proto Board for you to get started easily. You can power your Nano via coin cell battery, rechargeable battery or USB. The top part could be removed if you don't need it. It has 3 connectors for Seeed's Grove modules (more details below). Last but not least, we have reserved a place for the Apple MFi authentication coprocessor; you can develop BLE HomeKit product if you have the MFi license. 

## Blend 2

Our Blend is very popular as it is a "full-size" Arduino compatible board which supports most shields. It has on board a Cortex-M3 MCU that supports DAPLink, slot for Apple MFi coprocessor and two Grove connectors.

You should choose the Blend 2 if you want to test all GPIOs and functions available on the Nordic nRF52832 SoC. 

![image](./docs/images/Blend2/Blend2_Pinout.png)

## Resoureces

* Documentations
	* Getting Started Guide
* Nordic nRF52832 Datasheet
* MB-N2 Datasheet







