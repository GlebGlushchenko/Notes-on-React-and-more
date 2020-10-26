# Notes on React and more

## React it doesn't hurt...maybe

<b>React<b/>— это JavaScript-библиотека для разработки пользовательского интерфейса.

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/Ogmo.png)

---

### Single Page Application (SPA)

<details><summary>SPA</summary>
<p>

Single Page Application: это веб-приложение или веб-сайт, использующий единственный HTML-документ как оболочку для всех веб-страниц и организующий взаимодействие с пользователем через динамически подгружаемые HTML, CSS, JavaScript, обычно посредством AJAX.

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/SPA.jpg)

</p>
</details>

<hr>

### JSX

<details><summary>JSX</summary>
<p>
  
![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/JSX.jpg)
  
  JSX - это расширение языка JavaScript.
  <br>
  JSX представляет собой объекты.
  <br>
  Babel компилирует JSX в вызовы `React.createElement()`

</p>
</details>
<hr>

### Component

<details><summary>Component</summary>
<p>

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/Component.jpg)

</p>
</details>

<hr>

### Props

<details><summary>Props</summary>
<p>

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/props1.jpg)
![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/props2.jpg)
![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/props3.jpg)

</p>
</details>

<hr>

### Pure Function


![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/Function.png)
<hr>
Pure

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/Pure-function.png)

Dirty

![Image alt](https://github.com/GlebGlushchenko/Notes-on-React-and-more/blob/master/Dirty-function.png)


Для того что бы функция могла называться _чистой_ Pure она должна сочетать в себе несколько свойст

<details><summary><b>Immutable (Иммутабельность, неизменная)</b><p></summary>

Pure Function не должна мутировать данные которые в неё приходят.
Допустим данные пришли из _вне_ и они являються { _Обьектом_ }, то в случае если мы их мутируе _изменим_ в нутри функции { _обьект_ } который пришёл к нам из вне тоже измениться так как, к нам придёт не сам { _Обьект_ }, а лишь ссылка на него.</details>

<details><summary><b>Return</b><p></summary>

Pure Function должна что то вернуть </p></details>

<hr>

_Здесь я буду оставлять свои заметки, связанные с web разработкой в частности с React_

## collapsible markdown?

<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```javascript
alert('Hello world!');
```

</p>
</details>
