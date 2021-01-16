# Puzzle
Финальный проект по СИТ'у с первого семестра 3 курса.  
Игра в пазлы.

## Задание
Реализовать многостраничное web-приложение, стостоящее минимум из 3 страниц (или landing page).  
Минимальный стек технологий для приложения: 
  - Nginx/Apache2
  - Http
  - JSON
  - HTML (обязательно наличие элементов управления в виде кнопок, элементов ввода)
  - CSS (можно использовать фреймворки Bootstrap/Foundation)
  - Javascript (любые библиотеки, типа JQuery, Select2, Bootstrap и тд...)
  - Ajax
  - Пакетный менеджер (npm/yarn/bower/...)
  - Сборщик (webpack/rollup/parcel/...)
 
В процессе защиты проекта нужно ответить на вопросы:
  1. Почему выбран именно указанный стек технологий?
  2. Как формировался проект, описать этапы.
  3. Для чего нужен тот или иной файл/папка в проекте?
  4. Что делает та или иная строка в коде/разметке/стилях?
  
## Как собрать проект
Установить в корень проекта jQuery, Npm и WebPack.  
В webpack скачать следующие библиотеки: css-loader, style-loader ...  
Использовать webpack.config.js, который лежит в репозитории.  
В package.json в scripts написать:
- ``` build : webpack```
- ``` watch : webpack --mode development --watch```

Собирать проект через:
```bash
npm run build
```
Стартовая страница проекта *puzzle/index.html*  

Демо сайта: https://fuwe.me/puzzle

## Как играть  
Переходим на главную страницу, нажимаем начать. Затем выбираем любую понравившуюся картинку, после чего сайт перекидывает к пазлу. Нужно собрать все кусочки картинки.

