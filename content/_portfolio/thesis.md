---
title: "Artificial Intelligence Based Image Recognition Using Limited-Resource Hardware for an Aerial Drone Application"
excerpt: "Thesis Report"
header:
  overlay_image: /assets/images/boards.jpg
  teaser: /assets/images/boards.jpg
---

[![QUB](/assets/images/Queens_Red_Logo_Landscape.png)](https://pure.qub.ac.uk/en/studentTheses/artificial-intelligence-based-image-recognition-using-limited-res)
## Abstract
Existing search and rescue (SAR) systems using aerial drones depend on transmitting images to ground stations for decision making, as drones typically lack on-board image processing capability – particularly those at the lower end of the market. Despite technological advances, lightweight, low-cost and small-size image recognition capability on smaller civil drone systems have yet to be fully explored.
This thesis examines the integration of deep learning models with commercially available single board computing (SBC) and image capture hardware, quantifying the lower limits of image recognition capability relative to weight, cost and size on aerial drones. The methodology includes specification, development and testing of system architectures for an autonomous image recognition task and the independent operation of both a fixed-wing aircraft and a quadcopter. It includes the assessment of candidate AI approaches required to successfully process and identify objects on the drone without human intervention.
Results showed the optimal combination of weight / cost / size combination for the highest detection rate was the VIM3 Pro SBC (28.5g / £117.50 / 47.56cm2) with Khadas OS08A10 camera (13.2g / £80.00 / 15.97cm2), using the YOLO V4-CSP model. Testing across various environments (beach, mountains, grass, forest, concrete) the success rate of identifying a human form at least once per flight was 90.48% when test and training data were from the same location. The YOLOv4-CSP model achieved 75.87% average precision (AP) on a custom dataset. When test data was recorded separately from training data (different people and weather conditions), AP score dropped to 26.69%.
Higher success rates require training data beyond the 2020 images used, including all environments with comprehensive light / weather conditions. The work delivers a protocol / framework for system development and testing, plus a custom control regime for a fixed-wing drone based on Pixhawk autonomous control system using ArduPilot software (ArduPlane).