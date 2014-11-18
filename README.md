Chordials
=========
## Задачи на ближайшее будущее
### Приложение
    1. Подгружать аккорды к текстам песен в фоновом режиме
    Смотрим, сколько аудиозаписей доступно, инфу по каждой шлём в чапи (artist, song, lhash -- lyrics hash). Чапи проверяет актуальность аккордов (lhash_old == lhash_new) и возвращает musicxml, если аккорды не актуальны. Расширение обновляет тексты песен через VK API.

-------------------------------------------------------------------------------

### Дизайн
    1. Нарисовать иконку для chromium-расширения
    2. Сделать иконки, отображающие статус загрузки аккордов.
       - При запросе к чапи -- idle.
       - Аккорды актуальны или успешно найдены -- success.
       - Не удалось найти -- failed.
    3. Нарисовать иконки для скачивания guitar pro, нот и табов в текстовом виде
