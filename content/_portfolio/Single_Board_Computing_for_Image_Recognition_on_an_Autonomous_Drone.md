---
title: "Single Board Computing for Image Recognition on an Autonomous Drone"
excerpt: "This is a conference paper presented in IEACon regarding the use of Single Board Computer for Image Recognition on an Autonomous Drone"
date: 2023-11-06
last_modified_at: 2025-07-11
header:
  overlay_image: /assets/images/splash_drone_adjusted.jpg
  teaser: /assets/images/splash_drone_adjusted.jpg
---

[![IEEE](/assets/images/ieee-logo.png)](https://ieeexplore.ieee.org/document/10370368)

## Abstract
Image recognition is a well-established method of extracting information from digital images. However., the selection, testing and integration of such methods when designing the software and hardware to enable situational awareness for autonomous systems in unstructured environments, remains a challenge. This is particularly the case when lightweight and low- cost are the driving requirements for the system. The main aim of this paper is to compare the k-nearest neighbour (K-NN) traditional machine learning method against a deep learning model for a character recognition task intended for implementation on a single-board computer on an aerial drone. A series of image recognition experiments were carried out which attempted to identify a set of alphanumeric characters using a Raspberry Pi (RPi) image capture system (RPi V2.I camera with an RPi 4 B) with a total cost of £97.50 and weight of 49g. The experiments identified that (LSTM) within Tesseract optical character recognition (OCR) was 2.I2% more successful on average than a K-NN algorithm for character recognition but took 58.30% longer on average to process a single image. It also indicated that for human-defined shape detection in an unstructured environment, data specific to each search environment must be used. This highlighted the importance of tailoring hardware and software selection to the application.