---
name: Data Acquisition and Safety System for EV
tools: [Microcontrollers, Python, C++]
image: /assets/car.png
description: Embedded Systems and PCB design for data acquisition and safety systems. Placed 2nd nationally for Data and Telemetry at the 2025 Shell Eco Marathon with this system.
# external_url: https://thefabulous.co/
---

# CEV 
During the academic semester, I am part of a project team building an awesome EV that competes in the annual _Shell Eco Marathon_. Find our team website [here](https://www.cornellelectricvehicles.org/)

Over the past two years, I have worked on the following sub-systems:

### Data Acquisition 

Researched feasibility of concept, prototyped from scratch and integrated car-mounted sensors such as Rotary encoder for steering, RPM, IMU, etc. Involved implementation of CAN, UART, SPI protocols for comparing various possible set-ups. I also implemented multi-threading on a Pi Pico to enable simulataneous RPM conversions and data transfer. Currrently working on scaling system to more than 15 sensors with accurate and low-latency data collection. <br>
I lead a team of two peers while developing this system and liased with leads of other vehicle sub-systems to ensure proper specifications and meeting competition requirements. We placed 2nd nationally in 2025 with this system.

{% include elements/figure.html image= "/assets/CAN_system.png" caption="CAN System Diagram" %}

### Auxilliary Board and System Integration
Designed and built a complete Wiring harness system to enable easy access to critical car systems during competition. Prototyped several sub-systems: lighting, horn, emergency stop, braking, etc as part of safety system design. Co-designed updated PCB based on team design requirements. 

{% capture carousel_images %}
/assets/Aux_PCB.jpeg
/assets/CEV_Wiring_Schematic.jpeg
{% endcapture %}
{% include elements/carousel.html %}

<!-- <img src="/assets/CEV_Wiring_Schematic.jpeg" alt="Alt text" width="200" height="100"> -->






