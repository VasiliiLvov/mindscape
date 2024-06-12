# MindScape

Приложение для хранения своих мыслей

## Содержание

- [Разработка](#разработка)
- [Изменения](#изменения)

## Разработка

### Требования

Для установки и запуска проекта, необходим [NodeJS](https://nodejs.org/) v8+.

### Установка зависимостей

Для установки зависимостей, выполните команду:

```sh
$ npm i
```

## Изменения

### 30.05.24

Теперь в поле заметок по умолчанию пишется 'Напишите что-нибудь' для упрощения ориентирования в интерфейсе

### Функции вынесены в отдельные файлы

- [app.js](https://github.com/SspablosS/mindscape/blob/main/js/app.js)
- [storage.js](https://github.com/SspablosS/mindscape/blob/main/js/storage.js)

### Новые функции

```typescript
deleteNote(); // Удаляет замтку и ее содержимое
saveNoteContent(); // Cохраняет содержимое заметки в локальное хранилище браузера при изменении текста в текстовом поле заметки
loadNotes(); // Загружает заметки из локального хранилища браузера и отображает их на странице при загрузке
```

### Также обновлены некоторые [стили](https://github.com/SspablosS/mindscape/blob/main/css/notes.css) заметок

## Изменения

### 12.06.24

Добавлено AboutUs, Календарь
