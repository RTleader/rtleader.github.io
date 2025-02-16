---
title: My Project to be Presented at Fairfax County Regional Science & Engineering Fair
date: 2025-02-15
type: post
showTableOfContents: true
description: Status Update & Overview
draft: false
---
![](/projects/scifair24-25/SF_2025_Web_Hero.jpg)
*image credit: <https://www.fcps.edu/sciencefair>*

I have recently received the good news that my engineering project for my school's Science Fair had achieved 1st place in the engineering category and thus qualified to move onto the [Regional Fair hosted by FCPS](https://www.fcps.edu/sciencefair). It was a pleasure presenting to all the judges and I'm grateful for this opportunity to move on to the next level.


## Overview 
Project Title: *Designing NIR Sensor-based Glucose Spectroscopy Model for Non-invasive Glucose Monitoring*

This project was an Engineering Project that was inspired by my experiences taking care of my Type 1 Diabetic Sister and some research I'd done on the topic.

### Context: Current Issues
Type 1 Diabetes is an autoimmune disorder in which the body's ability to produce insulin significantly diminishes or is lost completely due to the immune system attacking the pancreatic β-cells (Not to be confused with Type 2 Diabetes which is the body becoming resistant to insulin or producing less over time due to unhealthy eating habits). 

![](/projects/scifair24-25/t1db-vs-t2db.png)
*image credit: <https://www.sugarfit.com/blog/difference-between-type-1-and-type-2-diabetes/>*

One of the devices used to treat this condition is a glucose monitor, which involves a small computer with a needle that's embedded into your arm, and stays attached at all times with an adhesive patch. Due to various natural processes such as immune system function, biofouling(undesired accumulation of things from the body's microbiome), and physiological acid levels, the life span of this device is usually limited to around 10 days at a time. In other words, the invasive nature of this device(needle "invades" body) necessitates frequent replacement, which can incur annual costs between $1,200 and $3,600 per year. Some of the more expensive systems can even reach up to **$7,000** per year!

![](/projects/scifair24-25/How_to_use_CGM.jpeg)
*image credit: <https://getheally.com/patients/news/how-to-use-continuous-glucose-monitoring>*

### Potential Solution & What My Project Did
While doing research, I discovered some studies looking into the use of Near-Infrared(NIR) Spectroscopy. Essentially, electromagnetic waves at the NIR level(about 800 to 2,500 nm) would be emitted into the tissue, where any present glucose molecules in the blood stream would absorb and reflect certain wavelengths([See my note's on Beer's Law for some info on how the calculations work](/notes/apchem/beers_law/)). Measuring how many NIR rays were able to come through or were reflected would give a pretty good calculation estimate of blood sugar levels without having to enter the body with a needle! This meant that a glucose monitor using spectroscopy could significantly lower costs due to not needing frequent replacements or any at all!

My project is a model of NIR spectrocopy being applied to measure the amount of glucose within the body, by using a gelatin based tissue phantom as a sit in for actual human tissue. The idea was to use a very minimal NIR spectrometer connected with a Raspberry Pi with code that read the spectrometer's numbers and presented an estimated concentration using the Beer-Lambert Law. The numbers for the calculation would be adjusted until the estimate was pretty close to the known concentration in the tissue phantom. Due to technical limitations my goal was to try to get to or below 10% error.

![](/projects/scifair24-25/projectpic.jpg)
*A photo of one of the test models*

Unfortunately, due to technical issues that resulted in a malfunction of the sensor and the circuit frying, I fell short of this goal, reaching 16% as the lowest error. However, I stil feel this project was a success as it showcased the promising application of a technology in the area of glucose monitoring with the potential to significantly lower costs.

### Future Updates
If you would like to hear more about my project, please don't hesitate to contact me at `isaackim626 [at] gmail [dot] com`. OR if you would like to come hear me talk about my project at the Fairfax County Regional Fair, then come to Robinson Secondary School on Sunday, March 23, from 1-3 pm. It would be great to see anyone reading this post at the actual fair!