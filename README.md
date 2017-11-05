Webpack + TypeScript starter
---

![example](https://juristr.com/blog/assets/imgs/meetup-intro-angular2/transpiling.png)

Это достаточно простой starter kit. Цель этого репозитория состоит в том, чтобы получить простейшую возможную настройку для работы с Webpack и TypeScript. Развернув себе этот репозиторий, вы сможете дополнитель теми инструментами, которые вам нужны, например, SASS-компиляция, Gzip, Brotli-компрессия. Дополнить тестами свое окружение.

## Features

- [x] Webpack
- [x] TypeScript compilation
- [x] ts-lint
- [x] Webpack Development Server
- [ ] Karma and Jasmine test execution

## How to use

Просто склонируйте репозиторий, а дальше:

```
# Переходим в директорию с проектом
cd  <your-project-name>

# Удаляем `.git` директорию

# установка зависимостей
npm i

# Запуск сборки приложения и веб-сервера:
npm serve

# Сборка приложения без минификации: 
npm run build

# Сборка приложения с минификацией: 
npm run build:prod
```
