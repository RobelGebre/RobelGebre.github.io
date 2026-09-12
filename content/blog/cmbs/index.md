---
title: Cerebral Microbleeds
date: 2026-06-01
tags:
  - MRI
  - Deep Learning
  - Image Segmentation
  - Cerebral Small Vessel Disease
---
A handful of dark specks, a few millimeters across, scattered anywhere in the brain. That is a cerebral microbleed, and it is one of the hardest things in neuroimaging to pin down.

<!--more-->

Microbleeds are tiny, sparse, and easy to confuse with vessels, calcium, and ordinary iron. A whole brain may hold only a few, each a handful of voxels, so any model that hunts for them drowns in class imbalance and false positives. Radiologists still count them by hand, slowly, and rarely agree on the total.

Microbleeds track cerebral small vessel disease and amyloid angiopathy, and they are at the center of the safety question for therapies that clear amyloid, where new microbleeds that clinicians monitor as ARIA can halt treatment.

Detection models exist. Reliable segmentation does not. No deep learning model delineates microbleeds well enough to trust at the voxel level, and that is the gap I am working to close.
