# CSS

Cascading Style Sheets

<img src="/css-is-awesome.jpg" alt="CSS is Awesome meme" width="500" v-click/>

---

# CSS

- Write CSS in a .css file and link it to HTML with

<v-clicks>

```html
<link href="<path-to-style-file>.css" rel="stylesheet" />
<style>
  p {
    color: red;
  }
</style>
```

- CSS starts with selectively choose one/many HTML elements, and setting the style rules
```css{0|1|all}
button {
  color: rgb(25 25 30);
  font-size: 1em;
  text-align: center;
  border: 1px dotted brown;
  border-radius: 5px;
}
```
</v-clicks>
---

<v-click>

Powerful selectors, and HUGE number of properties

</v-click>

<v-click>

```css{1|1-3|1-5|1-6|1-8|all}
.hero-section {} /* Class sector */

#email-input {} /* Id selector */

h1 {} /* Select HTMl element */
* {} /* Select everything */

button, .button, .btn {} /* Select multiple element */

input["required"] {} /* Select based on HTML attribute */

.list > li {} /* Select IMMEDIATE children */

.list li {} /* Select NO-MATTER-HOW-DEEP children */

input + lablel {} /* Adjacent sibling selector */

input ~ label {} /* General sibling selector */
```

</v-click>

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

<v-click>

### Common CSS properties

```css
* {
  padding: 8px;
  margin: 2em;
  font-size: 2rem;
  text-align: left | right | center | justify | ...;
  display: inline | block | flex | grid | ...;
  color: lightblue | #a5b6c7 | rgb() | hsl();
  background-color: #0f0f0f | url("/image-link");
  border: 1px solid red;
  border-radius: 1px | 50%;
}
```

</v-click>

---

## The box model

<img src="/box_model.png" width="800" alt="Box model" />

---

More to learn about:

<v-clicks>

- CSS transform, transition, and animations properties
- CSS Grid and Flexbox layout
- CSS responsive units (em, rem, vw, etc.)
- CSS variables
- CSS reset files
- Reference and tutorial of CSS on [MDN Web doc](https://developer.mozilla.org/en-US/docs/Web/CSS)

</v-clicks>
<v-click>

## CSS tools

</v-click>


<v-clicks>

- Prepared CSS components: Bootstrap, Bulma, Material, etc.
- Utility CSS: TailwindCSS, WindiCSS, etc.
- Plug and play CSS: WaterCSS
- CSS processor: SCSS, PostCSS

</v-clicks>

<div class="text-center text-blue-500 text-3xl mt-3" v-click>
  Give a lot of whitespace and contrast
</div>
