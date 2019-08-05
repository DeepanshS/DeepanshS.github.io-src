---
title: CSDM
summary: Light weight and portable Core Scientific Dataset Model (CSDM) for multi-dimensional data.
tags:
- CSDM
- CSDF
- Core Scientific Data Model
- Data Model

date: "2019-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link:  https://github.com/DeepanshS/csdmpy

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# image:
#   caption: Photo by Toa Heftiba on Unsplash
#   focal_point: Smart

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

<!-- The core scientific dataset (CSD) model is a *light-weight*, *portable*,
*versatile*, and *standalone* data model capable of handling a variety of
scientific datasets. The model only encapsulates
data values and the minimum metadata, to accurately represent a $p$-component
dependent variable,
$\mathbf{U}\equiv(\mathbf{U}_0, ..., \mathbf{U}_q, ... \mathbf{U}\_{p-1})$
discretely sampled at $M$ unique points in a $d$-dimensional coordinate space,
$(\mathbf{X}_0, ... \mathbf{X}_k, ... \mathbf{X}\_{d-1})$.
The model is not intended to encapsulate
any information on how the data might be acquired, processed, or visualized.

The data model is *versatile* in allowing many use cases for most spectroscopy,
diffraction, and imaging techniques. As
such the model supports multi-component datasets associated with continuous
physical quantities that are discretely sampled in a multi-dimensional space
associated with other carefully controlled quantities, for e.g., a mass as a
function of temperature, a current as a function of voltage and time, a signal
voltage as a function of magnetic field gradient strength, a color image with
a red, green, and blue (RGB) light intensity components as a function of two
independent spatial dimensions, or the six components of the symmetric
second-rank diffusion tensor MRI as a function of three independent spatial
dimensions. Additionally, the model supports multiple dependent variables
sharing the same $d$-dimensional coordinate space. For instance,
the simultaneous measurement of current and voltage as a function of time.
Another example would be the simultaneous acquisition of air temperature,
pressure, wind velocity, and
solar-flux as a function of Earth’s latitude and longitude coordinates. We
refer to these dependent variables as *correlated-datasets*.

The CSD model is independent of the hardware, operating system,
application software, programming language, and the object-oriented
file-serialization format utilized in serializing the CSD model
to the file. Out of numerous file serialization formats, XML, JSON, property
list, the model adopt the data-exchange oriented JSON (JavaScript Object Notation)
file-serialization format because its *human-readable*, and *easy integration*
with any number of programming languages and field related application-software. -->
