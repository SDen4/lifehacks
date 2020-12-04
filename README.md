# Lifehacks
---

## Delete arrows from input type number in Chrome, Safari, Edge, Opera
```sh
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
    -webkit-appearance: none;
    margin: 0;
}
```

## Delete arrows from input type number in Firefox
```sh
input[type=number] {
  -moz-appearance:textfield;
}
```
---

## Delete blue mark of tap in mobile version
```sh
-webkit-tap-highlight-color: transparent;
```
---

## Hide scroll
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

## Picture with gradient
```sh
background: linear-gradient(0deg, #fff, rgba(255,255,255, 0.6) 50%, #222), url("https://preziland.com/wp-content/uploads/Infographics-rainbow-diagram-Prezi-template-1600x900.png") 50%/75px;
```
---

## Fix problem of width fit-content in IE
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

## Glare button

https://codepen.io/SDen4/pen/mdVxmWx

---

## Github pages
```sh
git add dist && git commit -m "Initial dist subtree commit"
git subtree push --prefix dist origin gh-pages
```

---

## Справочник Github 

https://gist.github.com/Qarc/0573bbce1b963b4d6de2fcd582daf000

---

## Star rating

https://codepen.io/SDen4/pen/zYqVJQx

---

## Tor by CSS

https://codepen.io/SDen4/pen/LYGaEep

---

## Counting checkboxes by pure js

https://codepen.io/SDen4/pen/PoNNdyz

---

## Smooth scroll indicator

https://codepen.io/SDen4/pen/ExjJxmO

---

## Elements smooth scroll appear

https://codepen.io/SDen4/pen/ZEGwRwx

---

## One page scroll

https://codepen.io/SDen4/pen/LYVmNXB

---

## Fixed header

https://codepen.io/SDen4/details/rNVdJgJ

---

## Fixed footer

https://codepen.io/SDen4/pen/YzXeGKx

---

## Simple preloader

https://codepen.io/SDen4/pen/BaNmBYd

---

## Три типа слайдеров на js (бесконечный, плавный конечный, простой конечный)

https://jsfiddle.net/SDen4/q48v679w/latest/

https://jsfiddle.net/SDen4/6r13mx0t/latest/

https://jsfiddle.net/SDen4/xrjyd3g2/latest/

---

## Геометрические фигуры css

https://habr.com/ru/post/126207/

---

## Сopy-protected text

https://codepen.io/SDen4/pen/KKMwqzJ

#### Copy protection
```sh
<body onselectstart="return false">
```

#### Selecting text protection
```sh
<body oncontextmenu="return false">
```

#### Context menu appear protection
```sh
<body oncopy="return false">
```

---

## Word-wrap

```sh
.order__name {
    width: 25%;
    word-wrap: break-word; // Принудительный перенос слова, чтобы поместилось в заданную ширину блока.
}
```

---

## Неразрывный дефис

```sh
&#8209;
```

---

## Different speed of scroll sections

https://codepen.io/SDen4/pen/LYZJGVb?editors=1010

---

## Сlosure example in counter function

https://codepen.io/SDen4/pen/JjKwvZP?editors=0010

---

## The exapmple of constructor function for creation new ojects

https://codepen.io/SDen4/pen/gOMqzGr?editors=0010

---

## Canvas base

https://codepen.io/SDen4/pen/XWjWGqq

---

## Array's copy

```sh
let array = [1,2,3];
let arraysCopy = array.concat();
```

---
