---
title: 'From noise to PET: diffusion is winning, but is it really?'
summary: Diffusion methods have overtaken GANs for generating images. Turning MRI into PET is within reach, yet a realistic picture is not a trustworthy one.
date: 2026-06-18
authors:
  - me
tags:
  - Generative Models
  - Diffusion Models
  - PET
  - Medical Image Synthesis
---
Teach a model to drown an image in noise, then to claw it back, and it learns to imagine new ones. The same trick now produces medical images sharp enough to fool a trained eye.

<!--more-->

For years, adversarial methods set the bar for image synthesis, and they were difficult to train, prone to collapse and to artifacts. Diffusion methods, which generate by reversing a slow addition of Gaussian noise, have overtaken them. They train more stably and produce cleaner, more faithful results, and the same shift is sweeping through image-to-image and text-to-image generation.

That progress is tempting for PET. The scan is expensive, radioactive, and scarce, while MRI are ubiquitous in nearly every hospital. A model that turns an MRI into a faithful PET image would widen access to information many patients never get.

However, realistic is not the same as clinically correct. PET is read quantitatively, and a synthetic image can look convincing while the numbers beneath it are wrong. The field has no shared benchmark to test whether generated images preserve the measurements clinicians and researchers depend on, across tracers, scanners, and cohorts.

Before a synthetic scan informs a single clinical decision, that benchmark has to exist. Generation is the easy part. Trust is the part still missing, and that is where I think the next work belongs.
