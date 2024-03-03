# Mohamed Nishath Digital Resume

A digital resume website built based on the content from my personal REAL [resume](./assets/Mohamed_Nishath.pdf) 

View live demo here using github pages: [Live Demo](https://nishathmhd.github.io/My-Digital-Portfolio/)

## Dark Mode Preview

<img width="661" alt="NishathPorfolioDark" src="https://github.com/nishathmhd/My-Digital-Portfolio/assets/117710744/3c253515-ffd5-42e1-8d71-a1aa1de9f329">

## Light Mode Preview

<img width="630" alt="NishathPorfolioLight" src="https://github.com/nishathmhd/My-Digital-Portfolio/assets/117710744/ebcec997-b506-44a9-91f9-420dd7e2ccab">

## Switching between color themes

This project includes a dark mode feature for enhanced readability and user experience. By clicking on the toggle button located at the top right corner of the page, users can easily switch between dark and light color themes to suit their preferences. Enjoy seamless navigation and readability with our customizable color themes!

```js
// Dark mode toggle script
const darkModeToggle = document.getElementById('dark-mode-toggle');
const body = document.body;

darkModeToggle.addEventListener('click', () => {
    body.classList.toggle('dark-mode');
});
```
