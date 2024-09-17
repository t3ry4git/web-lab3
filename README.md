# Лабораторна робота №3 "Розробка інтерфейсів користувача Web-додатків засоби фреймворку VueJS" ([звіт](https://docs.google.com/document/d/12AZ_Z90rAtoo4u3Ym9uw6h1NwtImU21f4BPsX7PfcDg/edit?usp=sharing))

## Виконав

Терентьєв Іван Дмитрович КВ-11

## Мета

Ознайомитись із засобами фреймворка VueJS та навчитись створювати асинхронні запити до Web-сервера

## Загальне завдання

Адаптувати програмний код ([ЛР№2](https://github.com/73794449/web-lab2)) до вимог фреймворка VueJS та забезпечити завантаження необхідних даних з Web-сервера

## Інструменти розробки

JavaScript, VueJS, NodeJS, Express, MongoDB, Axios

## Ініціалізація проекту front

```
cd t3-calc
npm install
```

### Компіляція з hot-reload

```
npm run serve
```

### Компіляція

```
npm run build
```

### Фіксинг файлів(LINT)

```
npm run lint
```

## Ініціалізація проекту back

```
cd t3-back
npm install
```

Не забудьте замінити db url на свій якщо використовуєте не локальну базу даних.

### Компіляція

```
node ./server.js
```

### Компіляція з hot-reload

```
npm install --save-dev nodemon
nodemon ./server.js
```

## Оцінювання 
Робота: 20/20

Захист: відсутній