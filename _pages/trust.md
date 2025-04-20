---
layout: archive
title: "Transparent, Robust and Ultra-Sparse Trees (TRUST)"
permalink: /trust/
author_profile: true
---

TRUST is my flagship Ph.D. project in Trustworthy AI. 
It achieves comparable accuracy to state-of-the-art machine learning algorithms - including black box models like Random Forest - while remaining fully interpretable. 
Current version solves regression problems (variants like time series only experimentally). An extension to multiclass classification is in the horizon.

## Free version
- Complete core functionality including main visualization and explainability tools
- Explainability tools include state-of-the-art variable importance scoring and ALE plots + instance-level explanations including SHAP analysis
- Perfect for small to medium datasets where both accuracy and interpretability are essential

## Premium version
- All the core functionality included in the free version
- Faster training times (can handle bigger datasets)
- Guaranteed support
- Added functionality:
  - LLM integration for enhanced explainability
  - Signed (+/-) variable importance plots
  - 2-way interaction ALE plots
  - Prediction confidence intervals
  - Out-Of-Distribution detection

Below is a demo of the integrated LLM capabilities within TRUST. In the video, a user is asks Gemini what minimum changes should be made in a given data point (a target house) for the learnt model to output a prediction of a desired value (expected house price).

<video controls width="640" height="360">
  <source src="files/TRUSTxGemini.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
