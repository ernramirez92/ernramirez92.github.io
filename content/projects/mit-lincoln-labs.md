+++
title = "MIT Lincoln Labs Internship"
date = 2015-06-01
draft = false
image = "/images/projects/lincoln-labs.png"
description = "Controls Engineering Intern - Implementing Extended Kalman Filter for autonomous driving localization."
+++

# MIT Lincoln Labs - Controls Engineering Intern

MIT Lincoln Labs has been working on a autonomous driving a sensor that uses very high frequency (VHF) radar reflections of underground features to generate a baseline map of a road's subsurface.

The sensor is called Localizing Ground Penetrating Radar (LGPR). It creates a map while driving and later when the vehicle returns to the same location, it compares what it sees with LGPR to what the GPS thinks it should see from the map it stored. This allows the vehicle to be more reliable than it would be using only vision or lane marker based localization.

I worked on implementing and calibrating an Extended Kalman Filter in [ROS](http://www.ros.org/) that would estimate position based on LGPR data and GPS data. In addition to implementing the EKF, I developed a simulation environment in ROS based on previously collected data to validate and tune parameters in the EKF.

[More about the Project](https://www.ll.mit.edu/r-d/projects/groundhog)
