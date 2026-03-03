---
permalink: /research/
title: CTAO and pSCT
author_profile: false
redirect_from:
  - /lab/
  - /research/
  - /psct/
  - /ctao/
---
Here in UW-Madison, I work with [Professor Vandenbroucke](https://pages.physics.wisc.edu/~justin/) and his group on the Cherenkov Telescope Array Observatory (CTAO), which will be the newest generation Imaging Atmospheric Cherenkov Telescope (IACT) observatory, with two arrays: one in the northern hemisphere and one in the southern hemisphere. Our group works on a proposed design for a Medium Sized Telescope (MST), one of the three kinds of telescopes CTAO arrays will feature. In particular, this proposed design has Schwarzschild-Couder dual mirror optics that is also used by the Small Sized Telescopes. This design has advantages in comparison to the current single-mirror MST design. In particular, it causes much milder aberrations to light incoming off-axis of telescope pointing, enabling good performance across a wide field of view, and the optics is more isochronous, i.e, the light arrives at each pixel with less spread in arrival time due to different optical paths. In addition, this telescope will have high resolution silicon photomultiplier (SiPM) pixels in the camera, with over eleven thousand pixels covering a field of view, 8 degrees in diameter.

There is currently a prototype Schwarzschild-Couder Telescope (pSCT) at the Fred Lawrence Whipple Observatory (FLWO) in Arizona, and the collaboration is currently working on upgrading the camera for the pSCT. Camera design bellow (1):

![](/images/Past20260303121241.png)

Here at UW-Madison we are doing the mass calibration and assembly of the camera modules, the smallest independent divisions of the camera which will be assembled together in the pSCT for a full camera by Fall 2026, starting with 1 sector (out of 9) by Summer 2026. Here's an image of a module (1)

![](/images/Past20260303121547.png)

These new modules feature improved electronics design for reduced electrical noise and crosstalk than the first iteration, and the SiPMs have less optical crosstalk and higher photon detection efficiency. I have been implementing some of the calibrations for these modules, making them as automated as possible so that we can efficiently calibrate the 177 modules that will compose the full camera. The calibrations include scanning through the parameter space of various settings to find the best values of such settings for each module, with the goal that all modules will behave optimally and similarly at the end of this calibration. 

Once the updated camera is installed, I will be working with the data of the pSCT.


All images in here came from the following reference.

(1) Ambrosi, Giovanni, et al. “Design and Performance of the Upgraded Prototype Schwarzschild-Couder Telescope Camera Module.” arXiv:2512.12529, arXiv, 14 Dec. 2025. _arXiv.org_, [https://doi.org/10.48550/arXiv.2512.12529](https://doi.org/10.48550/arXiv.2512.12529).