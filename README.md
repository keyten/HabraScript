# Habrahabr Enhancement Suite
Юзерскрипт для Хабрахабра / Гиктаймс.

[Установить](https://raw.githubusercontent.com/keyten/HES/master/hes.user.js) (нужен Greasemonkey или Tampermonkey).

![Скриншот](https://habrastorage.org/files/d1c/3c9/b25/d1c3c9b2532e4158ac6c23317ad04d42.png)

### Текущие возможности:
 - Night Mode ( использован стиль от WaveCut и extempl ).
 - Добавление базового TeX-функционала в редактор.
 - Превращение картинок в «натуральные» формулы (TeX, MathJax).
 - Скрытие постов от определённых авторов из списка ( редакторов Geektimes, etc ), хабов и потоков.
 - Частичное скрытие постов.
 - Скрытие плашки с юзеринфо при наведении на ник пользователя.
 - Замена plaintext-ссылок в комментариях на кликабельные ссылки.
 - Инвертирование тёмных прозрачных картинок (текст, например) для Night Mode.


Установка зависимостей для сборки: 
```
npm install
```

Сборка: 
```
node bin/assembly
```
