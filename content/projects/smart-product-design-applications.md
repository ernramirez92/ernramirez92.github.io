+++
title = "Smart Product Design Applications"
date = 2016-01-01
draft = false
image = "/images/projects/me218b.png"
description = "ME218B - Intermediate coursework applying smart product design principles."
course = "ME218B"
+++

# ME218B: Smart Product Design Applications

ME218B is the second course in Stanford's graduate level Mechatronics series. In this course, you learn about user I/O, timer systems, interrupts, signal conditioning, software design for embedded systems, state charts, sensors, actuators, noise, and power supplies.

## Labs

The MCU used for all the labs was TI's Tiva Launchpad, an ARM Cortex M4F evaluation board.

**Lab 1 (Individual):** Firmware to control stepper motor using wave drive, full step, half step, and micro-stepping.

**Lab 2 (Individual):** Use PWM peripheral to control speed of a DC motor and measure speed using an encoder.

**Lab 3 (Individual):** Drive-Break mode and closed loop speed control.

**Lab 4 (Team):** Mobile robot capable of sensing an IR beacon and receiving commands via SPI.


## Team Project

For our team project, our robot needed to sense three things. The first was a 100mA current being driven at 20kHz through a wire. This allowed the robot to drive along the wire. The second was an oscillating magnetic field to determine the location of each station. The third was a long range IR beacon to help the robot align itself with a distant beacon.

I designed all of the signal conditioning circuits for the three sensors. The circuits I made used a mix of tuned resonance circuits, Butterworth filters, peak detection circuits, Hall effect sensing, and a multi-stage photo transistor amplification.

![Team Project 1](/images/projects/me218b-1.jpg)

![Team Project 2](/images/projects/me218b-2.jpg)

![Team Project 3](/images/projects/me218b-3.jpg)

![Team Project 4](/images/projects/me218b-4.jpg)

![Team Project 5](/images/projects/me218b-5.jpg)

![Team Project 6](/images/projects/me218b-6.jpg)

![Team Project 7](/images/projects/me218b-7.jpg)

![Team Project 8](/images/projects/me218b-8.jpg)

![Team Project 9](/images/projects/me218b-9.jpg)


## Wire Sensing Circuit

![Wire Sensing Circuit](/images/projects/me218b-10.png)

## Hall Effect Circuit

![Hall Effect Circuit](/images/projects/me218b-11.png)

## Infrared Light Detecting Circuit

![Infrared Light Detecting Circuit](/images/projects/me218b-12.png)
