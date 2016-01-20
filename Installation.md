## Порядок установки ##

1. Установите права доступа 0777 на перечисленные директории: `wb-cache`, `wb-cache/liked_posts/`, `wb-cache/popular_tags/`, `wb-cache/tags/`, `wb-content/`, `wb-content/avatars/`

2. Укажите параметры подключения к базе данных MySQL в файле `wb-system/configuration/database.php`

3. Отредактируйте конфигурацию CMS в файле `wb-system/configuration/system.php`

4. Зарегистрируйтесь на сайте, запомните свой ID

5. Получите права администратора, выполнив SQL-запрос `UPDATE users SET user_admin_privilege = '1' WHERE user_id = ваш_ID`