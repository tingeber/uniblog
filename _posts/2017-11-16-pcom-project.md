---
layout: post
title: On My Sleeve - PCOM first project
date: 2017-11-16
description:
img: onmysleeve-sketch.jpg
tags:
  - Physical Computing
  - Arduino
---

## Concept

A wearable sleeve that interprets data received through bluetooth and visualises them on a series of LEDs.

I am fascinated by the potential of technology to enhance our expression and add to communication between individuals. The concept of wearing one's heart on their sleeve made me think what it would look like if I literally wore an expression device on my arm. At first I was exploring the idea of using sensors to show my pulse rate, thereby exposing my emotional state without control on my part. However, from a technical perspective I didn't find that engaging enough (also, it is a project that has been done multiple times). For that reason, I decided that, instead of my emotional state, I can use the LEDs to express the emotional state of a community, a concept, or a movement. I am still deciding what exactly I will want to show, but a good example is pulling twitter stream data around a certain hashtag (say, #blacklivesmatter or #maga), doing basic sentiment analysis (flagging words representing hate or love, disgust or compassion), and pushing this information to the sleeve via Bluetooth.


## Electronics

### For the MVP:

- Arduino Uno
- Bluetooth chip
- NeoPixel RGBW Arduino shield

### For the final project:

- Adafruit FLORA
- Adafruit BLE wearable component
- 20 NeoPixel RGB LEDs
- Li-Poly external battery
- capacitors (to regulate current towards LEDs)
- resistors (I think?)
- lots of conductive thread
- fabric - a sleeve of some kind
- smartphone for sending data to wearable

![sketch]({{ site.baseurl }}/assets/img/basic-components.png)


## Design

This will be a sleeve, made out of fabric, meant to be worn on the forearm. Fabric and color TBD. The sleeve will have a series of RGB LED strips, each responding to input received from the smartphone via the BLE chip, and processed on the FLORA.

![sketch]({{ site.baseurl }}/assets/img/onmysleeve-sketch.jpg)


## MVP

An LED matrix that reacts to data input through BLE chip, without stitching into final product.
