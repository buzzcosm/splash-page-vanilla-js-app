# Splash Page

Exercise Project of `ZTM` Cours on Udemy ([JavaScript Web Projects: 20 Projects to Build Your Portfolio](https://www.udemy.com/course/javascript-web-projects-to-build-your-portfolio-resume)).

## Description

Programmed in vanilla-js. Working with Figma design.

> Great algorithm for switching the background!

```js
function changeBackground(number) {
  // Check if background is already showing
  let previousBackground;
  if (body.className) {
    previousBackground = body.className;
  }
  // Reset CSS class for body
  body.className = '';
  switch (number) {
    case '1':
      return (previousBackground === 'background-1') ? false : body.classList.add('background-1');
    case '2':
      return (previousBackground === 'background-2') ? false : body.classList.add('background-2');
    case '3':
      return (previousBackground === 'background-3') ? false : body.classList.add('background-3');
    default:
      break;
  }
}
```

## Interesting things

- [Medium (Article) - Memory leaks in JavaScript](https://medium.com/@lelianto.eko/memory-leaks-in-javascript-and-how-to-prevent-them-96a69de65c31)
- [snyk | learn - Memory leaks](https://learn.snyk.io/lesson/memory-leaks/)

## Useful references

- [Figma - Overview for Developer](https://www.figma.com/best-practices/tips-on-developer-handoff/)
- [Heropatterns - Background Generator](https://heropatterns.com/)
- [uiGradients - Background Generator](https://uigradients.com/#Mystic)
- [W3Schools - JavaScript Switch Statement](https://www.w3schools.com/js/js_switch.asp)
- [Mozilla - Conditional (ternary) operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_operator)