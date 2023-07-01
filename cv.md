# **Литвиненко Николай**
### **Начинающий Front-end разработчик** 
********************
#### **Контактная информация**
#### **Телефон:** +7(996) 417-90-01
#### **Электронная почта:** litvinenko_n.v@mail.ru
#### **Telegram:** litvinenko_n.v
#### **GitHub:** https://github.com/litvinenko88 
***************************
### **Коротко о себе**
В последние годы я работаю по другой специальности.
Front-end разработку изучаю самостоятельно с 2022г. Проходил именно авторские курсы от действующих специалистов в IT, 
читал книги, статьи по разработки и технологиям. Хочу разрабатывать web-приложения и mobail-приложения
### **Мой навыки**
За это время я изучил:
* HTML
* CSS
* SASS
* JAVASCRIPT
* БМ-технологию от яндекс  
* ООП 
* Асинхронный JavaScript 
* Axios 
* WEBPACK
* REACT уже изучаю
### **Пример кода**
```
 function calculationEquationGenerator() {
  let getRandomNumber = Math.floor(Math.random() * 10) + 1;
  let nam1 = getRandomNumber;
  let nam2 = nam1 * getRandomNumber;
  let incorrectAnswer1 = Math.floor(Math.random() * 10);
  let incorrectAnswer2 = Math.floor(Math.random() * 10);
  let number1 = document.querySelector(".equation__num1");
  let number2 = document.querySelector(".equation__num2");
  rightAnswer = nam1 / nam2;

  if (nam1 < nam2) {
    rightAnswer = nam2 / nam1;
  } else {
    rightAnswer = nam1 / nam2;
  }

  let equation1 = nam1 > nam2 ? nam2 : nam1;
  let equation2 = nam2 < nam1 ? nam1 : nam2;

  number1.textContent = equation2;
  number2.textContent = equation1;

  allAnswer = [rightAnswer, incorrectAnswer1, incorrectAnswer2];

  let answerRandom = allAnswer
    .map((value) => ({ value, sort: Math.random() }))
    .sort((a, b) => a.sort - b.sort)
    .map(({ value }) => value);

  answer1.textContent = answerRandom[0];
  answer2.textContent = answerRandom[1];
  answer3.textContent = answerRandom[2];
}
```
### **Курсы**
* Современный JavaScript с нуля до Junior-специалиста
* Современный React
* Webpack
* Адаптивная верстка сайтов
### **Образование**
* Ставропольский политехнический колледж
  + Прораб
* Дополнительное образование
  + Интернет маркетолог 
## **Язык**
* Русский
* Английский 0
