---
layout: page
title: The IDS Scaled Smart City (IDS3C)
description: Scaled city testbed implementation and maintaince
img: assets/img/scaledcity.png
importance: 1
featured: true
category: work
related_publications: false
---

## Overview

The **IDS Scaled Smart City (IDS3C)** is a cyber-physical testbed developed by the [Intelligent and Distributed Systems (IDS) Lab](https://ids-lab.net/facilities/), which occupies a 400 square feet area and includes 70 robotic cars at a 1:25 scale and 12 quadcopters. It is designed to study coordination and control of intelligent transportation systems in a controlled yet realistic environment. The platform integrates connected and automated vehicles (CAVs), human-driven vehicles (HDVs), infrastructure, and aerial systems into a unified experimental framework.

<div class="row justify-content-center mt-3 mb-3">
  <div class="col-sm-8">
    <img src="{{ 'assets/img/ids3c_bv.png' | relative_url }}" 
         class="img-fluid rounded z-depth-1" 
         alt="Scaled City">
  </div>
</div>

The scaled city enables real-time experimentation on traffic coordination, decision-making under uncertainty, and human–AI interaction. It provides a bridge between theoretical algorithm design and physical validation, allowing for rapid prototyping and deployment of control and learning-based methods.

---

## Demo Videos
**Baseline controller.**  
This video presents the scaled city experiment under the baseline controller.

<div class="row justify-content-center mt-3 mb-3">
  <div class="col-sm-10">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
      <iframe
        src="https://www.youtube.com/embed/J5PhbT0owF8"
        title="IDS Scaled Smart City Baseline Demo"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
      </iframe>
    </div>
  </div>
</div>

**Coordination controller.**  
This video presents the scaled city experiment under the coordination controller.

<div class="row justify-content-center mt-3 mb-3">
  <div class="col-sm-10">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
      <iframe
        src="https://www.youtube.com/embed/dMIGunOJBec"
        title="IDS Scaled Smart City Coordination Demo"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
      </iframe>
    </div>
  </div>
</div>

---

## My Contributions

#### Scaled City Maintenance and Operation

- Took primary responsibility for maintaining the IDS Scaled Smart City as a reliable experimental platform.  
- Supported daily operation, including system setup, monitoring, experiment assistance for lab members.  
- Diagnosed and resolved hardware and software issues to ensure stable and reproducible experiments and demonstrations.

#### Vehicle Controller Integration and Tuning

- Integrated existing coordination and baseline controllers into newly designed cars  
- Ensured compatibility between controllers and the physical vehicle platform  
- Participated in the design and tuning of PID controllers to improve tracking and control performance  

#### Drone Integration

- Contributed to integrating drones into the scaled city framework  
- Supported system-level connectivity between aerial agents and the existing platform  
- Assisted in enabling future experiments involving both ground vehicles and drones  
