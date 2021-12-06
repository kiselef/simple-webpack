# simple-webpack

В директории **dist** находится файл **index.html**, который подключает файл **main.js** (генерится автоматически, в репозитории его нет).

Все js-изменения вносятся в директории **src**, где лежит корневой файл **index.js**. Webpack использует этот файл как точку входа (см. **webpack.config.js:entry**).

Что делать:

```
npm install
npm run build
```

Webpack соберет код в **dist/main.js**, после открыть в браузере файл **dist/index.html**.
