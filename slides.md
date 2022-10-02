---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
    ## Slidev Starter Template
    Presentation slides for developers.

    Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
    persist: false
# use UnoCSS
css: unocss
---

# Web development crash course

## HTML, CSS, JavaScript, and other things you might wanna learn

<br/>

#### By: Bao Huynh @ [ACM@UC](https://acmatuc.org)

---

# Agenda

1. HTML
2. CSS
3. JavaScript
4. Cool demo: https://bh-demo-notecracker.netlify.app

---

# HTML

HyperText Markup Language

<v-clicks>

-   HTML is a markup language that defines the structure of your content

-   System of **tags** that you "enclose" your content with to "mark" it a certain way, combined with **attributes** that
    give extra information about the element

```html{1|3|2|all}
  <p>
    Hello MakeUC and ACM@UC
  </p>
```

```html
<a href="https://makeuc.io" class="rainbow"> Hello MakeUC and ACM@UC </a>
```

-   Some tags are self-enclosed
```html
<img src="https://i.imgur.com/oeYzasc.jpeg" alt="" />
<input type="text" placeholder="Homeaddress" />
<br />
```

</v-clicks>

---

# HTML


<v-clicks>

-   HTML can be **nested**

```html
<div>
  <p>My home is <strong>here</strong><p>
  <button>Open door <img src="/door.png" /></button>
  <a href="https://to-my-home.com">
</div>
```

- List of common tags and attributes
```html
<p class="color-red" id="presentation">Paragraph</p>
<div>Divide HTML into sections for easier styling</div>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>

<html></html>
<head></head>
<body></body>
<header></header>
<nav></nav>
<footer></footer>
```
</v-clicks>

---

```html
<section></section>
<aside></aside>

<button type="submit|button">Button text</button>
<a href="https://link.com" >Text to show</a>
<img src="https://image.com" alt="Alt text" />

<ul>
  <li>List item 1</li>
  <li>List item 2</li>
</ul>
<ol>
  <li>Ordered List item </li>
  <li>Ordered List item </li>
</ol>

<form>
  <input type="text|email|date|number|file" disabled placeholder="email" id="email-input" required="true"/>
  <label for="email-input">Enter email:</label>
</form>
```

<v-clicks>

- Other HTML tags: detail/summary, figure/figcaption, cite, etc.

- Other HTML attributes: aria attributes, pattern, data attributes, etc.

</v-clicks>

---
layout: center
---

<div class="text-6xl leading-loose text-center text-red-800 font-bold mt-5">
  DO NOT USE TAGS FOR STYLING PURPOSES
</div>

---
src: "./css.md"
---
<!-- CSS Page loaded-->
---
src: ./javascript.md
---
<!-- JavaScript page loaded -->
---

# Project time