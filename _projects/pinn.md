---
layout: page
title: Physics Informed Neural Networks for Battery Modeling
description: PINN based modeling of lithium ion battery dynamics
img: assets/img/battery.png
importance: 4
featured: false
category: work
related_publications: false
period: Nov. 2021 – Apr. 2022
---

## Overview

This project was conducted at the University of British Columbia from November 2021 to April 2022 under the supervision of [Maricela Best McKay](https://scholar.google.com/citations?user=k2OdAfAAAAAJ&hl=en). The work focused on applying Physics Informed Neural Networks to lithium ion battery modeling, with the goal of improving the understanding of electrode concentration dynamics and supporting more efficient battery charging strategies.

## Motivation

Battery systems are governed by physical laws that are often described by partial differential equations. Traditional numerical approaches can be computationally intensive, especially when calibration and repeated simulation are needed. This project explored whether Physics Informed Neural Networks could provide an effective alternative by embedding physical constraints directly into the learning process.

## Project Scope

The project involved developing and analyzing a PINN model to solve the governing partial differential equations in lithium ion battery modeling. The model was implemented in Julia and fitted to existing data describing electrode concentration dynamics with respect to scaled time and particle radius.

In addition to model development, the project also included data cleaning, analysis, and visualization. Simulated datasets were generated using PyBaMM to support validation and comparison of the model behavior.

## Contributions

1. Contributed to a research project as a research assistant by applying Physics Informed Neural Networks to solve partial differential equations in lithium ion battery modeling.

2. Developed and analyzed a PINN model in Julia for electrode concentration dynamics over scaled time and particle radius.

3. Performed data cleaning, exploratory analysis, and visualization for model development and interpretation.

4. Used PyBaMM to generate simulated datasets for validation and testing.

## Outcome

The project demonstrated how physics guided machine learning methods can be used to model battery dynamics in a structured and interpretable way. The work showed the potential of PINNs for combining domain knowledge with data driven modeling in energy systems.

## Repository

Project code is available here:

<p>
  <a href="https://github.com/SunWeihao1226/PINN_for_battery" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</p>