---
layout: default
title: Actuator Design 
description: Actuator Set-Up Design From Statics HW 4
technologies:
image: /assets/images/actuator-design.jpeg
---

<img src="{{ '/assets/images/actuator-diagram.jpg' | relative_url }}" width="500" alt="Actuator Diagram">

The mechanism was required to fit within a 150 cm by 50 cm bounding box and use pin connections at all joints. The design was evaluated in two stages: first assuming the bar to be rigid and second accounting for beam bending and deflection.

In the first stage of the design, the bar was modeled as a rigid body. The actuator was treated as a two-force member applying a force along its axis, and all joints were modeled as ideal pins.
<img src="{{ '/assets/images/part-one.jpg' | relative_url }}" width="500" alt="Part One">

In the second stage, the member was modeled as a simply supported beam. Only the components of the applied load and actuator force transverse to the beam were considered to contribute to bending. A maximum allowable deflection of 2% of the beam length was imposed as a design constraint.
<img src="{{ '/assets/images/part-two.jpg' | relative_url }}" width="500" alt="Part Two">

With this cross section, the beam safely supports approximately 62 kN. This is well below the actuator force limit, so beam deflection is the controlling factor. 