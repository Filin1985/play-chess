# Проект: Шахматный клуб

**Описание проекта**

Данный проект о шахматном клубе в Москве

**Используемые технологии**

- HTML
- CSS
- Flexbox
- Grid
- Responsive Design
- SCSS

Для запуска проекта, необходимо:
1. Инициализировать npm
```
npm init -y
```
2. Установить sass:
```
npm install node-sass
```
3. Прописать в файле package.json:
```
"scripts": {
    "sass": "node-sass -w modules/ -o pages/ --recursive"
  },
```
4. Запустить отслеживание sass:
```
npm run sass
```
