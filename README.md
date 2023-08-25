﻿# Tasks of React
task's solves of React from daruse.ru

## Задание про пропсам и компонентам
1. Создать компоненты:  
   - [x] [header](createComponents/Header.js) - шапка, принимает логотип (ссылка на любую картинку в инете) и         название сайта  
   - [x] [nav](createComponents/Nav.js) - пункты меню (штук 5 передай в виде массива [{title: 'Новости', link: '       /news'}, {...}])  
   - [x] [footer]() - копирайты и динимически вычисляемый год: @copyright все права защищены {текущий год} год.
2. Создать компонент content - и в нем вывести следующие компоненты (ну только попроще с версткой):
   https://bootstrap-4.ru/docs/4.3.1/components/alerts/
   - [x] [colorText] () - принимает текст и разные цветовые стили
   https://bootstrap-4.ru/docs/4.3.1/components/buttons/
   - [x] [button] () - принимает стиль и текст кнопки, type (submit, button или ссылка), если ссылка, то тег а и ещё    атрибут href
   https://bootstrap-4.ru/docs/4.3.1/components/card/
   - [x] [card] () - принимает ссылку на картинку и текст вместе с html-кодом
   https://bootstrap-4.ru/docs/4.3.1/components/breadcrumb/
   - [x] [bradcrumbNav] () - принимает массив такого же типа как и nav компонент
3. - [ ] []( ) Написать компонент для создания заголовков Title, где мы передаем текст заголовка, размер и цвет (черный по дефолту, красный или синий)
   - [ ] []( ) Написать компонент для простых Input, который принимает type (text, password...), placeholder, value. (Оформи как и Bootstrap инпуты)
4. - [ ] []( ) http://prntscr.com/q7m7vd Написать компонент по рейтингу, он принимает два пропса, 1 - максимальное количество звезд, 2 - сколько выбрано звезд. На скрине максмум 4 звезды, а выбрано 3
5. - [ ] []( ) http://prntscr.com/q7m028 Сделать компонент для тегов, теги мы отправляем в таком формате:

  tags = [
    { title: 'Тег №1', href: 'http://link1.ru'},
    { title: 'Тег №2', href: 'http://link2.ru'},
    { title: 'Тег №3', href: 'http://link3.ru'},
  ]
6. - [ ] []( ) https://bootstrap-4.ru/docs/4.3.1/components/breadcrumb/. Передаем массив объектов с ссылками (штук 5   передай в виде массива [{title: 'Новости', link: '/news'}, {...}])

7. - [ ] []( ) https://bootstrap-4.ru/docs/4.3.1/components/pagination/ Принимает два пропса, 1 - countArticles(Число (якобы материалов)), 2 - limit (Сколько Выводить на страницу). Например если мы передали countArticles=49, limits=10, то у нас будут кнопки = Previous 1 2 3 4 5 Next (То есть якобы на каждую страницу по 10 материалов, поэтому страниц 5 всего, так как мы указали, что выводить по 10 на страницу)  

## Задание про состояниям
1. - [ ] []( ) Создать любой компонент и выполнить в нем код по этой ссылке (3.12.2.1 Хук состояния), надо примерно понять как это работает.
  Можно же в этом же компонент создать новые состояния, например:
  const [countSecond, setCountSecond] = useState(0);
  Также добавь кнопку, которая будет увеличивать countSecond на 1, но ниже выводите ещё текст в параграфе:
  Count меньше 10" или "count больше 10" (для этого нужно использовать тернарный оператор, примеры тут
  Создать новое состояние countThird, и две кнопки, одна прибавляет значение на 1, а другая уменьшает на 1, примерно так, только можно попроще.
  Создать новое состояние countFourth, и три кнопки, одна увеличивает на 1, другая на 5, третья на 10, четверная умножается сама на себя
