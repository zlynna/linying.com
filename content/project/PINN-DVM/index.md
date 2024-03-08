---
title: PINN-DVM
summary: Physics-informed Neural Networks combined with Discrete Vellocity Method.
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: code
    url: https://github.com/zlynna/PINN-DVM
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

The linearized Bhatnagar–Gross–Krook equation is widely used to describe low-speed rarefied gas flows and can be solved numerically using deterministic methods such as the discrete velocity method (DVM). With the help of physics-informed neural networks (PINNs), which have experienced rapid development in recent years, we develop a new surrogate model that combines the PINNs and DVM methods (PINN–DVM) to simulate rarefied gas flows. In the proposed PINN–DVM model, the linearized Bhatnagar–Gross–Krook equation is directly encoded into the residual of an artificial neural network. A new loss function for the boundary condition based on the impermeable diffusion model is proposed to accurately capture the velocity slip and temperature jump at the boundary. PINN–DVM overcomes the limitations of conventional numerical methods, such as complex mesh generation and derivative calculations. Furthermore, the proposed model is enhanced by a self-adaptive strategy based on the neural tangent kernel, which enables the loss weight for each component of the loss function to be adjusted adaptively. Four representative numerical cases of Couette flow, Fourier heat transfer flow, triangular duct flow, and cavity flow demonstrate the superiority of the proposed PINN–DVM model in solving rarefied gas flows compared with original PINNs.
