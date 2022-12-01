# Личная настройка сборки Gulp
В сборке настроено минифицирование [ html / js / css ] файлов, установлен препроцессор SASS и PUG. Установлена поддержка TypeScript.

### Файловая структура

    .
    ├── dist                   # Папка сборки
    │   ├── css
    │   │   ├── main.min.css
    │   │   └── main.min.css.map
    │   ├── js
    │   │   ├── main.min.js
    │   │   └── main.min.js.map
    │   ├── img                 # Папка со всеми переработанными изображениями
    │   │   └── ...
    │   └── *.html              # Все html файлы
    ├── src                     # Папка разработки проекта
    │   ├── html
    │   │   ├── HTML            # html без препроцессора
    │   │   │   └── ...
    │   │   └── PUG             # PUG || HTML
    │   │   │   └── ...
    │   ├── img                 # Папка со всеми изображениями
    │   │   └── ...
    │   ├── scripts             # Папка с логикой
    │   │   ├── js              # Логика на js
    │   │   │   └── ...
    │   │   └── ts              # TypeScript || JS native
    │   │       └── ...
    │   └── styles              # Папка SASS стилей
    │           ├── _**.scss
    │           ├── _libs.scss  # Подключение CSS библиотек
    │           └── ...
    ├── .editorconfig
    └── ...

Файлы .keep затычки для github для создания пустых папок.
