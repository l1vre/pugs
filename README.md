# PUGS
## _Pug + SCSS Template_


Заготовленный шаблон для удобного развёртывания проекта на препроцессорах PUG и SCCS.

## Развёртывание

Сначала склонируем шаблон в папку проекта

```sh
git clone https://github.com/l1vre/pugs.git.
```

Затем установим все необходимые зависимости

```sh
npm i
```

После этого можем приступить к запуску компиляций

```sh
pug ./src/pug/pages/index.pug --watch --out ./
scss ./src/scss/main.scss:./assets/css/style.css --watch --no-source-map --style=compressed
```

Эти команды запустят постоянную компиляцию pug и scss файлов. Для каждого нужно сделать отдельное окно в консоле.
