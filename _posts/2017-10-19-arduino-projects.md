---
layout: post
title: The Arduino Projects Post
date: 2017-10-21
description:
img: servo.jpg
tags:
  - Physical Computing
  - Arduino
---

**Latest update: 21 Oct 2017** We're playing sound with theremins and keyboard, connecting electromotors and learning about back voltage, aka the circuit board killer, counting time, and flipping boards.

------------------------------


# Project 9 - Electric Motors

Code-wise this was a basic circuit, but it was important to understand how to deal with a) more powerful sources of energy and b) back-voltage, i.e. the fact that once you start pushing an electric motor with curent, it keeps spinning _and produces its own current_ that risks entering your circuit from the wrong side.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/pinwheel.mp4" type="video/mp4">
</video>

------------------------------

# Project 8 - Hourglass

We were tasked with counting down our meager existence (or pasta cooking time) by turning our Arduinos into hourglasses. LEDs light up on regular intervals and you can flip the Arduino to reset them.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/hourglass.mp4" type="video/mp4">
</video>

------------------------------

# Project 7 - Keyboard

Piezos vibrate on frequencies, and each note has its own frequency (the most famous is "A" at 440hz). So if you send differently modulated current to a piezo, it will vibrate on a certain frequency. Result: [PUBLIC DOMAIN MUSIC](https://arstechnica.com/tech-policy/2016/02/happy-birthday-is-public-domain-former-owner-warnerchapell-to-pay-14m/).

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/keyboard.mp4" type="video/mp4">
</video>

------------------------------

# Project 6 - Theremin

The most exciting thing about this project is that the sound coming from the piezo is modulated by a light sensor, so basically you're manipulating light in order to manipulate sound and that's just cool. The least exciting thing was doing this project in a closed room with twenty other people making their Arduinos squeal in a gloriously atonal chaos.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/theremin.mp4" type="video/mp4">
</video>

------------------------------

# Project 5 - Servo Motor

So this is where my Mac and my Arduino decided they never met before, and will not talk to strangers. I spent the better part of my evening troubleshooting the complete lack of meaningful port options on the Arduino app — besides the _ever so useful Bluetooth Input_ — but I came up short. But the code compiles, and the capacitors didn't explode, so we should be all set. ~~For now, here's a picture of the constructed board~~ **UPDATE** the USB cable was faulty. People, if you get the Arduino kits, there's a non-zero risk the provided USB cable will die on you for no reason. Also, before spending hours troubleshooting software, I learned it's smart to check all the HW components first. Even if they are literally five days old and have been working flawlessly until yesterday.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/servo.mp4" type="video/mp4">
</video>

------------------------------

# Project 4 - RGB Sensor

Analogue input again, and playing with the big RGB LED from the kit. The red/green/blue gels are pretty flimsy, while the gel holders are massive, so together they make an odd couple. But not in a family-comedy sort of way, more like "how did anyone think this will work" kind of way. I resorted to veeeeerrry carefully balancing the gels on top of the light sensors. It worked.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/rgbsensor.mp4" type="video/mp4">
</video>

------------------------------

# Project 3 - Heat Sensor

First time playing with analogue sensors - it was fun to figure out how to actually activate a sensor with no easy heat source around me. Lighters? Dumb idea. Good thing my lamp doesn't have an LED bulb...

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/heatsensor.mp4" type="video/mp4">
</video>

------------------------------

# Project 2 - Spaceship

This project was about programming the micro-controller to react to physical (digital) input, i.e. my fingers pushing a button.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/spaceship.mp4" type="video/mp4">
</video>

------------------------------

# Project 1 - Hurray, it's a Circuit

My first pushing of buttons, lighting of LEDs, and closing of circuits, on an Arduino. No coding, just pushing current and learning how not to fry anything.

<video height="500" controls>
  <source src="{{ site.baseurl }}/assets/video/itsalive.mp4" type="video/mp4">
</video>
