![image](https://user-images.githubusercontent.com/94482915/175429683-536f18ef-611f-4349-9761-8b8d0a72f172.png)

# Homework checker Telegram bot

### Для чего этот проект:
Бот в Telegram для проверки статуса домашней работы на Яндекс.Практикум.
Бот проверяет статус домашей работы чрез API, присылает уведомления об изменения статуса или ошибок. 
Логирует свою работу.

### Технологии:
- Python 3.7
- Python telegram bot 13.7
- Requests 2.26.0

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```
git@github.com:Andr3w-k/homework_bot.git
```

```
cd homework_bot
```

Шаблон наполнения env-файла:
```
PRACTICUM_TOKEN = '***'
TELEGRAM_TOKEN = '***'
TELEGRAM_CHAT_ID = '***'
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```
Запустить проект:

```
python3 homework.py
```

