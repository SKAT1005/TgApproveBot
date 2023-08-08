<br/>
<p align="center">

  <h3 align="center">
TgApproveBot - Телеграмм бот с открытым исходным кодом
</h3>

  <p align="center">
   Простое и действенное решение для помощи ведения каналов
    <br/>
    <br/>
  </p>
</p>

## Table Of Contents

* [О проекте](#о-проекте)
* [Стек](#стек)
* [Начало работы](#начало-работы)
* [Установка](#установка)
* [Использование](#использование)
* [Авторы](#авторы)

## О проекте

Данный бот принимает заявки в телеграмм каналы/чаты. При подачи заявки в канал бот отправляет пользователю личное
сообщение с просьбой привязать свой TON кошелек к боту. Далее бот проверяет кошелек. Если у аккаунта есть Telegram
Premium или 1 NFT, бот принимает заявку в канал/чат. В ином случае заявка откланяется

## Стек

Данный бот был написан на Python, испрользуя pyTelegramBotAPI, а так же pyTONPublicAPI

## Установка

1. Получите у [BotFather](https://t.me/BotFather) Токен бота и вставьте его в переменную BOT_TOKEN.
2. 
3. Создание виртуального окружения
  <br>`python -m venv venv`</br>
  <br>`python venv\Scripts\activate.bat` - для Windows;</br>
  <br>`python source venv/bin/activate` - для Linux и MacOS.</br>

4. Установите все зависимости, используя команду `pip install -r requirements.txt`


## Использование

1. Создайте телеграмм чат(ы)/канал(ы) и добавьте в них бота, выдав ему права администратора
2. Запустите бота командой `python main.py`


## Авторы

* **Skat1005** - *Developer* - [Skat1005](https://github.com/SKAT1005/) - *Python Backend Developer*
