---
title: "Research"
description: "ML research in optimization, microscopy, and forecasting."
showTableOfContents: false
---

<p class="page-intro">A few projects where the model has to deal with real constraints — optimization structure, noisy images, or messy demand data.</p>

<div class="akhil-research-list">

{{< researchblock
  image="img/research/optimization.jpg"
  accent="blue"
  title="Difference-of-convex neural optimization"
  meta="Li Group · Purdue ChemE · Feb 2026 – Present"
  question="Can neural nets solve hard nonconvex problems more reliably?"
  contribution="Architectures that bake in DC programming, with custom PyTorch autograd, feasibility penalties, and new anchor-selection methods."
  result="End-to-end training setup with strong predictive projections; working toward a conference submission."
  tags="PyTorch · DC programming · CVXPY · Optimization"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/microscopy.jpg"
  accent="teal"
  reverse="true"
  title="Vision for microscopy and microplastics"
  meta="Prabhakar Group · Purdue · Sep 2025 – May 2026"
  question="Can we segment and track cells across noisy microscopy frames without babysitting every clip?"
  contribution="Pipeline around Cellpose and TrackMate, fine-tuned on our annotations, plus Python tooling for cytotoxicity analysis."
  result="Up to 21% fewer false-positive microplastic detections. OUR Distinction List; AAAR submission."
  tags="Cellpose · TrackMate · OpenCV · Microscopy"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/forecasting.jpg"
  accent="violet"
  title="Product-line demand forecasting"
  meta="Cisco · Jan 2024 – May 2024"
  question="How do you forecast demand when price and seasonality change by product?"
  contribution="XGBoost and Random Forest models over 15 product lines, with Plotly/Dash dashboards for the team."
  result="Around 90% forecast accuracy and about five fewer hours of manual reporting each week."
  tags="XGBoost · Random Forest · Plotly · Dash"
  link="/experience/"
>}}

</div>

<p class="page-intro" style="margin-top: 2rem;">Supported by Purdue OUR and SURF recognition. Happy to chat about ML work that needs both careful theory and solid engineering.</p>

{{< buttonrow >}}
{{< button href="experience/" >}}Full experience{{< /button >}}
{{< button href="contact/" >}}Get in touch{{< /button >}}
{{< /buttonrow >}}
