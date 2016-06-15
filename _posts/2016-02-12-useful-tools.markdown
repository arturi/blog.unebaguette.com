---
layout: post
title:  "Useful Tools for Web Design"
date:   2016-02-12 12:00:37 +0300
author: "Artur Paikin"
---

*When designing new projects at Baguette we rely on a bunch of tools that make our work easier and more pleasant. Today we are sharing what’ve learned over the last 5 years.*

### 1. Color and Illustrations

* **[Crayon CSS](http://riccardoscalco.github.io/crayon/)** — wonderful color palette with easy to remember names — `banana`, `asparagus`, `caribbeangreen` и `frostbite`. Desginers and developers will thank you.

* **[Swiss Color](http://swisscolors.net/)** — one more minimalistic color collections, just colors this time, no names.

* **[Name That Color](http://chir.ag/projects/name-that-color/)** — pick a color or enter its code and this service will pick a nice poetic title for it.

* Many have probably heard of **[Unsplash](https://unsplash.com/)** — a large collection of free pictures. But there is one more service that extends that functionality — **[Unsplash.it](https://unsplash.it/)**. In it, you can easily crop any photo “on the fly” (`https://unsplash.it/200/300`), display a random (`https://unsplash.it/200/300/?random`) or blurred (`https://unsplash.it/200/300/?blur`) image. Have a look.

### 2. Icons
* **[The Noun Project](https://thenounproject.com/)** — самая популярная коллекция иконок, на любое слово можно найти иконку. Есть бесплатные, но чаще всего условно бесплатные: заплатите $2 (большая часть денег пойдет автору) или используйте бесплатно, но с указанием авторства. Мой любимый иконочный ресурс.

* **[The Noun Project](https://thenounproject.com/)** — the most popular icon collection, you can literally find an icon for every noun. There are free onces, but most are “free and give creadit” or “purchase for $2” (most of the money goes towards the designer), which is fair. My favorite icon resourse by far.

* **[IcoMoon](https://icomoon.io/app/)** — searches a large collection of various paid and free icons, exports them to an SVG format.

### 3. Fonts
* **[Google Webfonts Inspiration](http://tobiasahlin.com/typesource/)**, **[Hello Happy](http://hellohappy.org/beautiful-web-type/)**, **[Fontpair](http://fontpair.co/)** — nice font pairings of free fonts for your inspiration.

* **[Font CDN](http://fontcdn.org/)** — displays any phraze you type in a nice manner, using different fonts from the Google collection. 

### 4. Vector graphics

I use **[Sketch](http://sketchapp.com)**, and tend to like it quite a lot. And I’m not the only one. Unfortunately, it is Mac-only for now. For Windows and Linux there is Illustrator and Inkscape.

There are quite a few cool plugins for Sketch, I’ll highlight the following:

* **[Craft](https://labs.invisionapp.com/craft)** — adds real data to your mockups — photos, names, titles, copy. Capable of multiplying user’s profile 20 times and add a different set of data to each one, while aligning everything to your grid. Pretty neat and magical, [take a look](https://medium.com/minitheory-design/holy-sh-t-designing-with-real-data-in-real-time-in-sketch-and-photoshop-1b3610c77a59#.7zvndpqm3).

* **[Compo](https://github.com/romashamin/compo-sketch)** — превращает сгруппированый объект в умный компонент, например, кнопку, которая сама увиличится в ширину, если текст станет больше. Поддерживает привязку выравнивания по краю и настройку отступов как в CSS. [Обзор](https://evilmartians.com/chronicles/compo-sketch).

* **[Compo](https://github.com/romashamin/compo-sketch)** — turns a grouped object into a smart component, say, a button, that will grow in width automagically, if the text grows bigger. Support snapping to edges and adjusing padding, like in CSS. [Review](https://evilmartians.com/chronicles/compo-sketch).

* **[Typograph](http://tpgrf.ru/)** for Sketch. Correct hyphens, quotes, phone number formatting — everything you wished for.

### 5. Layout and Code Editor

I’m talking about **[Atom](https://atom.io/)**, of course. I used sublime before, but Atom is cooler, though a bit slower. [Best plugins](http://www.threechords.org/blog/my-atom-setup/) were picked by the Three Chords, I’ll just mention a few:

* **[Pigments](https://github.com/abe33/atom-pigments)** — shows a tiny circle of a color next to it’s hex code.
* **[Color Picker](https://atom.io/packages/color-picker)** — let’s you pick a color without having to leave the editor.
* **[Autocomplete Paths](https://atom.io/packages/autocomplete-paths)** — autocompletes paths to your assets, according to your project folder.

### 6. Grid

Мне нравится [CSS-сетка Адама Каплана](http://adamkaplan.me/grid/) и его анализ [сеток год спустя](http://adamkaplan.me/blog/grid-retrospective). Я обычно не использую такие готовые сетки для верстки сайтов или интерфейсов, а задаю семантические классы и в них уже нужные размеры. Но сетка полезна, например, когда верстаешь блог и нужно дать автору возможность самому легко сверстать несколько колонок.

I like [CSS-grid by Adam Kaplan](http://adamkaplan.me/grid/) and his [grid retrospective](http://adamkaplan.me/blog/grid-retrospective) a year later. Usually I don’t use ready-made grids like this for websites or interfaces, but instead set a semantic classes and construct grids inside those. But the grid is useful, for example, when you are making a blog layout and you want to give the author an ability to add a few columns himself.

Bootstrap has a [pretty decent grid](http://v4-alpha.getbootstrap.com/layout/grid/#quick-start-example) for inspiration, but to my taste it’s a tad heavy for most usecases. And here is a nice usage example in an article “[Why are we writing a book using InDesign](http://book.glvrd.ru/indesign/)”.

### 7. Chrome Dev Tools
Obvious, yet surreal. Read a [review of useful features](https://medium.com/jotform-form-builder/how-to-use-chrome-devtools-like-a-pro-b9bd414870e3#.a04s1gu1s), most of those I didn’t know about, despite using it daily. My favorite picks are: Expand All Child Nodes, color palettes (especially “Page Colors” — the palette is auto-generated based on the colors of the current page), and access to selected element by way of using `$0`.

### 8. Finally
* **[Instagram Filters](https://una.im/CSSgram/)** with CSS
* **[Animate CSS](http://daneden.github.io/animate.css/)** — best library for CSS animations
* **[U.S. Web Design Standards](https://standards.usa.gov/accordions/)** — styleguide for buttons, typography, colors. Insightful reading.
* **[Give ’n’ go](http://give-n-go.co/)** — Dribbble mockups turned into HTML/CSS
* **[SVGO](https://github.com/svg/svgo)** — exported an icon from Sketch, or, oh-my, Illustrator? Put it through SVGO — it will strip out all trash, compress it and make it awesome. Not a fan of the command line? There is [an app for that](https://github.com/svg/svgo-gui). And, while we are on the image optimization subject, [ImageOptim](https://imageoptim.com/mac) is my favorite: JPG, PNG, GIF — it can handle and optimize it all for you. Enjoy.
