---
title: "Feedback-Driven Quantum Reservoir Computing for Time-Series Analysis"
authors:
- admin
- Keisuke Fujii
- Naoki Yamamoto
date: "2024-11-14T00:00:00Z"
doi: "10.1103/PRXQuantum.5.040325"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "PRX Quantum"
publication_short: "PRX Quantum **5**, 040325"

abstract: Quantum reservoir computing (QRC) is a highly promising computational paradigm that leverages quantum systems as a computational resource for nonlinear information processing. While its application to time-series analysis is eagerly anticipated, prevailing approaches suffer from the collapse of the quantum state upon measurement, resulting in the erasure of temporal input memories. Neither repeated initializations nor weak measurements offer a fundamental solution, as the former escalates the time complexity while the latter restricts the information extraction from the Hilbert space. To address this issue, we propose the feedback-driven QRC framework. This methodology employs projective measurements on all qubits for unrestricted access to the quantum state, with the measurement outcomes subsequently fed back into the reservoir to restore the memory of prior inputs. We demonstrate that our QRC successfully acquires the fading-memory property through the feedback connections, a critical aspect in time-series processing. Notably, analysis of measurement trajectories reveals three distinct phases depending on the feedback strength, with the memory performance maximized at the edge of chaos. We also evaluate the predictive capabilities of our QRC, demonstrating its suitability for forecasting signals originating from quantum spin systems.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Quantum Reservoir Computing
- Reservoir Computing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.aps.org/prxquantum/pdf/10.1103/PRXQuantum.5.040325
url_code: ''
url_dataset: ''
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