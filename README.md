<!-- @format -->

# webdev

Сборка Gulp4 с плагинами для разработки вебпроектов.

Что есть в сборке:

- компилятор для препроцессора scss/sass;
- минификация готового css;
- автопрефиксер;
- импорт одних файлов в другие, который позволяет собирать html из модулей;
- babel;
- конвертация шрифтов из ttf в eot, woff и woff2;
- сжатие изображений;
- для живого обновления страниц - browsersync;
- карта исходников для отображения в браузере, из какого scss взят кусок css;
- вывод размеров файлов в консоли во время работы gulp;
- автоматичская отправка на хостинг по FTP/SFTP.

Тасклист следующей версии:

- автоматическое формирование и подключение @font-face;
- адекватное сжатие png через pngquant;
- сжатие svg;
- создание png и svg-спрайтов;
- разделение задач на dev и build (работа с разными плагинами и вызов разными командами);
- etc.
