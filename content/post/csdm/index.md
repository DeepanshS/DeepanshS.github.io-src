---
title: 'CSDM: Core Scientific Dataset Model'
subtitle: ''
summary: A light weight and portable data model for multi-dimensional data.
authors:
- admin
tags:
- CSDM
- csdmpy
# categories:
# - Demo
date: "2019-08-01T00:00:00Z"
lastmod: "2019-08-01T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["csdm", "csdmpy"]

# Set captions for image gallery.
gallery_item:
- album: gallery
  caption: TEM image
  image: CSDM-Figure4.png
- album: gallery
  caption: Astronomy
  image: CSDM-Figure5.png
- album: gallery
  caption: NMR
  image: CSDM-Figure6.png
- album: gallery
  caption: Dark
  image: theme-dark.png
- album: gallery
  caption: Multi-channel Images
  image: CSDM-Figure9.png
- album: gallery
  caption: Vector datasets
  image: CSDM-Figure10.png
- album: gallery
  caption: Tensor datasets
  image: CSDM-Figure11.png
- album: gallery
  caption: Strawberry
  image: theme-strawberry.png
---

The core scientific dataset (CSD) model is a *light-weight*, *portable*,
*versatile*, and *standalone* data model capable of handling a variety of
scientific datasets. The model only encapsulates
data values and the minimum metadata, to accurately represent a $p$-component
dependent variable discretely sampled at $M$ unique points in a $d$-dimensional
coordinate space. The model is not intended to encapsulate
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
with any number of programming languages and field related application-software.

**Supported datasets**

{{< gallery >}}
