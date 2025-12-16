---
title: "Holographic Representation of One-Dimensional Many-Body Quantum States via Isometric Tensor Networks"
authors:
- admin
- Benjamin Sappler
- Frank Pollmann
date: "2025-12-12T00:00:00Z"
doi: "10.48550/arXiv.2512.11967"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv.2512.11967"

abstract: "Isometric tensor network states (isoTNS) allow for efficient and accurate simulations of higher-dimensional quantum systems by enforcing an isometric structure. We bring this idea back to one dimension by introducing a holographic isoTNS ansatz: a (1+1)-dimensional lattice of isometric tensors where the horizontal axis encodes physical space and an auxiliary 'holographic' axis boosts expressivity. Despite the enlarged geometry, contractions and local updates remain computationally efficient due to isometric constraints. We investigate this ansatz and benchmark it in comparison to matrix product states (MPS). First, we show that randomly initialized holographic isoTNS typically display volume-law entanglement even at modest bond dimension, surpassing the representational limits of MPS and related ansätze. Second, through analytic constructions and variational optimization, we demonstrate that holographic isoTNS can faithfully represent arbitrary fermionic Gaussian states, Clifford states, and certain short-time-evolved states under local evolutio---a family of states that is highly entangled but low in complexity. Third, to exploit this expressivity in broad situations, we implement a time-evolving block decimation (TEBD) algorithm on holographic isoTNS. While the method remains efficient and scalable, error accumulation over TEBD sweeps suppresses entanglement and leads to rapid deviations from exact dynamics. Overall, holographic isoTNS broaden the reach of tensor-network methods, opening new avenues to study physics in the volume-law regime."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Tensor Networks
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2512.11967
url_code: ''
url_dataset: https://zenodo.org/records/17907383
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

# slides: example
---