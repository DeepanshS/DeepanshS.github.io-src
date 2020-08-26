---
title: "Statistical Learning of NMR tensors from 2D Isotropic/Anisotropic Correlation Nuclear Magnetic Resonance Spectra"
authors:
  - admin
  - Philip J. Grandinetti

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*J. Chem. Phys. (submitted)*"
publication_short: "JCP"

abstract: Many linear inversion problems involving Fredholm integrals of the first kind are frequently encountered in the field of magnetic resonance. One important application is the direct inversion of a solid-state NMR spectrum containing multiple overlapping anisotropic subspectra to obtain a distribution of the tensor parameters. Because of the ill-conditioned nature of this inverse problem, we investigate the use of the TSVD-S-LASSO based regularization method, which (a) stabilizes the solution and (b) promotes sparsity and smoothness in the solution. We also propose a unambiguous representation for the anisotropy parameters using a piecewise polar coordinate system to minimize rank deficiency in the inversion kernel. To obtain the optimum tensor parameter distribution, we implement the k-fold cross-validation, a statistical learning method, to determine the hyperparameters of the regularized inverse problem. In this article, we provide the details of the linear- inversion method along with numerous illustrative applications on purely anisotropic NMR spectra, both synthetic as well as experimental two-dimensional spectra correlating the isotropic and anisotropic frequencies.

# Summary. An optional shortened abstract.
# summary:

tags:
  - Linear Inversion
  - Statistical learning
  - NMR tensors
  - Glass NMR
  - PASS
  - MAT
  - MAF
  - NMR

featured: true

# links:
#   - name: ""
#     url: ""
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
projects: ["mrinversion", "mrsimulator"]
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
