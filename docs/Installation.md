---
title: Installation
layout: default
nav_order: 2
---

{% include Header.html %}

## Installation in a Full Fuselage Model ##

Choose a location on the airplane that is accessible and where the status indicator LED will be visible to the pilot from the centre of the flying circle.  The included wiring can reach up to 11" (28cm) from the timer mounting location.

Click [HERE][1] for a dimensional drawing of the assembled PCB.

Use the drill template to locate the position of the two holes to be drilled through the fuselage sides.  The template has two sets of holes; one to locate 1/16" (1.5mm) diameter pilot holes and the other set for the actual suggested hole diameter.  A 5/32" (4mm) drill for the switch and a 7/32 (5.5mm) drill for the LED should provide a little extra clearance for installation.  Note: the holes in the provided vinyl label are smaller and should cover up any excessive gaps around the electrical components.

Leave the plywood spacer blocks attached to the PCB.  Position the Contol_Panel assembly in place and glue to the face of the spacer blocks to the inside wall of the fuselage.

Clean the outside surface of the fuselage around the switch and LED.  Carefully align and apply the vinyl label for a clean appearance.

{: .highlight }
**Caution:** The adhesive used on the label is very sticky. It is strongly suggested to use the 'wet' method to allow an opportunity to correctly position the label.  Wet the fuselage area and the back of the label with a soapy water solution (a popular blue window cleaner works very well) then position and align the label before pressing down and blotting off the excess water.  Let dry.

## Installation on a Profile Fuselage Model ##

The Control_Panel version for external mounting uses a low profile addressable LED and pushbutton switch.  Installation is straight forward as the PCB can be mounted with velcro or using the included #2 x 3/8" screws.  Hint: use thin CA glue to 'harden' the threaded holes when screwing into basla wood.

{: .highlight }
**Note:** The short addressable LED used on the profile fuselage version of the Control_Panel is an GRB Neopixel.  Refer to the Climb_and_Dive instruction manual under the section titled [Advanced Modifications, Additional Parameters Accessible within the Program Code][2] to change the variable named pixel_colour from "RGB" to "GRB".  This is needed to change the indictor LED to illuminate the correct colours.  Otherwise the red and green lights will be reversed.


[1]: https://github.com/CircuitFlyer/Control_Panel/Design%20Files/Contol_Panel_Drawing_-_v2.0.pdf
[2]: https://circuitflyer.com/Climb_and_Dive/docs/Advanced%20Modifications.html#additional-parameters-accessible-within-the-program-code
