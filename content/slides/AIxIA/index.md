---
title: Ultrasound Detection of Subquadricipital Recess Distension
summary: 
authors: [admin, Gabriele Civitarese, Dragan Ahmetovic, Claudio Bettini, Roberta Gualtierotti, Flora Peyvandi, Sergio Mascetti]
tags: []
categories: []
date: '2023-02-01T00:00:00Z'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

## Ultrasound Detection of Subquadricipital Recess Distension

<sub><sup>Marco Colussi*, Gabriele Civitarese, Dragan Ahmetovic, Claudio Bettini, Roberta Gualtierotti, Flora Peyvandi, Sergio Mascetti</sup></sub>

---

## Problem definition

- Context: detecting distended subquadricipital recess (SQR) needed for preventing permanent articular damage in hemofilic patients.
- Problem: no CAD system exists to support the practitioner
- Objective: create a CAD system to support the practitioner in  
  - Identifying the SQR (green box)
  - Classifying the SQR as:
    - Not-distended
    - Distended

---

## SQR examples



---

## Contribution

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Detection approach

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Multi-task approach

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Dataset
- Data collected from 208 hemophilic patients aged 44 ± 18.6
- Images selected and annotated by expert radiologist
- Evaluated on 5-fold cross-validation, with patient-based splits

---

## Results

---

## Best detection

---

## Worst detection

---

## Conclusion and future works

---

## Dataset
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

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
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

[Ask](https://warpcut.github.io/#contact)