# CyberPoligon
# BY FSIN team

Презентация проекта:
https://www.figma.com/slides/1jRDn4gpGf69DckXI08D6W/%D0%9F%D1%80%D0%B5%D0%B7%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F-%D0%92%D0%98-%D0%A4%D0%A1%D0%98%D0%9D?node-id=2-79&t=ZKDTXAkv7TXR3rbe-1

Для запуска сайта необходимо скачать и запустить Docker и Node js. 
В VS Code переносим фалы проекта и вводим в терменал команды:
 
//для запуска бд очистка:   docker-compose down -v          
 запуск бд:   docker-compose up -d

 //запуск сервера   node app.js

![photo_2025-04-24_22-37-32](https://github.com/user-attachments/assets/f99ac32d-39a7-444a-95e0-6234dfa60f41)

После чего переходи в браузере на  localhost:8000
![photo_2025-04-24_22-38-35](https://github.com/user-attachments/assets/3ac6fc6a-a010-4004-8652-87f17533905d)

Видим стартовое главное окно

![photo_2025-04-24_22-38-56](https://github.com/user-attachments/assets/28278372-1c7c-41d2-8641-3ba0b5dca908)

В нем для примера уже указаны шаблонные данные Вакансий и Заявок на участие 

![photo_2025-04-24_22-42-29](https://github.com/user-attachments/assets/7ecaae52-6525-412e-9133-a99e76c28d87)

![photo_2025-04-24_22-42-06](https://github.com/user-attachments/assets/b29c3cfe-81e3-4ea3-8ea5-910e9bcdd889)

Чтобы войти используем кнопку Авторизация (но перед этим нужно зарегистрировать пользователя Участник/Организатор)

![photo_2025-04-24_22-48-59](https://github.com/user-attachments/assets/1235dbc2-c964-4ac3-b29a-610aca2f6147)

Регистрация:

![photo_2025-04-24_22-54-44](https://github.com/user-attachments/assets/164c9fb6-6578-4e1f-a1e4-c23f69f6936e)

После входа попадаем в окно профиля:

![photo_2025-04-24_22-55-45](https://github.com/user-attachments/assets/edfb028b-ef0a-48d2-a363-e80d5b1ddf4d)

В меню профиля (за организаторв) можно создать вакансии на турнир

![photo_2025-04-24_22-59-05](https://github.com/user-attachments/assets/66aa0398-f687-4061-b4f4-669d647f6a28)

За участника мы создаем "Заявку" на участие

![photo_2025-04-24_23-10-56](https://github.com/user-attachments/assets/190a777e-8916-462c-996a-8ff74b7ca58c)

И также можем откликнуться на существующую "Вакансию"

![photo_2025-04-24_23-11-41](https://github.com/user-attachments/assets/8a9f6ca6-4b00-4bcd-adfb-a7ef7ccd1b9c)

Что в свою очередь видно в профиле у Организаторов

![photo_2025-04-24_23-12-51](https://github.com/user-attachments/assets/d4b15297-11ea-415d-944b-e356cce2fad2)

И видно активные заявки

![photo_2025-04-24_23-13-34](https://github.com/user-attachments/assets/585aa897-8333-47b7-8909-55de8c05b797)

Помимо пользователей разработан функционал для администраторов в адресной строке перейдем на /admin    (login: admin@admin.admin   Password: Admin-cyberpoligon)

![photo_2025-04-24_23-06-40](https://github.com/user-attachments/assets/bf9c79ea-8c98-4a55-9d95-20b3d690c08a)

У админов подробная информация про все существующие пользователи,соревнования, а также логи кто с кем связывался 

![photo_2025-04-24_23-06-57](https://github.com/user-attachments/assets/e73b6bce-d48d-422c-8a7f-fb3770bf82ab)


![photo_2025-04-24_23-08-30](https://github.com/user-attachments/assets/e9b93a70-fac1-418d-b82b-5123fce52e50)

В админ панели видно взаимодействие всех пользователей (на примере Master и Nik)

![photo_2025-04-24_23-16-06](https://github.com/user-attachments/assets/a7d52ce5-1943-43b6-886e-8497aa4aed75)
