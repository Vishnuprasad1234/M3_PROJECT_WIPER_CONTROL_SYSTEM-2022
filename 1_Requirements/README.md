# INTRODUCTION


Car glass that is exposed to dirt or rainwater will usually be cleaned using a wiper. usually, the wiper is attached to the front and rear sides
with the wiper, the driver's view will not be hindered and so they can see clearly towards the front or rear. Wipers do have a very important role
in the safety of the drivers because wiper performance is closely releated to the safety of driving. If it is rains a lot and the car does'nt use wipers
windshield will be dewy. Visible dew on the glass will block the view of the driver. When the driver's view is hindered, the risk of an accident is very 
high. This makes the wipers a very important car enchancement and must be present on all types of vehicles.

# HISTORY


By 1917 John Oeishi formed the Tri-Continental Corporation later to become Trico, one of the largest manufacturers of windshield wipers in the world. 
the windshield wiper had reached mass production phase! By the early 1920s, the hand-cranked wiper had been replaced by a system that uses engine vacuum 
to drive the mechanism. Vacuum Wipers were great, except that their speed would vary according to engine load and speed. By the early 60s vacuum wipers 
were replaced by an electric drive, and in the mid-60s. teh intermittent wiper was invented (and was initially rejected by Ford).

# FEATURES
  1.  It shall lock the car when the button is pressed once
  2.  It shall open the car when the button is pressed twice
  3.  It shall wiper on and it moves clock wise direction and when the button is pressed thrice
  4.  It shall wiper off and it moves anti clock wise direction and when the button is pressed four times
  5.  It shall wiper complete one cycle when the button is pressed five times.

# AIM & OBJECTIVE

* To prevent the accident during rain conditions
* To remove the raindrops, dust, oil or water from the windshield.

# RESEARCH

Application is researched from various resource like from Google, Youtube and research papers and then developed one application model that is Wiper Control System

# END GOALS

* Avoid accidents and prevent safety environment.
* Clean Visions in Winter and rainy seasons.

# SOFTWARE REQUIREMENTS

* STM32 CUBE IDE

# COMPONENTS

* STM32F407VG Microcontroller Board

# DESCRIPTION
## STM32F407VG

The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers capabilities to mak eit simple for users to create audio-based application. 
It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons and USB OTG micro-AB connector. Ethernet connectivity, an LCD Display and other features have been added ti the STM32F4 DISCOVERY kit. the STM32F405xx and STM32F407xx families are built around the high performance Arm cortex -M4 bit RISC core, which runs at up to 168 MHz.

## FEATURES OF STM32F407VG MICROCONTROLLER

* Up to 1 Mbyte of flash memory
* Up to 192+4 Kbytes of SRAM including 64-Kbytes of CCM (Core Coupled Memory) data RAM.
* 512 bytes of OTP memory.
* Flexible static memory controller supporting Compact flash SRAM, PSRAM, NOR and NAND memories


# WORKING PRINCIPLE

Assume that the automobiles is the microcontroller. If the button is hit, the first led (red) will turn on, clicking again the wiper will start and the second led (blue) will turn in for a desired rate. If the button os pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. the microcontroller (vehicle) is turned off after the fifth click.

# USES

* This microcontroller is utilised in printing and scanning machines, heat ventilation, air conditioning and security system.
* This module can be found in a variety of household product.

# 4W'S AND 1H

## WHERE 

* Most of the vehicles have two wipers on the windshield one on the rear windshield and the other on the front windshield. some have a single wiper system.

## WHY

* The main purpose of the wiper system is to clean the wind screen sufficiently to provide clear visibility at all the time.

## WHEN 

* The main purpose is to be clear the winshield from rain, oil, dust and snow. so that we use wiper whenever these things get struck to the windshield.

## WHAT

* Wiper system comprises a wiper drive and two wiper arms at a certain angle across the windshield. it is used to remove the dust, water, oil and snow.

## HOW

* Wiper systems are operated by an electric motor which is attached to a worn gear. It transmits the necessary force to a long rod that sets the wiper arms in motion. The worm gear is able to generate the force required to move the wipers as fast as they need to move.

# SWOT ANALYSIS

## STRENGTH

* Decrease the accidental situation
* Decreases the environmental pollution.
* Decreases the fuel consumption.
* Increase safety
* Capacity increases under shot gaps.

## WEEKNESS

* Limited speed 
* Capacity decreases under conservation gaps.
* cost is high.
* High maintenance.
* Can be frustrating at low penetration rates.

## OPPORTUNITIES

* Technology maturity may reduce system cost.
* Enables novel MTM application.

## THREATS

* User acceptance in terms of both purchase intention and frequent activation after purchase.
* Cost
* MTM delayed adapation.

# DETAIL REQUIREMENTS

## High Level Requirements
| ID | Description | Status |
|--|--|--|
| HR01 |It shall Lock the car  | Implemented |
| HR02 | It shall Unlock the car | Implemented |
| HR03 | It shall Activate Wiper System |  Implemented |
| HR04 | It shall Deactivate Wiper System |  Implemented |


## Low Level Requirements 

| ID | Description |  Status |
|--|--|--|
| LR01 |If the user pressed the Button ONCE - ON LED RED  |  Implemented |
| LR02 | If the user pressed the Button TWICE - OFF LED RED| Implemented |
 LR03 | If the user pressed the Button THREE times - ON BLUE, GREEN, ORANGE | Implemented |
| LR04 | If the user pressed the Button FOUR times - IN ORANGE, GREEN, BLUE | Implemented |


