---
title: "Research"
description: "ML projects in optimization, microscopy, and forecasting."
showTableOfContents: false
---

<p class="page-intro">A few ML projects from labs and industry.</p>

<div class="akhil-research-list">

{{< researchblock
  image="img/research/optimization.jpg"
  accent="blue"
  title="Difference-of-convex neural optimization"
  meta="Li Group, Purdue ChemE, Feb 2026 - Present"
  question="Making neural nets better at hard nonconvex problems"
  contribution="Building models that use DC programming inside the network, with custom PyTorch autograd and better ways to pick anchors."
  result="We have a working training setup and decent early results. Aiming for a conference submission."
  tags="PyTorch, DC programming, CVXPY, Optimization"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/microscopy.jpg"
  accent="teal"
  reverse="true"
  title="Microscopy and microplastics"
  meta="Prabhakar Group, Purdue, Sep 2025 - May 2026"
  question="Segmenting and tracking cells in noisy microscopy video"
  contribution="Built a Cellpose and TrackMate pipeline, fine-tuned it on our labels, and wrote Python tools for cytotoxicity analysis."
  result="False-positive microplastic detections dropped by up to 21%. OUR Distinction List and an AAAR submission."
  tags="Cellpose, TrackMate, OpenCV, Microscopy"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/forecasting.jpg"
  accent="violet"
  title="Product demand forecasting"
  meta="Cisco, Jan 2024 - May 2024"
  question="Forecasting demand when price and seasonality differ by product"
  contribution="Trained XGBoost and Random Forest models on 15 product lines and built Plotly and Dash dashboards for the team."
  result="About 90% forecast accuracy. Saved roughly five hours of manual reporting each week."
  tags="XGBoost, Random Forest, Plotly, Dash"
  link="/experience/"
>}}

</div>

<p class="page-intro" style="margin-top: 2rem;">Supported by Purdue OUR and SURF. If you want to collaborate or are hiring for ML work, email me.</p>

{{< buttonrow >}}
{{< button href="experience/" >}}Full experience{{< /button >}}
{{< button href="contact/" >}}Get in touch{{< /button >}}
{{< /buttonrow >}}
