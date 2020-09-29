# lifehacks

---

## delete arrows from input type number in Chrome, Safari, Edge, Opera
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
    -webkit-appearance: none;
    margin: 0
}

## delete arrows from input type number in Firefox
input[type=number] {
  -moz-appearance:textfield;
}

---

## delete blue mark of tap in mobile version
-webkit-tap-highlight-color: transparent

---

## hide scroll

### chrome, safari
.container::-webkit-scrollbar { width: 0; }

### ie 10+
.container { -ms-overflow-style: none; }

### ff
.container { overflow: -moz-scrollbars-none; }

---

## Scroll style for chrome, yandex, safari, opera

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

---

## Scroll style for ff

html, body {
    scrollbar-color: #458245 #714826;     /* «цвет ползунка» «цвет полосы скроллбара» */
    scrollbar-width: auto | thin | none;  /* толщина */
}

---

## picture with gradient
background: linear-gradient(0deg, #fff,rgba(255,255,255, 0.6) 50%, #222), url("https://preziland.com/wp-content/uploads/Infographics-rainbow-diagram-Prezi-template-1600x900.png") 50%/75px;

---

## fix problem of width fit-content in IE
margin: 10px auto 10px 10px;

---

## Простой компонент (сообщение в tot_systems):
import React from 'react';
export default ({ user, update, index }) => {
  return (
    <tr onClick={() => update({ active: index })}>
      <td><img src={`images/${user.image}.svg`} className="user-image" /></td>
      <td>{user.name}</td>
      <td>{user.age}</td>
      <td>8 {user.phone}</td>
    </tr>
  );
};

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