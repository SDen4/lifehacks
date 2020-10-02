# lifehacks
---

## delete arrows from input type number in Chrome, Safari, Edge, Opera
```sh
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
    -webkit-appearance: none;
    margin: 0;
}
```

## delete arrows from input type number in Firefox
```sh
input[type=number] {
  -moz-appearance:textfield;
}
```
---

## delete blue mark of tap in mobile version
```sh
-webkit-tap-highlight-color: transparent;
```
---

## hide scroll
### chrome, safari
```sh
.container::-webkit-scrollbar { width: 0 }
```
### ie 10+
```sh
.container { -ms-overflow-style: none; }
```
### ff
```sh
.container { overflow: -moz-scrollbars-none; }
```
---

## Scroll style for chrome, yandex, safari, opera
```sh
::-webkit-scrollbar {
    width: 10px; //scroll width
    background-color: red; //scroll bg color
    border-radius: 5px; //scroll border radius
}
::-webkit-scrollbar-thumb {
    background-color: 10xp; //scroll thumb color
    border-radius: 5px; //scroll thumb border radius
}
::-webkit-scrollbar-thumb:hover { //thumbs hover
    background-color: #253861; //thumbs hover color
}

others: https://only-to-top.ru/blog/coding/2020-01-31-stilizaciya-skrolla-css.html
```
---

## Scroll style for ff
```sh
html, body {
    scrollbar-color: #458245 #714826;     /* «цвет ползунка» «цвет полосы скроллбара» */
    scrollbar-width: auto | thin | none;  /* толщина */
}
```
---

## picture with gradient
```sh
background: linear-gradient(0deg, #fff, rgba(255,255,255, 0.6) 50%, #222), url("https://preziland.com/wp-content/uploads/Infographics-rainbow-diagram-Prezi-template-1600x900.png") 50%/75px;
```
---

## fix problem of width fit-content in IE
```sh
margin: 10px auto 10px 10px;
```
---

## Простой компонент (сообщение в tot_systems):
```sh
import React from 'react';
export default ({ user, update, index }) => {
  return (
      <li className="user__item">
        ...
      </li>
  );
};
```
---

## Backgroung smooth scale change

https://codepen.io/SDen4/pen/gOrBGKv

---

## CSS Parallax

https://codepen.io/SDen4/pen/oNxPOmX

---

## Date & time

https://codepen.io/SDen4/details/RwaLdGy

---

## Hover works after second mouse move

https://codepen.io/SDen4/pen/QWNpKvY

---

## Generator CSS code of TOR (gradient)

https://codepen.io/SDen4/pen/LYGaEep

---

## glare button

https://codepen.io/SDen4/pen/mdVxmWx


## github pages
```sh
git add dist && git commit -m "Initial dist subtree commit"
git subtree push --prefix dist origin gh-pages
```

---

## Star rating

https://codepen.io/SDen4/pen/zYqVJQx

---
