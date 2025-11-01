+++
title = "Smart Product Design Practice"
date = 2016-03-01
draft = false
image = "/images/projects/me218c.png"
description = "ME218C - Advanced coursework in smart product design and mechatronics."
course = "ME218C"
+++

# ME218C: Smart Product Design Practice

ME218C is the third course in Stanford's graduate level Mechatronics series. In this course, you learn about PIC architecture and assembly programming, inter-processor communication, system design with multiple microprocessors, and A/D and D/A techniques, You also get to apply that knowledge through two labs and a team course project.

## Labs

**Lab 1 (Individual):** Programmed an 8bit PIC in assembly to move a stepper motor using full step drive. The PIC would automatically take steps on manually take steps in a given direction based on the states of three input pins.



**Lab 2 (Team):** Programmed a four node UART communication network using four 8-bit PICs in a assembly. The node I programmed was responsible for reading the sending information and lighting an LED for 0.5 seconds when a button was pressed.



## Team Project

For our team project, we decided to make a hovercraft and remote control as well as a game to play. The game was inspired by Hungry-Hungry Hippo. Our design was meant to pay homage to one of the best professors at Stanford, Ed Carryer. Ed loves his yellow Porsche, fanny packs and being generally awesome. So, we made a yellow Porsche hover craft and controller based on a fanny pack. We added three modes of sending commands to the hovercraft: audio commands, motion command, and button commands.

For this project I used TI's Tiva Launchpad, an ARM Cortex M4F evaluation board. We utilized Xbee to wirelessly send command over a UART connection.


![Project Image 1](/images/projects/me218c-1.jpg)

![Project Image 2](/images/projects/me218c-2.jpg)

![Project Image 3](/images/projects/me218c-3.png)

![Project Image 4](/images/projects/me218c-4.jpg)

![Project Image 5](/images/projects/me218c-5.jpg)

![Project Image 6](/images/projects/me218c-6.jpg)

![Project Image 7](/images/projects/me218c-7.jpg)

![Project Image 8](/images/projects/me218c-8.jpg)

![Project Image 9](/images/projects/me218c-9.jpg)

![Project Image 10](/images/projects/me218c-10.jpg)

## Code

{{< gist anonymous abf761f5d0dab9633f907a9bc42357ed >}}

