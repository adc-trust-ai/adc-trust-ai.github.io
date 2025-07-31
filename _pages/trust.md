---
layout: archive
title: "Transparent, Robust and Ultra-Sparse Trees (TRUST)"
permalink: /trust/
author_profile: true
---

`TRUST` is my flagship Ph.D. project in Trustworthy AI. 
It achieves [comparable accuracy](https://adc-trust-ai.github.io/accuracy.html){:target="_blank"} to state-of-the-art machine learning algorithms - including black box models like Random Forest - while remaining fully interpretable. Scroll down for a short demo of `TRUST`.
Current version solves regression problems (variants like time series only experimentally). Extensions to multiclass classification and beta regression are already under development and I will soon make them available as well.

## Free version (Released in July 2025)
- Complete core functionality including main visualization and explainability tools
- Explainability tools include state-of-the-art variable importance scoring and ALE plots + instance-level explanations including SHAP analysis
- Perfect for small to medium datasets where both accuracy and interpretability are essential
- See Proprietary - Permissive Binary Only License at the bottom of this page
- Link to [version history](https://adc-trust-ai.github.io/changelog.html){:target="_blank"} 

## Premium version (launching in October 2025)
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

### LICENSE
Copyright (c) 2025 Albert Dorador Chalar. All rights reserved.

Redistribution and use in binary forms, with or without modification, are permitted provided that the following condition is met:

Redistributions in binary form must reproduce the above copyright notice, this condition and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY ALBERT DORADOR CHALAR "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL ALBERT DORADOR CHALAR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
