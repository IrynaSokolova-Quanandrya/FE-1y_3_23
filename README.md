# FE-1y_3_23

- Kahoot

Пригадуємо:

1. що таке тег?
2. Які теги можна вкладати, а які ні?
3. для чого використовуються атрибути?
4. Які існують групи тегів?
5. Що таке блочний тег?
6. Що таке рядковий тег?

ТЕМА: Текст. Стилі для форматування тексту. Шрифти.

1. text-transform: none/capitalize/uppercase/lowercase/inherit/initial;
2. white-space:
   normal/nowrap/pre/pre-wrap/pre-line/break-spaces/inherit/initial;
3. Правило !important
4. Підключення сторонніх шрифтів до розмітки
   - через CDN з видаленого сервера (наприклад Google Fonts) HTML:
   <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

CSS: font-family: 'Montserrat', serif;

- локально, попередньо завантаживши потрібний шрифт на комп'ютер @font-face {
  font-family: 'Wisdom Script'; src: url(../fonts/Wisdom_Script_AJ.otf); src:
  url(../fonts/WisdomScriptAJ.ttf) format("ttf"); }

5. Font - Стилі для шрифтів
6. font-weight: bold|bolder|lighter|normal|100|200|300|400|500|600|700|800|900
7. font-style - накреслення шрифта: звичайний, курсив або нахилений.
8. font-size - розмір шрифта (px, em, rem).
9. line-height - міжрядковий інтервал.
10. text-align - вирівнювання тексту в CSS
11. vertical-align - вертикальне вирівнювання. Ця властивість може
    застосовуватись тільки до рядкових елементів
12. Додаємо шрифти до вебстудії
