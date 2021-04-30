---
course_id: 2-003-modeling-dynamics-and-control-i-spring-2005
layout: course_section
parent_title: Labs
title: 'Lab 3: Translational 2nd-order Spring/Mass/Damper System; Natural Response;
  Fitting Models'
type: course
uid: 251559173a3bbdbbe7a3db6c7794f661

---

Pre-Lab ([PDF]({{< baseurl >}}/sections/labs/prelab3))  
Lab 3 Description ([PDF]({{< baseurl >}}/sections/labs/lab3))

In this lab, the dynamics of a second-order system composed of a spring, mass and damper are examined. As shown in figure 1, the system consists of a cylindrical shaft riding on air bearings. A voice coil is attached at the left side to add variable damping. The voice coil armature is wound on an aluminum cylinder. If the coil is open-circuited, some damping is still present due to eddy currents in the aluminum. If we short-circuit the voice coil the damping is increased significantly, because of resistive losses in the wire. In the middle between the two air bearings, an adjustable spring is attached to the shaft. By decreasing the length of the spring, the natural frequency of the system is increased and the damping ratio is decreased. By adjusting the length of the spring, one can demonstrate overdamped, critically damped and underdamped behavior. A pulse can be applied to the system by allowing a small brass ball hanging on a piece of string to impact the plate attached to the shaft at the right. To measure the motion, an LVDT (Linear Variable Differential Transducer) is fixed on the right side of the shaft. See Prelab3 page 5 for an explanation of LVDT operation.

![The second order system.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig1.jpg)

Figure 1. The second order system with voice-coil, air bearings, adjustable spring, shaft mass, and LVDT sensor. (Image by Prof. Trumper.)

Figure 2 shows the drawing of this system.

Note the schematic detail in figure 2 that shows the off-center attachment of the spring to the collar on the shaft. The reason for this is to allow for axial displacements of the end of the spring by free rotation of the shaft. If the spring is bend, it shortens a distance d, as shown in figure 2 on the bottom right. If the spring was not attached this way, the actual stiffness would be much larger. More importantly, the linearity of the stiffness would be much less because of the unwanted axial pulling force on the spring rod.

![Drawing of the first-order rotary system.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig2.gif)

Figure 2. Drawing of the first-order rotary system. (Image by Prof. Trumper.)

Figure 3 shows the idealization of its dynamics.

![A Brass ring can be added to increase the inertia.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig3.gif)

Figure 3. A Brass ring can be added to increase the inertia. (Image by Prof. Trumper.)

Figure 4 shows the Close-up spring collar attachment.

![Close-up spring collar attachment.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig4.jpg)

Figure 4. Close-up spring collar attachment. (Image by Prof. Trumper.)

The signal passes through a signal conditioner and is made visible on an oscilloscope in Figure 5.

![Overdamped impulse response.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig5.jpg)

Figure 5. Overdamped impulse response. (Image by Prof. Trumper.)

The signal passes through a signal conditioner and is made visible on an oscilloscope in Figure 6.

![Underdamped impulse response.](/courses/mechanical-engineering/2-003-modeling-dynamics-and-control-i-spring-2005/labs/lab3fig6.jpg)

Figure 6. Underdamped impulse response. (Image by Prof. Trumper.)

Materials and Notes: Practical Info and Comment
-----------------------------------------------

*   Adjustable spring clamp
    
*   Air bearings from New Way, see Lab 2. They do not mount directly to optical breadboard, so we made special adaptor plates from Pelrin. Another simpler option to attach the bearings to the baseplate would be to use toeclamps.
    
*   Angle plate 3X3X3 inch ground steel (flat surfaces) from Suburban Tool, inc.
    
*   Collars see Lab 2.
    
*   Optical breadboard
    
*   LVDT (Linear Variable Differential Transducer) Schaevitz HR-1000 ($450 each) was the best choice, because of the large clearance through the hole in the body of the sensor. LVDT's with smaller clearance caused problems with alignment. This sensor has a hole all the way through. It is unguided, i.e. does not use bearing surfaces, to avoid friction.
    
*   Separate signal conditioner ($167) is needed for this LVDT.
    
*   Shaft Thompson shafting, necessary threading can be specified, precision ground stainless steel, diameter 3/4 inch to match the air bearings.
    
*   Spring
    
*   Stand
    
*   Voice coil LA24-33 BEI-Kimco seems to be the only manufacturer for this type of part. Prices are much lower when ordering in large quantities ($315 each when ordering 30).