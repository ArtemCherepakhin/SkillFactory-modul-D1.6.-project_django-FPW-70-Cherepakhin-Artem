В данном проекте были выполнены следующие пункты:
1. Создан проект Django.
2. Добавлено в него 3 статические страницы(first_page, next_page, finish_page.).
3. На странице next_page контент повторяется 2 раза без изменения content (два раза прописано {{ flatpage.content }}).
4. Одна из страниц на сайте доступна только админу (только вошедшему пользователю).
5. На следующих страницах(next_page, finish_page.) изменены шрифты и размеры текста.
6. Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными.
7. Статические файлы Bootstrap загружаются через теги {% load static %} и {% static %}.
