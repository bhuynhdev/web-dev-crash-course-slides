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


-   HTML can be **nested**

<v-clicks>


```html
<div>
  <p>My home is <strong>here</strong><p>
  <button>Open door <img src="/door.png" /></button>
  <a href="https://to-my-home.com">
</div>
```

- List of common tags and attributes: https://codepen.io/baohuynhlam/pen/ZEoRKPx
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

<img src="/html-meme.jpeg" alt="HTML for babies book meme" width="400" v-click />

<div class="text-4xl leading-loose text-red-500 font-bold mt-5" v-click>
  DO NOT USE TAGS FOR STYLING PURPOSES
</div>