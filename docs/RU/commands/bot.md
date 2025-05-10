# Команда: Bot  
<sup>Автор: [@ItzKITb](https://twitch.tv/itzkitb)</sup>  

## 📝 Описание  
Главная команда для управления ботом. Позволяет выполнять широкий спектр действий: изменять язык интерфейса, управлять валютой, банить/разбанить пользователей, добавлять/удалять каналы, назначать модераторов и многое другое.  

## ⚙️ Параметры  
| Характеристика        | Значение                     |  
|-----------------------|------------------------------|  
| **Псевдонимы**        | `bot`, `bt`, `бот`, `бт`, `main`, `start`, `старт`, `главная`, `info`, `инфо`, `information`, `информация` |  
| **Аргументы**         | `lang (set [en/ru])`, `invite`, `currency (adddollars [int])`, `ban [username] (reason)`, `pardon [username]`, `rejoinchannel [channel]`, `addchannel [channel]`, `delchannel [channel]`, `joinchannel [channel]`, `leavechannel [channel]`, `modadd [username]`, `demod [username]` |  
| **Перезарядка**       | - Пользователь: `10 секунд`<br>- Канал: `5 секунд` |  
| **Доступ только для** | - Модераторы бота: ❌<br>- Разработчики: ✅ (ограниченные функции)<br>- Модераторы канала: ✅ (ограниченные функции) |  
| **Дата создания**     | 07/04/2024 (ДД/ММ/ГГГГ)      |  
| **Платформы**         | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ce/Twitch_logo_2019.svg/512px-Twitch_logo_2019.svg.png" width="16"> Twitch<br><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/512px-Telegram_2019_Logo.svg.png" width="16"> Telegram<br><img src="https://upload.wikimedia.org/wikipedia/ru/thumb/b/b7/Discord_logo_svg.svg/675px-Discord_logo_svg.svg.png" width="16"> Discord |  

## 💬 Пример использования  
```
ItzKITЬ: _bot 
(Replying to @ItzKITЬ: _bot) butterBror: 👋 Hello! Commands: itzkitb.lol/bot

ItzKITЬ: _bot lang get 
(Replying to @ItzKITЬ: _bot lang get) butterBror: 🏳️ You have English language set

ItzKITЬ: _bot lang set en 
(Replying to @ItzKITЬ: _bot lang set en) butterBror: ✅ English language is set 

ItzKITЬ: _bot invite 
(Replying to @ItzKITЬ: _bot invite) butterBror: ✅ Account verified! Wait for manual check for adding 
```  

### 🔒 Ограничения доступа  
- **Модераторы канала**: могут использовать команды `ban`, `pardon`, `rejoinchannel`  
- **Разработчики**: имеют полный доступ ко всем функциям  
- **Пользователи**: без прав могут использовать команды `lang`, `currency`, `invite`  