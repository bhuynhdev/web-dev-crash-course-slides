# JavaScript

<v-click>

No, it's not Java

</v-click>

<v-click>

Is your friends/kids texting about JavaScript ?

</v-click>

<v-clicks>

- AF: **A**rrow **F**unction
- ASAP: **AS**ync **A**wait and **P**romises
- Jason: **Ja**va**s**cript **o**bject **n**otation

</v-clicks>

---

# JavaScript

-   Write in .js file to add interactivity to web pages

```html
<script src="js-file.js"></script>
```

<v-clicks>

-   High-level interpreted language with multiple paradigms: procedural, functional, a bit of OOP (with prototype inheritance)
-   **Client-side** APIs (Application Programming Interfaces):
    -   DOM API: Changing, updating, creating, or removing the browser HTML
    -   WebRTC: peer-to-peer multimedia streaming
    -   Navigator API: access to browser camera and microphone

</v-clicks>

---

# Server-side vs Client-side Js

<div class="grid grid-cols-2">
  <img src="/server-client.png" alt="Server client" width="350" />
  <img src="https://833250.smushcdn.com/1694534/wp-content/uploads/2021/06/its-a-frontend-is-it-3oth-its-both-backend-i-44043917-1.png?lossy=1&strip=1&webp=1" width="250" v-click="3"/>
</div>

<v-clicks>

-   **Client-side code** runs on the user's computer — when a web page is viewed, the page's client-side code is downloaded, then run and displayed by the browser

-   **Server-side code** runs on the server - create web server, connect to the Database, talk with 3rd party services, render templates, etc. - powered by **Node.js**

</v-clicks>

---

# JavaScript basic

https://codepen.io/baohuynhlam/pen/abGGRZG

```js
const num = 3.1;
let str = "Hello";
const person = {
    key: "value",
    name: "Asher",
    age: 35
};

const arr = [1, 2, 3, 4];
const arr2 = [{}, {}, { battery: "100" }];

function getNumber() {
    return 1.234;
}

const createMessage = (message) => {
    return {
        color: "red",
        text: message
    };
};
const created = createMessage("Hello");
const {color, text} = createMessage("World");
```
---

# Javscript basic

```js
let sum = 0;
for (let i = 0; i < 10; i++) {
    sum += i;
}

while (isFormInValid) {
  showErrorMessage();
}

const templateString = `${created.color} *-* ${getNumber()}`;

arr.forEach((arrElement) => {
  console.log(arr + 1)
})

arr.map((arrElement) => {return arrElement * 2})

for (element of arr) {
  if (element % 2 === 0) {
    console.log("This is odd");
  }
}

for (key in object) {}
```
---

# DOM API

https://codepen.io/baohuynhlam/pen/jOxxeYm

```js
// Select an element
const introElem = document.querySelector(".intro");
console.log(introElem.classList);

// Tamper with the classList
introElem.classList.add("text-huge");

// Eject into space
introElem.remove();

// Create new elements
let newElem = document.createElement("pre");
newElem.innerText = introElem.innerText;
let divElem = document.querySelector("#main");
divElem.appendChild(newElem);

// Changing style
newElem.style["color"] = "#a7b055";
```
