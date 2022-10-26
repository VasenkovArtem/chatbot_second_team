# Чат-бот "Я всё сам"
 
 Схема работы чат бота:

![Схема](docs/diagram3.png)

Документация(на данный момент: [URL](http://localhost:9191/ws/docs)

## Инструкция по запуску бота
#### Ubuntu
##### Бэкенд
Версия python на момент разработки: ```python3.8```\
Установка всех необходимых пакетов для бэкенд части командой:```pip install -r requirements.txt```
Запуск бэкенда:

```
cd ./backend
make
```

Или

```bash
cd ./backend
poetry install
poetry run start
```
##### Фронтенд
Установка Nodejs: ```sudo apt install nodejs```\
Установка последней версии Nodejs:
```
sudo npm install -g n
n latest
```
```hash -r``` если node -v выдает старую версию (версия на момент разработки v18.10.0).\
Далее:

```
cd ./frontend
make
```

Или

```bash
cd ./frontend
npm i
npm run dev
```

#### Windows

