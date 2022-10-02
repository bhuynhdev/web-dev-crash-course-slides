# CSS

Cascading Style Sheets

<v-clicks>

- Write CSS in a .css file and link it to HTML with

```html
<link href="<path-to-style-file>.css" rel="stylesheet" />
```

- CSS starts with selectively choose one/many HTML elements, and setting the style rules
```css{1|all}
p {
  color: rgb(25 25 30);
  font-size: 1em;
  text-align: center;
  border: 1px dotted brown;
  border-radius: 5px;
}
```
</v-clicks>
---

Powerful selectors, and HUGE number of properties
```css{1|1-2|1-4|1-6|1-8|all}
h1 {} /* Select HTMl element */
* {} /* Select everything */

.hero-section {} /* Class sector */

#email-input {} /* Id selector */

button, .button, .btn {} /* Select multiple element */

input["required"] {} /* Select based on HTML attribute */

.list > li {} /* Select IMMEDIATE children */

.list li {} /* Select NO-MATTER-HOW-DEEP children */

input + lablel {} /* Adjacent sibling selector */

input ~ label {} /* General sibling selector */
```

---

More selectors

```css
/* Pseudo-selector */
a:hover {} /* :focus, :focus-within */

p:last-child {}
p:last-of-type {}

/* Pseudo-element */
a::after {} /* ::before */
```

Common CSS properties
```css
p {
  padding: 8px;
  margin: 2em;
  font-size: 2rem;
  text-align: left | right | center | justify | ...;
  display: inline | block | flex | grid | ...;
  position: absolute | relative | fixed | sticky;
  color: lightblue | #a5b6c7 | rgb() | hsl();
  background-color: #0f0f0f | url("/image-link");
  border: 1px solid red;
  border-radius: 1px | 50%;
}
```
---

## The box model

<img src="/box_model.png" width="800" alt="Box model" />

---

More to learn about:

<v-clicks>

- CSS transform, transition, and animations
- CSS Grid and Flexbox layout
- CSS mobile-first responsive designs (with responsive units like em, rem, vw, etc.)
- CSS variables
- Reference and tutorial of CSS on [MDN Web doc](https://developer.mozilla.org/en-US/docs/Web/CSS)

</v-clicks>

<v-click>

## CSS tools

</v-click>


<v-clicks>

- Prepared component CSS: Bootstrap, Bulma, Material, etc.
- Utility CSS: TailwindCSS, WindiCSS, etc.
- Plug and play CSS: WaterCSS
- CSS processor: SCSS, PostCSS

</v-clicks>

<div class="text-center text-blue-500 text-3xl mt-4" v-click>
Give a lot of whitespace and contrast
</div>
