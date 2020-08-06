---

title: "Core Scientific Dataset Model"
summary: "A lightweight and portable model and file format for multi-dimensional scientific data"
authors: ["Deepansh J. Srivastava"]
tags: [CSDM, csdmpy, mrsimulator]
categories: []
date: "2019-02-05T00:00:00Z"

slides:
  background_transition: "none"
  # slide_level: 2
  slide-number: true
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (none).
  highlight_style: github
  center: true

# motivation


---

{{< slide background-image="/title.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/01-csdm-intro.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/motivation/02-presentation-art.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- At some point, we have all witnessed the horrors of lack of standard file-format.

{{< /speaker_note >}}

---

{{<
    slide
      background-image="/csdm/motivation/03-pdf.png"
      background-size="contain"
      data-state="dim"
     background-transition="none">}}

{{< speaker_note >}}

- Adobe's introduced a portable document format (PDF) which has now become a standard for document file-exchange.

{{< /speaker_note >}}

---

{{< slide background-image="/csdm/motivation/05-database.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- Nowadays besides scientific document, Journal ask also for scientific datasets.
- Unlike pdf, there is no portable scientific dataset format.
- You may ask, why do we need such file-format. How many ways can there be store numbers?
- The problem isn't storing number. It is reading them.

{{< /speaker_note >}}

---

{{< slide background-image="/csdm/motivation/12-metadata.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- Locating where data and metadata resides.
{{< /speaker_note >}}

---

{{< slide background-image="/csdm/motivation/11-multiple-interpretation.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- If located, how should the numbers be read.
- Based on some common format, there are at-least 96 ways to interpret the data with only one correct ways
{{< /speaker_note >}}

---

{{< slide background-image="/csdm/motivation/13-metadata-no-standards.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- Numbers by itself is useless without supplementary metadata.
- There are no standards for metadata.
{{< /speaker_note >}}

---

<!-- # consequences -->
{{< slide background-image="/csdm/consequences/07-csv-vs-text.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- Consequence is CSV files.
- Inefficient and may have metadata loss.
{{< /speaker_note >}}

---

{{< slide background-image="/csdm/CSDM/03-CSD-model.png" background-size="contain" background-transition="none">}}

{{< speaker_note >}}

- Introducing CSDM.
{{< /speaker_note >}}

---
<!-- # Objectives -->
{{< slide background-image="/csdm/CSDM/04-objectives/01-light-weight.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/02-versatile.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/03-independent.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/04-comprehensible.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/05-data-model-reveal/01.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/05-data-model-reveal/02.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/05-data-model-reveal/03.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/05-data-model-reveal/04.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/05-data-model-reveal/05.png" background-size="contain" background-transition="none">}}

---
<!-- JSON -->
{{< slide background-image="/csdm/CSDM/05-JSON.png" background-size="contain" background-transition="none">}}

---
<!-- CSDM -->
{{< slide background-image="/csdm/CSDM/csdm/09-csdm-object.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/csdm/09-csdm-object-2.png" background-size="contain" background-transition="none">}}

---
<!-- Dimension -->

{{< slide background-image="/csdm/CSDM/10-dimension/10-linear.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/10-dimension/10-monotonic.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/10-dimension/10-labeled.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/10-dimension/10-dimension-example.png" background-size="contain" background-transition="none">}}

---

<!-- DependentVariable -->
{{< slide background-image="/csdm/CSDM/11-dependent_variable/06-1.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/11-dependent_variable/06-2.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/11-dependent_variable/06-3.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/11-dependent_variable/06-internal.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/11-dependent_variable/06-external.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/12-dependent_variable.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/13-dependent_variable.png" background-size="contain" background-transition="none">}}

---

<!-- Examples -->
{{< slide background-image="/csdm/CSDM/examples/examples_intro.png" background-size="contain" background-transition="none">}}

---
<!-- 1D scalar -->
{{< slide background-image="/csdm/CSDM/examples/01-example-0.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/examples/01-example-1.png" background-size="contain" background-transition="none">}}

---

<!-- 2D scalar NMR -->
{{< slide background-image="/csdm/CSDM/examples/02-NMR-example.png" background-size="contain" background-transition="none">}}

<!-- 2D{3} Image -->
<!-- {{< slide background-image="/csdm/CSDM/examples/03-RGB-example.png" background-size="contain" background-transition="none">}} -->

---
<!-- 3D{2} Vector -->
{{< slide background-image="/csdm/CSDM/examples/04-vector-example.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/examples/04-vector-example-1.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/examples/04-vector-example-2.png" background-size="contain" background-transition="none">}}

---
<!-- 2D{1,1,2,1} Correlated dataset -->
{{< slide background-image="/csdm/CSDM/examples/05-correlated-example.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/examples/05-correlated-example-1.png" background-size="contain" background-transition="none">}}

---

<!-- 2D{1,1,2,1} Correlated dataset -->
{{< slide background-image="/csdm/CSDM/examples/06-0D-example.png" background-size="contain" background-transition="none">}}

---

<!-- Summary -->
{{< slide background-image="/csdm/CSDM/summary.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/csdm/CSDM/csdmpy.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/intro.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/motivation.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/features.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/isotopomer-0.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/isotopomer-1.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/isotopomer-2.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/example-0.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/example-1.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/mrsimulator-doc.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/mrsimulator/application.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/future-work.png" background-size="contain" background-transition="none">}}

---

{{< slide background-image="/acknowledgment.png" background-size="contain" background-transition="none">}}

---

<!--
## Examples

---

## Features

- Efficiently write slides in Markdown
- 3-in-1: Create, Present, and Publish your slides
- Supports speaker notes
- Mobile friendly slides

---

## Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

## Code Highlighting

Inline code: `variable`

Code block:
```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (none)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/img/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/img/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://discourse.gohugo.io)

[Documentation](https://sourcethemes.com/academic/docs/) -->
