---
name: Data Acquisition and Safety System for EV
tools: [Microcontrollers, Python, C++]
image: https://storage.googleapis.com/gd-wagtail-prod-assets/original_images/material_design_awards_inline_002.jpg
description: Embedded Systems Engineering
# external_url: https://thefabulous.co/
---

# CEV 
During the academic semester, I am part of a team building an awesome EV that competes in the annual _Shell Eco Marathon_. Find our website [here](https://www.cornellelectricvehicles.org/)

Over the past two years, I have 

{% capture carousel_images %}
https://bit.ly/2BBbVhc
https://bit.ly/2DOtxXB
{% endcapture %}
{% include elements/carousel.html %}
### Data Acquisition 

Researched feasibility of concept, prototyped from scratch and integrated car-mounted sensors such as Rotary encoder for steering, RPM, IMU, etc. Involved implementation of CAN, UART, SPI protocols for comparing various possible set-ups. I also implemented multi-threading on a Pi Pico to enable simulataneous RPM conversions and data transfer. Currrently working on scaling system to more than 15 sensors with accurate and low-latency data collection. <br>
I lead a team of two peers while developing this system and liased with leads of other vehicle sub-systems to ensure proper specifications and meeting competition requirements. 

### Auxilliary Board and System Integration
Designed and built a complete Wiring harness system to enable easy access to critical car systems during competition. Prototyped several sub-systems: lighting, horn, emergency stop, braking, etc as part of safety system design. Co-designed updated PCB based on team design requirements. 

{% include elements/figure.html image= "assets\CEV_Wiring_Schematic.jpeg" caption="Harness System Diagram" %}

<img src="assets\CEV_Wiring_Schematic.jpeg" alt="Alt text" width="200" height="100">






