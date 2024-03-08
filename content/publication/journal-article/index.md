---
title: "Simulation of rarefied gas flows using physics-informed neural network combined with discrete velocity method"
authors:
- admin
- Wenjun Ma
- Qin Lou
- Jun Zhang

date: "2023-07-24T00:00:00Z"
doi: "https://doi.org/10.1063/5.0156404"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Physics of Fluids*"
publication_short: "PoF"

abstract: The linearized Bhatnagar–Gross–Krook equation is widely used to describe low-speed rarefied gas flows and can be solved numerically using deterministic methods such as the discrete velocity method (DVM). With the help of physics-informed neural networks (PINNs), which have experienced rapid development in recent years, we develop a new surrogate model that combines the PINNs and DVM methods (PINN–DVM) to simulate rarefied gas flows. In the proposed PINN–DVM model, the linearized Bhatnagar–Gross–Krook equation is directly encoded into the residual of an artificial neural network. A new loss function for the boundary condition based on the impermeable diffusion model is proposed to accurately capture the velocity slip and temperature jump at the boundary. PINN–DVM overcomes the limitations of conventional numerical methods, such as complex mesh generation and derivative calculations. Furthermore, the proposed model is enhanced by a self-adaptive strategy based on the neural tangent kernel, which enables the loss weight for each component of the loss function to be adjusted adaptively. Four representative numerical cases of Couette flow, Fourier heat transfer flow, triangular duct flow, and cavity flow demonstrate the superiority of the proposed PINN–DVM model in solving rarefied gas flows compared with original PINNs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.researchgate.net/profile/Wenjun-Ma-7/publication/372609968_Simulation_of_rarefied_gas_flows_using_physics-informed_neural_network_combined_with_discrete_velocity_method/links/6554c87a3fa26f66f40447a6/Simulation-of-rarefied-gas-flows-using-physics-informed-neural-network-combined-with-discrete-velocity-method.pdf
url_code: 'https://github.com/zlynna/PINN-DVM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
