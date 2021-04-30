---
course_id: 2-003-modeling-dynamics-and-control-i-spring-2005
layout: course_section
parent_title: Study Materials
title: System Model
type: course
uid: 57dd520a3a29428663572d8872899351

---

[Main]({{< baseurl >}}/sections/study-materials/main) | [Hardware]({{< baseurl >}}/sections/study-materials/hardware) | System Model | [Linearized Control]({{< baseurl >}}/sections/study-materials/linear_control) | [Nonlinear Control]({{< baseurl >}}/sections/study-materials/nonlinear_cont) | [Movies]({{< baseurl >}}/sections/study-materials/movies) | [Technical Details]({{< baseurl >}}/sections/study-materials/tech_details) | [Credits]({{< baseurl >}}/sections/study-materials/credits)

The first step in controlling a system is deriving an accurate model for the system. Each of the system elements' behaviors can be derived from basic physics. In the examples below, many of the equations are left in terms of constants. These constants are dependent on materials and geometry, and are thus specific to the hardware. Procedures for measuring these constants are provided in Yi Xie's MEng thesis (see the [technical details]({{< baseurl >}}/sections/study-materials/tech_details) section).

![Free body diagram of the plant.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/freebody.jpg)

Free Body Diagram of the Plant. (Fig. M1)

As shown in the free body diagram above, two forces act on the steel ball: gravity and the electro-magnetic force from the coils. The equation of motion for the ball is therefore:

![mxdoubledot=mg-F_M.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/meq1.jpg)

Eq. M1.

In the simplest model, Fm, the electromagnetic force, is proportional to the square of the current passing through the inductor and inversely proportional to the square of the distance between the magnet and the steel ball. The constant C is a function of the physical construction of the electromagnet.

![Fm=C(i/x+x0)^2.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/meq2.jpg)

Eq. M2.

The power amplifier is set up as an actively controlled current source, so we assume current to be the controlled variable. This means that we can ignore coil inductance and speed voltage effects. Combining the two equations given above gives:

![mxdoubledot=mg-C(i/(x+x0))^2.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/study-materials/meq3.jpg)

Eq. M3.