# GoTo_Challenge_Spring_2017
## Веб-сервис и сам бот
В данный момент веб-сервис размещен по адресу [shtirlets.beget.tech](shtirlets.beget.tech).

Ник бота в telegram: [@gotoschool_bot](https://t.me/gotoschool_bot)<br>
  
  
## Инструкция по установке
1. Установите библиотеку для Python - pyTelegramBotAPI.
> pip install pyTelegramBotAPI<br>
>[pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI)
2. Установите и запустите сервер Apache.
> http://httpd.apache.org/download
3. Откройте папку с проектом в браузере.
> localhost/<путь к папке>/admin
4. Введите **логин**: *admin*, **пароль** : *admin*.
5. Введите токен вашего бота, выданный [@BotFather](https://telegram.me/botfather).
6. Придумайте пароль для админов и пользователей и нажмите кнопку сохранить.
7. Запустите файл gotobot.py в папке bot.
8. Бот готов к работе!


>-------------------------------------------------------------------------------------------------------


## Описание работы с ботом

### Регистрация
После того, как вы запустили файл gotobot.py, напишите своему боту комманду /start. 
Он запросит пароль, введенный вами в веб-сервисе
> *admin* (Пароль для админа)<br>
> *user* (Пароль для юзера)


Регистрация администратора | Регистрация юзера
------------ | -------------
![Регистрация админа](/screenshots/registeradmin.PNG)|![Регистрация юзера](/screenshots/registeruser.PNG)

>-------------------------------------------------------------------------------------------------------


### Основные комманды бота
#### 🛠 Комманды
С помощью кнопки 🛠 Комманды или комманды /help можно узнать доступные тебе комманды и их описание.

Админ | Юзер
------------ | -------------
![Комманды админа](/screenshots/commandsadmin.png)|![Комманды юзера](/screenshots/commandsuser.png)

#### 🗓 Расписание
С помощью кнопки 🗓 Расписание или комманды /schedule можно узнать расписание.

![Расписание](/screenshots/schedule.png)

#### ⛳️ Событие
С помощью кнопки ⛳️ Событие или комманды /event можно узнать текущее событие.

![Событие](/screenshots/event.png)
#### 🏅 Ачивки
С помощью кнопки 🏅 Ачивки или комманды /achives можно просмотреть свои ачивки. Так же, когда выдают ачивку, приходит уведомление.

![Ачивки](/screenshots/achives.png)

#### ❗️ Информация
С помощью кнопки ❗️ Информация или комманды /info можно просмотреть где ты живешь и контактные телефоны

![Startinfo](/screenshots/infofirst.png)

🏡 Где я живу? | ☎️ Контакты
------------ | -------------
![Где я живу](/screenshots/infoadress.png)|![Контакты](/screenshots/infophones.png)

>-------------------------------------------------------------------------------------------------------


### Административный режим бота и его комманды
#### 🔒 Админка
С помощью кнопки 🔒 Админка или комманды /admin вы входите в административный режим.

![Админка](/screenshots/admin.png)

#### 📆 Расписание
С помощью кнопки 📆 Расписание или комманды /editschedule можно редактировать расписание.

Далее нужно подтвертить дальнейшие действия по изменению или же наоборот отлонить.

Админ | Юзер
------------ | -------------
![Подтвердить изменения](/screenshots/confirmeditschedule.png)<br>![Изменение расписания](/screenshots/editschedule.png)|![Расписание у юзера](/screenshots/scheduleuser.png)

#### 🎖 Ачивки
С помощью кнопки 🎖 Ачивки или комманды /editachives можно добавлять, выдавать ачивки

![Работа с ачивками](/screenshots/editachives.png)

#### 🏠 Где я живу?
С помощью кнопки 🏠 Где я живу? или комманды /editadress можно изменять информацию о проживании

![Информация о проживании](/screenshots/editadress.png)

#### 📞 Контакты
С помощью кнопки 📞 Контакты или комманды /editphones можно изменять контактную информацию

![Контактная информация](/screenshots/editphones.png)

#### ✉️ Срочное сообщение
С помощью кнопки ✉️ Срочное сообщение или комманды /quickmessage можно производить срочную рассылку

Админ | Юзер
------------ | -------------
![У админа](/screenshots/messageadmin.png)|![У юзера](/screenshots/messageuser.png)

#### ❌ Выход
С помощью кнопки ❌ Выход или комманды /exit можно выйти из административного режима.

![Выход](/screenshots/exit.png)




>-------------------------------------------------------------------------------------------------------




## Описание работы с веб-сервисом
###  🔧 Настройки (Главная страница)

#### Конфигурация
В полях Токен бота, Админ, Пользователь можно измениять токен бота и пароли админа и юзера соответственно.

![Конфигурация](/screenshots/configure.png)

#### Расписание
Можно изменять расписание.

![Расписание](/screenshots/scheduleweb.png)

#### Контакты
Можно изменять контактную информацию.

![Контакты](/screenshots/contacts.png)


#### Проживание
Можно изменять информацию о проживании.

![Проживание](/screenshots/adressweb.png)

#### Срочное сообщение
Позволяет сделать мнгновенную рассылку.

![Срочное сообщение](/screenshots/messageweb.png)

###  🎯 Квесты
![Квесты](/screenshots/questweb.png)

После запуска всем юзерам прийдет уведомление

![Уведомление](/screenshots/startquest.png)

Далее пользователь проходит квест

![Квест](/screenshots/quest.png)

По завершению квеста одной из комманд админу приходит уведомление

![Уведомление](/screenshots/adminquest.png)






>-------------------------------------------------------------------------------------------------------
# Если возникли какие-либо вопросы
VK: [shtelzerartem](https://vk.com/shtelzerartem)

Telegram: [@shtelzerartem](https://t.me/shtelzerartem)

E-mail: shtirlets@list.ru

