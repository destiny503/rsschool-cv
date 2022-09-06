## Рахматуллин Артур
Frontend-разработчик, 23 года.

### Контакты

**Почта:**  
503destiny503@gmail.com

**Telegram:**  
@destiny503

**Никнейм на Discord-сервере RS School:**  
Arthur R. (@destiny503)  

### О себе

В средней школе решил, что хочу связать свою жизнь с программированием.  
Успешно сдал экзамены и поступил в университет на программиста.  
Планирую дальше развиваться как специалист и повышать свою квалификацию.🚀

### Мой стек технологий

* HTML
    + HTML5, семантическая вёрстка, BEM, Figma

* CSS
    + CSS3, Flexbox, Grid, Sass/SCSS, Mobile first, адаптив

* JavaScript
    + ES6, *ReactJS (в процессе)*

* VCS
    + Git, GitHub

* Прочее
    + Prettier

### Codewars

**Who likes it? (6 kyu)**  
You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.  
Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:  
[]                                -->  "no one likes this"  
["Peter"]                         -->  "Peter likes this"  
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"  
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"  
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"  
*Note: For 4 or more names, the number in "and 2 others" simply increases.*

**Solution:**
```
function likes(names) {
  switch(names.length) {
  case 0:
    return "no one likes this"
    break

  case 1:
    return names[0] + " likes this"
    break

  case 2:
    return names[0] + " and " + names[1] + " like this"
    break

  case 3:
    return names[0] + ", " + names[1] + " and " + names[2] + " like this"
    break

  default:
    return names[0] + ", " + names[1] + " and " + (names.length - 2) + " others like this"
    break
 }
}
```

### Опыт разработки

В моём [GitHub](https://github.com/destiny503) есть несколько небольших учебных проектов (два интернет-магазина, две демо игры, тайм-менеджер),  
также я занимаюсь разработкой ещё одного учебного интернет-магазина.

### Образование

**Поволжский государственный университет телекоммуникаций и информатики**  
Неоконченное высшее образование, учусь на последнем курсе.  
**Прохожу курс по JS в RS School :)**  
**Самостоятельное изучение веб-технологий**

### Английский язык

Согласно [тестированию](https://test.str.by/mod/quiz/view.php?id=1176), мой уровень английского — А2.
Могу гуглить проблемы на английском, разговорный английский теоретически уровнем ниже.
