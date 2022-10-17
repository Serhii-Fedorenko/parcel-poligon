1.Редактируем скрипт build и добавляем --public-url /имя_репозитория/
2.Редактрируем в package.json поле "homepage": "https://ваше_имя.github.io/имя_репозитория"
3.Устанавливаем пакет npm install gh-pages
4.Добавляем npm-скрипты
- "deploy": "gh-pages -d dist"
- "predeploy": "npm run build"
 
