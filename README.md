# test_task_virtusystems

Необходимо создать форму обратной связи, с валидацией данных на фронте (Vue или Nuxt) и бекэнде (Laravel)
Заявку сохранять в базе данных.

Дополнительно по желанию: 
1. Возможность прикреплять файл к форме
2. Просмотр отправленных данных в админ панели

Разместите пожалуйста задание на github.com и пришлите ссылку.

Комментарий к выполненному заданию:
1. Из дополнительного реализовано только отправка файла.
2. VueJs находятся в папке resources/frontend

Что, на мой взгляд, можно сделать лучше:
1. Сделать кастомную валидацию для проверки файла на стороне frontend.
2. Сделать обработку ошибок валидации, которые frontend получает со стороны backend

Запуск:
1. Указать доступы к бд в .env файле
2. php artisan migrate
3. cd resources/frontend && yarn dev