---
layout: post
title:  "Useful Tools for Web Design"
date:   2015-12-07 07:18:37 +0300
author: "Artur Paikin"
---

*When designing new projects at Baguette we rely on a bunch of tools that make our work easier and more pleasant. Today we are sharing what’ve learned over the last 5 years.*

### 1. Color and Illustrations

* **[Crayon CSS](http://riccardoscalco.github.io/crayon/)** — wonderful color palette with easy to remember names — `banana`, `asparagus`, `caribbeangreen` и `frostbite`. Desginers and developers will thank you.

* **[Swiss Color](http://swisscolors.net/)** — one more minimalistic color collections, just colors this time, no names.

* **[Name That Color](http://chir.ag/projects/name-that-color/)** — pick a color or enter its code and this service will pick a nice poetic title for it.

* Многие, наверное, слышали про **[Unsplash](https://unsplash.com/)** — большую коллекцию бесплатных фотографий. Но есть еще один сервис, который дополняет Unsplash — **[Unsplash.it](https://unsplash.it/)**. В нем можно легко обрезать любую понравившуюся картинку «на лету» (`https://unsplash.it/200/300`), отобразить случайную (`https://unsplash.it/200/300/?random`) или размытую (`https://unsplash.it/200/300/?blur`). Посмотрите. 

### 2. Icons
* **[The Noun Project](https://thenounproject.com/)** — самая популярная коллекция иконок, на любое слово можно найти иконку. Есть бесплатные, но чаще всего условно бесплатные: заплатите $2 (большая часть денег пойдет автору) или используйте бесплатно, но с указанием авторства. Мой любимый иконочный ресурс.

* **[IcoMoon](https://icomoon.io/app/)** — ищет по большой коллекции разных платных и бесплатных иконок, экспортирует в векторный формат SVG

### 3. Fonts
* **[Google Webfonts Inspiration](http://tobiasahlin.com/typesource/)**, **[Hello Happy](http://hellohappy.org/beautiful-web-type/)**, **[Fontpair](http://fontpair.co/)** — хорошо сочетаемые пары бесплатных шрифтов для вдохновения.

* **[Font CDN](http://fontcdn.org/)** — красиво показывает любой набранный вами текст разными шрифтами из коллекции Google, удобно выбирать.

### 4. Vector graphics

Я использую **[Sketch](http://sketchapp.com)**, он мне очень нравится. И я не одинок в своих пристрастиях. К сожалению,   пока только для Мака. Для Виндоуса и Линукса есть Иллюстратор и Inkscape.

К Скетчу есть много крутых плагигов, выделю следующие: 

* **[Craft](https://labs.invisionapp.com/craft)** — добавляет в ваши макеты настоящие данные — фото, имена, заголовки, тексты. Может размножить профиль пользователя до двадцати профилей и самостоятельно добавить каждому уникальную фотографию и биографию, выстроив все по сетке. Магия. Посмотрите [обзор](https://medium.com/minitheory-design/holy-sh-t-designing-with-real-data-in-real-time-in-sketch-and-photoshop-1b3610c77a59#.7zvndpqm3).

* **[Compo](https://github.com/romashamin/compo-sketch)** — превращает сгруппированый объект в умный компонент, например, кнопку, которая сама увиличится в ширину, если текст станет больше. Поддерживает привязку выравнивания по краю и настройку отступов как в CSS. [Обзор](https://evilmartians.com/chronicles/compo-sketch).

* **[Типограф](http://tpgrf.ru/)** для Скетча. Правильные кавычки, тире, форматирование телефонных номеров — все в наборе.

### 5. Layour and code editor

Я про **[Atom](https://atom.io/)**, конечно. Раньше был Саблайм, но Атом круче, хоть и медленнее. С [подборкой плагинов](http://www.threechords.org/blog/my-atom-setup/) лучше меня справился автор блога Three Chords, упомяну несколько:

* **[Pigments](https://github.com/abe33/atom-pigments)** — отображает кружочек с цветом рядом с кодом цвета.
* **[Color Picker](https://atom.io/packages/color-picker)** — дает выбрать цвет из палитры не выходя из редактора.
* **[Autocomplete Paths](https://atom.io/packages/autocomplete-paths)** — дополняет пути к картинкам, стилям или чему-то еще, на основе папки проекта.

### 6. Grid

Мне нравится [CSS-сетка Адама Каплана](http://adamkaplan.me/grid/) и его анализ [сеток год спустя](http://adamkaplan.me/blog/grid-retrospective). Я обычно не использую такие готовые сетки для верстки сайтов или интерфейсов, а задаю семантические классы и в них уже нужные размеры. Но сетка полезна, например, когда верстаешь блог и нужно дать автору возможность самому легко сверстать несколько колонок.

В Бутстрапе [неплохая сетка](http://v4-alpha.getbootstrap.com/layout/grid/#quick-start-example) для вдохновения, но, на мой взгляд, тяжеловата для большинства случаев. И вот хороший пример использования в статье «[Зачем мы пишем книгу в Индизайне](http://book.glvrd.ru/indesign/)».

### 7. Chrome Dev Tools
Очевидное, но невероятное. Прочитайте [обзор полезных возможностей](https://medium.com/jotform-form-builder/how-to-use-chrome-devtools-like-a-pro-b9bd414870e3#.a04s1gu1s) Developer Tools, большую часть из которых я совсем не знал, хотя пользуюсь ими почти каждый день. Любимое: Expand All Child Nodes, палитры цветов (особенно «Page Colors» – палитра генерируется автоматически из цветов на открытой страницы), доступ к выбранному элементу по `$0`.

### 8. Finally
* **[Instagram Filters](https://una.im/CSSgram/)** with CSS
* **[Animate CSS](http://daneden.github.io/animate.css/)** — best library for CSS animations
* **[U.S. Web Design Standards](https://standards.usa.gov/accordions/)** — styleguide for buttons, typography, colors. Insightful reading.
* **[Give ’n’ go](http://give-n-go.co/)** — Dribbble mockups turned into HTML/CSS
* **[SVGO](https://github.com/svg/svgo)** — экспортировали иконку из Скетча или, ой, Иллюстратора? Пропустите через SVGO — вырежет лишнее, сожмет, сделает прекрасным. Если не любите консоль, то есть [программка вот](https://github.com/svg/svgo-gui). А раз уж мы про оптимизацию картинок, то [ImageOptim](https://imageoptim.com/mac) мой фаворит: уберет лишнее из JPG, PNG, GIF — все без потери качества.
