---
layout: archive
title: "Transparent, Robust and Ultra-Sparse Trees (TRUST)"
permalink: /trust/
author_profile: true
---

`TRUST` is my flagship Ph.D. project in Trustworthy AI. 
It achieves [comparable accuracy](https://adc-trust-ai.github.io/accuracy.html){:target="_blank"} to state-of-the-art machine learning algorithms - including black box models like Random Forest - while remaining fully interpretable. 
Current version solves regression problems (variants like time series only experimentally). Extensions to multiclass classification and beta regression are already under development and I will soon make them available as well.

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

Below is a demo of the integrated LLM capabilities within `TRUST`. The video starts by showing the call to the `.explain()` method included with the free version of the model, where a user wishes to know more about the model's prediction for a specific instance (a target house). 
After the default output is shown, including the key features influencing the prediction and their direction, plus a final summary explanation, the user then asks Gemini a completely custom question (premium feature): what minimum changes should be made in the attributes of the given house for the model to output a cheaper predicted price instead? This demonstrates the potential for actionable insights and counterfactual analysis offered by the premium LLM integration.

<video controls width="854" height="480">
  <source src="../files/TRUSTxGemini.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
