# lifehacks

//   // delete arrows from input type number in Chrome, Safari, Edge, Opera
// input::-webkit-outer-spin-button,
// input::-webkit-inner-spin-button {
//     -webkit-appearance: none;
//     margin: 0
// }

// // delete arrows from input type number in Firefox
// input[type=number] {
//   -moz-appearance:textfield;
// }

//delete blue mark of tap in mobile version
// -webkit-tap-highlight-color: transparent

// /* hide scroll */
// /* chrome, safari */
// .container::-webkit-scrollbar { width: 0; }
// /* ie 10+ */
// .container { -ms-overflow-style: none; }
// /* ff */
// .container { overflow: -moz-scrollbars-none; }

// picture with gradient
//  background: linear-gradient(0deg, #fff,rgba(255,255,255, 0.6) 50%, #222), url("https://preziland.com/wp-content/uploads/Infographics-rainbow-diagram-Prezi-template-1600x900.png") 50%/75px;

// //fix problem of width fit-content in IE
// margin: 10px auto 10px 10px;

//Вот таким образом реализовать просчтой компонент (сообщение в tot_systems):
// import React from 'react';
// export default ({ user, update, index }) => {
//   return (
//     <tr onClick={() => update({ active: index })}>
//       <td><img src={`images/${user.image}.svg`} className="user-image" /></td>
//       <td>{user.name}</td>
//       <td>{user.age}</td>
//       <td>8 {user.phone}</td>
//     </tr>
//   );
// };