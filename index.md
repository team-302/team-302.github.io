---
title: Check point 1
---

# Weather Protective Cover
* Team 302
* 4/28/2023
* ASU EGR 314: Embedded Sys Design Project II
* Prof. Kelley

## Table of Content
* Introduction
* Presentation
<details open>
<summary>expand</summary>
<br>
* Team Organization
  <br>
* User needs, Benchmarking, and Requirement
  <br>
* Design Ideation
  <br>
* Selected Design
  <br>
* Block Diagram
  <br>
* Component Selection
  <br>
* MicroController Selection
  <br>
* Hardware Proposal
  <br>
* Software Proposal
  <br>
* Power Budget
  <br>
* Appendex
  <br>
</details>



## Presentation

<iframe width="560" height="315" src="https://www.youtube.com/embed/XPlsDYkBCSw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Introduction
Every year in the United States there are at least 10,000 storms that have hail big enough to damage solar panels. With the growth of solar panels, the risk of them getting damaged by these hail storms and other debris increases. Team 302's goal is to be able to sovle this issue.

![](solarPanel1.jpg)
![](solarPanel2.jpg)

## Team Organization
Hailstorms and other debris can be a significant threat to the integrity of solar panels, leading to substantial damage and financial losses. With the rise in the use of solar panels across the United States, the risk of damage caused by hail and other debris is also increasing. According to recent estimates, there are at least 10,000 storms every year in the United States that produce hail large enough to cause damage to solar panels. This underscores the need for effective solutions that can mitigate the damage caused by these storms and debris.

In light of these challenges, Team 302 aims to develop innovative solutions to address this issue. They recognize that developing a solution that can effectively protect solar panels from damage caused by hail and other debris is critical to ensuring the longevity and reliability of solar panels. Their efforts could significantly reduce the risks and costs associated with the maintenance and repair of solar panels, while also increasing their overall efficiency.
[Our charter](/team-302-team-charter.md)


## User needs, Benchmarking, and Requirements



After establishing the organization, team 302 realized the importance of understanding user needs in developing successful products. To achieve this, the team gathered eight different products that are similar to their target products and can be used to benchmark existing products. By benchmarking, the team was able to evaluate and compare the features of their target products to the market competitors, which provided insights into the strengths and weaknesses of their target products.

Through the benchmarking process, the team also gathered user needs by analyzing the reviews of the benchmarked products. This helped the team to understand the key requirements of their potential customers and what they expect from similar products.

Once the team had gathered enough user needs, they grouped them into three categories based on the constraints that they faced. These categories were installation and use, longevity, and other related device standards. By grouping the user needs, the team was able to focus on specific areas and prioritize the requirements that were most important to their target customers.

The installation and use category focused on the ease of setting up and using the product. The longevity category focused on the durability and lifespan of the product. Finally, the other related device standards category focused on the compatibility and integration of the product with other devices in the market.

By sorting the user needs into these three categories, the team was able to ensure that they were addressing the most critical requirements of their target customers while considering the constraints that they had to work with. This approach helped the team to develop a product that not only met the user needs but also aligned with their organization's goals and objectives.



[link to user needs, Benchmarking, and Requirements](/User-Needs.md)

## Design Ideation

During our brainstorming session, every team member generated 25 ideas based on their own insights, observations from benchmarking, and suggestions from other team members. We utilized a jamboard to compile and display these ideas, ensuring that every team member could view all of them. Subsequently, we merged compatible ideas together while taking into account the relevant constraints, ultimately resulting in three distinct designs.

The Solar panel protection design, by Tyler Winder.

The Weather Station Glider design, by Tilak Rai Thanga Rai.

The Automated AC Unit Cover design, by Jose Nava-Mesina.

[link to design ideation](/design-ideation.md)


## Selected Design

We opted for the solar panel protector as our chosen design. This design comprises a self-contained unit that is installed adjacent to the solar panel. When it detects weather conditions that are likely to cause strong winds or hail, the device will activate a motor to unfurl a protective covering over the solar panel, safeguarding it against damage from hail, rain, and other storm debris. Additionally, the unit has a retractable lid that shields the sensors from the elements. The lid will raise every hour, allowing the sensors to assess the weather conditions before closing again. The design of this protector is depicted below.


![](Selected_design.png)

[Link](/Selected_design.png)

## Block Diagram

After selecting the design the team then broke down the design into subsystems and created the following block diagram.

![](newBlockDiagram.png)

[Link](/Block_Diagram.jpg)

## Component Selection

The team researched the different components that would be needed for making this product.

**Wind Sensor**

* ADC: ADC081C027
* This ADC has the best input voltage range, temperature range, is the cheapest of the three, and has a higher sample rate of 189 kSPS.

![](photo_component/image3.png)

* Op Amp: OPA2310IDR
* The reason we are choosing this one is that it has a lower input offset voltage, a higher bandwidth, a rail-to-rail input and output, and a lower power consumption.

![](photo_component/image11.png)

* DC Generator: MM10 DC Motor
* This product is currently available to us for free, has a higher torque output, has a higher efficiency rating, is designed for continuous use.

![](photo_component/image18.png)

**Barometric Pressure Sensor**

*  Barometric Pressure Sensor: KP253XTMA2
*  The KP253XTMA2 is a piezoresistive pressure sensor with a wide pressure range and a high accuracy. It is designed for harsh environments and can operate at temperatures ranging from -40°C to 125°C.

![](photo_component/KP235XTMA2 pic.jpg)

**Voltage Regulator**

* Voltage Regulator: LM2596S-3.3/NOPB
* Best choice in terms of operation and for what our design needs. May be a bit on the expensive side but it covers all the bases where some of the other components fall a bit short with good stock availability. It also has a high efficiency (up to 85%) and can operate over a wide input voltage range (4.5V to 40V).

![](photo_component/image6.png)

**Motor System**

* Motor Driver: IFX9201SGAUMA1
* The IFX9201SGAUMA1 is a highly integrated H bridge driver that provides a number of benefits, such as high efficiency, low power consumption, and high reliability. It also has built-in protection features such as over-temperature protection, over-voltage protection, and short-circuit protection.

![](photo_component/image1.png)


[Link to the full component selection](/Component_Selection_Team_302.md)

## Microcontroller Selection

After reviewing and studying the different Microcontrollers that were available to the team they decided to go with the PIC18F27Q10. They choose this pic because it has a higher maximum operating frequency of 64 MHz, has a larger program memory of 128 KB, and has a higher number of input/output (I/O) pins.
![](PIC18F27Q10-N2X-Regular.jpg)

[Link to the full Microcontroller Selection](microcontroller-selection-table-team-302.md)

## Hardware Proposal

The team created the following schematics for the following subsystems based on the subsystems created in the block diagram.

**Actuator Subsystem**

![](Actuator_subsystem2.png)

[Link](/Actuator_subsystem2.png)

**Barometric Pressure Sensor**

![](Barometric_Pressure_sensor3.png)

[Link](/Barometric_Pressure_sensor3.png)

**Wind Sensor**

![](temp.png)

[Link](/temp.png)

**MicroController and Voltage Regulator**

![](Micro.png)

[Link](/Micro.png)

**ESP32**

![](esp32.png)

[Link](/esp32.png)

**Full team Schematic**
![](fin.png)

[Link](/fin.png)

## Software Proposal

We will be using Mplab and MCC to program our microcontroller.

![](newSoftware.png)

[Link](/Software_Proposal2.jpg)

## Power Budget

[Link](/Power_Budget-Power_Budget.md)

## appendix
[appendix](/team-302-team-charter.md)
