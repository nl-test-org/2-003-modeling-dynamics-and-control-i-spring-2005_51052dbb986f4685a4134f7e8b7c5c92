---
course_id: 2-003-modeling-dynamics-and-control-i-spring-2005
layout: course_section
parent_title: Study Materials
title: Hardware
type: course
uid: 7772984a0715ec47488ac34f735f05c9

---

[Main]({{< baseurl >}}/sections/study-materials/main) | Hardware | [System Model]({{< baseurl >}}/sections/study-materials/system_model) | [Linearized Control]({{< baseurl >}}/sections/study-materials/linear_control) | [Nonlinear Control]({{< baseurl >}}/sections/study-materials/nonlinear_cont) | [Movies]({{< baseurl >}}/sections/study-materials/movies) | [Technical Details]({{< baseurl >}}/sections/study-materials/tech_details) | [Credits]({{< baseurl >}}/sections/study-materials/credits)

The two major sections of the Levitator are the plant/sensor structure and the electronics and computer which control the structure.

Plant
-----

![Photograph of suspended ball.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/ball_suspended2.jpg)

Levitator in action (above) and its schematic representation (below).

![Alternate schematic.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/basic_physical.jpg)

The plant consists of the actuator, an iron-core electromagnet and the steel ball bearing levitated by the electromagnet, along with the sensor that sends position to the control circuitry.

Current through the coils of the electromagnet induces a magnetic field in the iron core. In conjunction with the sensor and control electronics, the electromagnet exerts a force on the steel ball so as to keep it floating at a given height.

To control the position of the ball, the control electronics need to know the actual position of the ball at any given time. In this device, position is sensed by a light source and detector acting in combination. Light from the source striking the detector creates a current which is transduced into a voltage. The higher the ball is, the less light passes above the ball to the detector, translating to correspondlingly less voltage. In the control electronics, this voltage is translated into a position reading.

Control Electronics
-------------------

![Control circuitry, with the plant structure.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/system_group.jpg)

Control circuitry, with the plant structure.

The control circuitry consists of a set of power supplies and amplifiers connected to a control computer. The control computer is a dedicated digital signal processor (DSP), programmed through the laptop. The power supplies and amplifiers receive the signal from the position sensor and send power to the actuator. An input/output box wired to the analog to digital and digital to analog converters on the computer allows the power electronics and the computer to talk to one another. In the photograph above, the ball rests on a micrometer/force measurement apparatus used in calibrating the system.

![Interior of control box.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/box_photo.jpg)

The power electronics box.

Combining the plant and control electronics, the schematic for the whole system is:

![schematic.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/systemschematic.jpg)