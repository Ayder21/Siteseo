# OpenAgent Site (Hugo)

## Как запустить локально
1. Установите Hugo: https://gohugo.io/installation/
2. В терминале перейдите в эту папку:
   ```bash
   cd openagent-site
   ```
3. Запустите сервер:
   ```bash
   hugo server -D
   ```
4. Откройте в браузере: http://localhost:1313

## Деплой (GitHub Pages)
1. Создайте репозиторий на GitHub (например, `openagent-site`).
2. Запушьте этот код туда.
3. В настройках репозитория включите GitHub Pages (Source: GitHub Actions).
4. Сайт будет доступен по адресу `ваше-имя.github.io/openagent-site`.

## Контент
- Русские посты: `content/ru/posts/`
- Узбекские посты: `content/uz/posts/`
- Конфиг: `hugo.toml`
