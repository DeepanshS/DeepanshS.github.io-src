---
title: "Core Scientific Dataset Model: A lightweight and portable model and file format for multi-dimensional scientific data"
authors:
  - admin
  - Thomas Vosegaard
  - Dominique Massiot
  - Philip J. Grandinetti
date: "2020-01-02"
doi: "10.1371/journal.pone.0225953"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*PLOS ONE*"
publication_short: "PLOS ONE"

abstract: The Core Scientific Dataset (CSD) model with JavaScript Object Notation (JSON) serialization is presented as a lightweight, portable, and versatile standard for intra- and interdisciplinary scientific data exchange. This model supports datasets with a p-component dependent variable, {U0, …, Uq, …, Up−1}, discretely sampled at M unique points in a d-dimensional independent variable (X0, …, Xk, …, Xd−1) space. Moreover, this sampling is over an orthogonal grid, regular or rectilinear, where the principal coordinate axes of the grid are the independent variables. It can also hold correlated datasets assuming the different physical quantities (dependent variables) are sampled on the same orthogonal grid of independent variables. The model encapsulates the dependent variables’ sampled data values and the minimum metadata needed to accurately represent this data in an appropriate coordinate system of independent variables. The CSD model can serve as a re-usable building block in the development of more sophisticated portable scientific dataset file standards.

# Summary. An optional shortened abstract.
# summary:

tags:
  - Multi-dimensional Dataset
  - CSDM
  - Universal file-format
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
