---

title: "Core Scientific Dataset Model"
summary: "A lightweight and portable model and file format for multi-dimensional scientific data"
authors: ["Deepansh J. Srivastava"]
tags: [CSDM, csdmpy]
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  slide_level: 2
  slide_number: true
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
  center: true

# motivation

---

---

{{< slide background-image="/csdm/motivation/01-file-exchange.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/02-presentation-art.png" background-size="contain">}}

---

{{<
    slide
      background-image="/csdm/motivation/03-pdf.png"
      background-size="contain"
      data-state="dim"
    >}}

---

{{< slide background-image="/csdm/motivation/04-pdf-exchange-art.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/05-database.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/06-many-ways-to-save-art.png" background-size="contain">}}

---

{{< slide background="/csdm/motivation/07-numeric-type.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/08-byte-order.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/09-data-order.png" background-size="contain">}}

---

{{< slide background="/csdm/motivation/10-components-order.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/11-multiple-interpretation.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/12-metadata.png" background-size="contain">}}

---

{{< slide background-image="/csdm/motivation/13-metadata-no-standards.png" background-size="contain">}}

---

<!-- # consequences -->
{{< slide background-image="/csdm/consequences/01-art.png" background-size="contain">}}

---

{{< slide background-image="/csdm/consequences/02-end-users.png" background-size="contain">}}

---

{{< slide background-image="/csdm/consequences/03-imports-art.png" background-size="contain">}}

---

{{< slide background-image="/csdm/consequences/04-delayed-problem.png" background-size="contain">}}

---

{{< slide background-image="/csdm/consequences/05-why-not-CSV-art.png" background-size="contain">}}

---

{{< slide background-image="/csdm/consequences/07-csv-vs-text.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/01-PSDF-art.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/02-PSDF.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/03-CSD-model.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/01-light-weight.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/02-versatile.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/03-independent.png" background-size="contain">}}

---

{{< slide background-image="/csdm/CSDM/04-objectives/04-comprehensible.png" background-size="contain">}}

---

## Examples

---

```json
  "csdm": {
    "version": "1.0",
    "timestamp": "2019-05-21T13:43:00Z",
    "tags": ["GMSL", "satellite altimetry", "climate"],
    "description": "Global Mean Sea Level rise.",
    "dimensions": [
      {
      "type": "linear",
      "count": 1608,
      "increment": "0.083333333 yr",
      "coordinates_offset": "1880.0417 yr"
      }
    ],
    "dependent_variables": [
      {
      "type": "internal",
      "unit": "mm",
      "quantity_type": "scalar",
      "numeric_type": "float32",
      "component_labels": ["GMSL"],
      "components": [
        [-183.0, -171.125, ...  ... 59.6875, 58.5]
      ]
      }
    ]
  }
```

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

- black: Black background, white text, blue links (default)
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

[Documentation](https://sourcethemes.com/academic/docs/)
