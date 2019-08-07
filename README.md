# From JSON to form App

## Тестовое задание

Необходимо написать приложение для генерации форм по заданной JOSN конфигурации.

Приложение состоит из двух вкладок:
 Config – для ввода конфигурации формы в формате JSON;
 Result – для отображения формы.

Приложение должно позволять генерировать формы с любым кол-вом полей.

Поля могут быть следующих типов:
 Чиcловые (numberfield)
 Строковые (textfield)
 Многострочный текст (textarea)
 Логический тип (checkbox)
 Дата (dateflied)
 Перечисление (radio buttons)

Так же приложение должно иметь возможность задавать заголовок формы, кол-во и текст
кнопок, например (Ok, Cancel, Apply)

## Project setup 
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```