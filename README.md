## Разработка веб-приложения "Interno"
## SPA приложение на Vue.js 3.

## Иcпользуемые технологии

- Vue.js 3
- Vuex
- Vue Router
- SCSS
- Flexbox
- Grid
- Git
- Swiper JS library
- JS

## Ссылка на макет проекта
Посмотреть [Макет](<https://www.figma.com/design/y9p9QyiKzvm2lKMUZ6NO3W/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)-(Copy)?node-id=1-5&t=FqZG8vElNl3Gwksg-1>)

## Ссылка на README GitHub Pages
Посмотреть [Github README](<https://alexkhabibov.github.io/final_project/>)

## Ссылка на деплой сайта
Посмотерть [Сайт](<https://final-project-bulnlmcjh-alexkhabibovs-projects.vercel.app>)
 
## Реализованные задачи

1. Применение HTML, CSS, JavaScript, Vue.js.
2. Использование flexbox, Grid, формат изображений svg, png.
3. Использование библиотеки Swiper JS для создания слайдера на странице Project Details (при двойном нажатии на изображение слайдера оно увеличивается для предпросмотра)
4. Реализован компонентный подход для добавления похожих блоков на сайте:
   - Header
   - Footer
   - ArticleCard
   - BlackButton
   - Navigation
   - Pagination
   - Slider
5. Все ссылки работают через VueRouting и являются переходами на страницы, указанные в ТЗ. Нерабочая ссылка ведет на страницу NotFound (404).
6. На странице Blog
   - Реализована пагинация по 6 элементов ( "Articles & News")
   - Подгружается последний добавленный пост из статей и новостей ("Latest Post")

7. На странице Blog Details
- Добавлены несколько произвольных статей, с описанием. По нажатию на кнопки в разделе «Tags» происходит сортировка статей по хештегам "Kitchen", "Bedroom", "Building", "Architecture", "Kitchen Planning".

8. На странице Project ("Our Project)
   - Реализована пагинация для перемещения по страницам в категориях "Bathroom", "BedRoom", "Kitchen", "LivingArea".
   - Добавлен функционал лайков (звёздочки). При наведении на любой компонент проекта изначально звёздочка прозрачная, при нажатии на неё, она окрашивается оранжевым цветом.
9. Кнопка «Back to home» на странице NotFound(404) ведет на главную страницу.
10. Сайт выполнен в десктопной версии.



## Настройка проекта

```
npm install
```

### Компиляция и выполнение горячей перезагрузки для разработки

```
npm run serve
```

### Компиляция и сжатие для продакшена

```
npm run build
```

### Настройка конфигурации

[Configuration Reference](https://cli.vuejs.org/config/)
