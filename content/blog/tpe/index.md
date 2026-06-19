---
title: 'TPE: finding the turning point in disease progression'
summary: Disease trajectories are not lines. They bend, and the bend is where the clinical meaning hides.
date: 2026-06-18
authors:
  - me
tags:
  - Disease Progression Modeling
  - Alzheimer's Disease
  - Biomarkers
---
A disease does not progress in a straight line. It drifts, then turns, and the turn is the part that matters.

<!--more-->

A biomarker can changes gradually until it passes a critical point and then accelerates. The trajectory bends, and from one patient to the next that bend lands in a different place, pushed around by age, genetics, and everything else that makes a person who they are. Average the curves together and the turn smears into nothing.

I built the transition point estimator (TPE) to find that turn directly. It uses machine learning to model the nonlinear link between a biomarker and an outcome, keeps the confounders in check, and reads off the point where each marker's behavior shifts. That point becomes its cutpoint.

A cutpoint set this way is grounded in how the disease actually moves, not in a round number chosen for convenience. Find the turn, and you find the moment worth acting on.
