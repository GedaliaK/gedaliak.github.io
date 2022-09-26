---
layout: post
title: "Modeling Guitar Strings for Sound Synthesis"
subtitle: Research in Junior Year
background: /assets/media/voice_coach_background.png
date: 2022-03-26
---

### Modeling Guitar Strings for Sound Synthesis (Article in Progress)

General work flow was:
1. Solve wave equation
2. Look at time signal and frequency domain spectra
3. Listen to wave equation
4. Compare with sampled guitar sounds

#### Work done:
* modeled and solved 1D wave equations with viscous friction, frequency dependent losses, and stiffness.
* techniques used:
  * separation of variables to solve Partial Differential Equations (PDEs).
  * Routh Criteria analysis to verify validaty of solutions (stability analysis).
  * Discrete modeling with digital waveguides and finite difference equations
  * Inverse modeling:
    * traced peaks of spectrogram of recorded guitar notes, and used those to interpolate and generate an analytical model of the equations
    * used Prinicple Component Analysis in attempt to break recorded samples into eigen-"notes" (like eigen-faces in machine learning) and reconstruct notes with eigenvectors and eigenvalues.
  * convolved impulse response of recorded guitars with above methods to try and capture more dynamics of the systems.
  
#### Purpose of Work:
Grad student was working on a guitar note recognition machine learning model that was being trained to minimize the loss between notes it heard and notes it was generating. Ideally, if the model could generate a note that matched what it heard, it would also know what note it had heard. By having an analytical model of note generation, it would be easier to calculate loss between the generated and recorded notes, and use automatic differentiation.

This is based off the [DrummerNet Paper](https://arxiv.org/abs/1906.03697).