# Chat

Небольшое Java приложение, которое можно использоват для общения в пока что только локальной сети

В репозитории лежат серверная и клиентская части
<br/>Серверная часть сделана на Socket'ах, GUI клиентской части сделан с помощью библиотеки Swing

<br>**Принцип работы:**
1. Запускается сервер
2. Запускается нужное количество клиентов
   - Клиент должен пройти аутентификацию
   - При успешном прохождении предоставляется доступ к чату

<br>**Функции:**
- Авторизация
```
/auth login password
```
- Личные сообщения
```
/whisper whom message
```