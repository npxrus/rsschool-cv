# Evgeniy Mironov
### Junior Frontend Developer
---

## Contacts:
- **Email** - [npxrus@yandex.com](mailto:npxrus@yandex.com)
- **Telegram** - [@npxrus](https://t.me/npxrus)
- **Discord** - [Evgeniy Mironov (@npxrus)](https://discordapp.com/users/811575543115022396/)
- **GitHub** - [@npxrus](https://github.com/npxrus)
---

## About:
My goal is to master frontend and backend development at a professional level and become a fullstack Javascript developer.

---

## Professional skills:
- *CVS* - git
- *CVS services* - GitHub, GitLab
- *git tools* - cli, GitHub Desktop, GitKraken, GitHub CLI
- *Graphics* - Figma
- *Code editor* - VS Code
- *Frontend* - HTML, CSS, Javascript
- *Frontend frameworks* - ReactJS
- *Frontend tools* - SASS, PostCSS, Gulp, Webpack, Parcel
- *Backend* - NodeJS

---

## Code:
**Task from [Codewars](https://www.codewars.com/kata/563700da1ac8be8f1e0000dc)**: *Create a function that takes one positive three digit integer and rearranges its digits to get the maximum possible number. Assume that the argument is an integer.*

**Solution**:
```js
var maxRedigit = function(num) {
  if (typeof num !== 'number' || num <= 0 || num > 999 || num <= 100) {
    return null;
  } else {
    return parseInt(num.toString().split('').sort((a, b) => b - a).join(''));
  }
};
```

---