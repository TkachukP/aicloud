# Публичный репозиторий ML Space
### Как пользоваться API с помощью Postman:
##### 1. Установка postman 
Удостоверьтесь, что Postman установлен. Postman можно скачать по ссылке ниже:

[Postman Official Website](https://www.postman.com/downloads/)

##### 2. Импорт postman-коллекции ML Space 
1.  Откройте Postman.
2.  Нажмите клавишу **Import**
3.  Выберите вкладку **Link**, и используйте ссылку ниже для импорта:
    
    ```
    https://raw.githubusercontent.com/sbercloud-ai/aicloud/Docs-for-postman/doc/api.postman-collection.json
    ```

    ![import postman collection1](/doc/img/postman_import1.png)

4.  Подтвердите импорт
5.  Установите данные для авторизации в переменные коллекции

    ```
    https://docs.sbercloud.ru/aicloud/mlspace/concepts/api__auth.html#id3
    ```

##### 3. Авторизуйтесь на ML Space
Вызовите самый первый метод коллекции - ```/public/v1/auth/```
 
Теперь можно использовать другие методы коллекции без каких-либо забот об аутентификации - коллекция автоматически подставляет ID/Secret для авторизации
