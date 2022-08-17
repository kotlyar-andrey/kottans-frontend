# kottans-frontend progress

## 0. Git Basics

Я уже використовував git у власних проектах. Новими для мене стали команды diff і patch.

У майбутньому планую частіше користуватися гілками, наприклад, при створенні нових фіч.

<details>
  <summary>Скриншоти</summary>
  
  ![Основи: Introduction Sequence](/git/git1.png "Скриншот 1")
  ![Віддалені репозиторії: Push & Pull](/git/git2.png "Скриншот 2")
</details>
<br>

## 1. Linux CLI, and HTTP

Більшість команд, які було роглянуто, я вже знав. Новими для мене стали команди:

- _df_ - перегляд вільного місця на диску
- _ps_ - перегляд процесів (в т.ч. з опцією _aux_, яка дозволяе переглянути всі системні процеси)
- _grep_ - пошук слів у тексті

Здивувала простота викоритання команди _grep_, яку я зустрічав раніше, але погано розумів її призначення.

<details>
  <summary>Скриншоти</summary>
  
  ![Тест 1](/task_linux_cli/linux1.png "Тест 1")
  ![Тест 2](/task_linux_cli/linux2.png "Тест 2")
  ![Тест 3](/task_linux_cli/linux3.png "Тест 3")
  ![Тест 4](/task_linux_cli/linux4.png "Тест 4")
</details>
<br>

## 2. Git Collaboration

Продовжуємо вивчати можливості git. Було цікаво дізнатися про можливості платформи github. Новими для мене стали особливості команд push, fetch і pull.

Раніше я ніколи не використовував команду rebase. І хоч після вивчення матеріалу команда merge мені подобається більше (тому що не перезаписує попередні комміти і історія змін буде виглядати такою, як це і відбувалося насправді, в тій же послідовності), але rebase також може бути корисною. Особливо, коли працюєш над окремою гілкою і за цей час в головній гілці не відбувається ніяких змін. Обов'язково буду користуватися цим у власних проектах.

<details>
  <summary>Скриншоти</summary>

![Тиждень 3](/task_git_collaboration/coursera1.png)
![Тиждень 4](/task_git_collaboration/coursera2.png)
![Практика 1](/task_git_collaboration/learngitbranching1.png "Практика 1")
![Практика 2](/task_git_collaboration/learngitbranching2.png "Практика 2")

</details>
<br>

## 3. Intro to HTML & CSS

Я уже добре знаю цю тему, та все ж було корисно освіжити знання по деяким тонкощам. Наприклад, мені сподобалася формула, як порахувати приорітет стилів при їх конфлікті:

`style=""` => `ID` => `class, pseudo-class, attribuyte` => `# of elements`

<details>
  <summary>Детальніше про пріорітет</summary>

![Пріорітет css правил](/task_html_css_intro/css_priority.png)

</details>
<br>

Була наочно показана різниця між значеннями властивості `box-sizing`:

- `content-box` (значення за замовченням) означає, що підсумковий размір блоку буде дорівнювати вказаному розміру ширини `width` + внутрішні відступи `margin` + межа `border` (те саме для висоти, якщо вона вказана)
- `border-box` означає, що підсумкова ширина буде дорівнювати вказаній `width`, а контент буде мати ширина `width - border - padding`

Зовнішні відступи по ширині додаються, а по висоті - зливаються (підсумковий відступ буде дорівнювати більшому із двух).

Друге та третє завдання (на сайті codecademy) я не робив, оскільки вони занадно прості для мене. "Напишіть тег p після тегу h1" - мого терпіння вистачило лише на виконання першого розділу.

<details>
  <summary>Скриншоти</summary>

![Тиждень 1](/task_html_css_intro/coursera1.png)
![Тиждень 2](/task_html_css_intro/coursera2.png)

</details>
<br>

## 4. Responsive Web Design

Було цікаво ознайомитися з сітками і застосувати нові знання в ігровій формі.

<details>
  <summary>Скриншоти</summary>

![flexbox](/task_responsive_web_design/flex_froggy.png)
![grid](/task_responsive_web_design/grid_garden.png)

</details>
<br>

## 5. HTML & CSS Practice

Новим був метод роботи з чекбоксом, коли його можна сховати, а замість вікористовувати стилізований label

[Code](https://github.com/kotlyar-andrey/html-css-popup) | [Demo](https://kotlyar-andrey.github.io/html-css-popup/)

## 6. JS Basics

Теорія для мене була скоріше повторенням, а от задачі - це те, чого мені не вистачало, а саме застосувати знання до практичних вправ. Особливо спободобалися завдання із останньої группи, довелося помізкувати, але впорався самостійно з усіма.

<details>
  <summary>Скриншоти</summary>

![coursera](/task_js_basics/coursera4.png)
![basic_javascript](/task_js_basics/basic_javascript.png)
![es6_challenges](/task_js_basics/es6_challenges.png)
![basic_data_structures](/task_js_basics/basic_data_structures.png)
![basic_algorithm_scripting](/task_js_basics/basic_algorithm_scripting.png)
![functional_programming](/task_js_basics/functional_programming.png)
![intermediate_algorithm_scripting](/task_js_basics/intermediate_algorithm_scripting.png)

</details>
<br>

## 7. DOM

Практично всі методи для роботи з dom були для мене новими. Було корисно з ними розібратися і застосувати до виконання практичного завдання.

[Code](https://github.com/kotlyar-andrey/dom-ds) | [Demo](https://kotlyar-andrey.github.io/dom-ds/)

<details>
  <summary>Скриншоти</summary>

![coursera](/task_js_dom/coursera.png)
![intermediate_algorithm_scripting](/task_js_dom/intermediate_algorithm_scripting.png)

</details>
<br>

## 8. Building a Tiny JS World

[Code](https://github.com/kotlyar-andrey/a-tiny-JS-world) | [Demo](https://kotlyar-andrey.github.io/a-tiny-JS-world/)
