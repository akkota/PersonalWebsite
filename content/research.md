---
title: "Research"
description: "ML projects in optimization, microscopy, and forecasting."
showTableOfContents: false
---

<p class="page-intro">A few ML projects I've worked on in labs and industry.</p>

<div class="akhil-research-list">

{{< researchblock
  image="img/research/optimization.jpg"
  accent="blue"
  title="Difference-of-convex neural optimization"
  meta="Li Group · Purdue ChemE · Feb 2026 – Present"
  question="Can we make neural nets better at hard nonconvex problems?"
  contribution="I'm building models that use DC programming inside the network, with custom PyTorch autograd and new ways to pick anchors."
  result="We have a full training setup and good early results. Working toward a conference submission."
  tags="PyTorch · DC programming · CVXPY · Optimization"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/microscopy.jpg"
  accent="teal"
  reverse="true"
  title="Microscopy and microplastics"
  meta="Prabhakar Group · Purdue · Sep 2025 – May 2026"
  question="Can we automatically segment and track cells in noisy microscopy video?"
  contribution="I put together a Cellpose + TrackMate pipeline, fine-tuned it on our labels, and wrote Python tools for the cytotoxicity analysis."
  result="False-positive microplastic detections dropped by up to 21%. OUR Distinction List and an AAAR submission."
  tags="Cellpose · TrackMate · OpenCV · Microscopy"
  link="/experience/"
>}}

{{< researchblock
  image="img/research/forecasting.jpg"
  accent="violet"
  title="Product demand forecasting"
  meta="Cisco · Jan 2024 – May 2024"
  question="How do you forecast demand when price and seasonality differ by product?"
  contribution="I trained XGBoost and Random Forest models on 15 product lines and built Plotly/Dash dashboards for the team."
  result="About 90% forecast accuracy, and roughly five fewer hours of manual reporting each week."
  tags="XGBoost · Random Forest · Plotly · Dash"
  link="/experience/"
>}}

</div>

<p class="page-intro" style="margin-top: 2rem;">Supported by Purdue OUR and SURF. If you're hiring or collaborating on ML work, feel free to reach out.</p>

{{< buttonrow >}}
{{< button href="experience/" >}}Full experience{{< /button >}}
{{< button href="contact/" >}}Get in touch{{< /button >}}
{{< /buttonrow >}}
