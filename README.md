# Лабораторная работа 1.4

## Создание класса-модели, работа с ObservableList и отображение данных в TableView

### Цель работы

Создать класс-модель предметной области, использовать коллекцию `ObservableList` для хранения объектов модели и реализовать отображение данных в компоненте `TableView` с помощью контроллера.

### Задание

1. Создать класс-модель.
2. Использовать класс-модель в коллекции `ObservableList`.
3. Отобразить данные в компоненте `TableView` с помощью контроллера.

### Предметная область

В качестве предметной области используется **электронный каталог книг**.

### Книга

Книга содержит следующие характеристики:

- Название
- Переплёт
- Издательство
- Год издания
- Жанр
- Автор

### Автор

Автор содержит:

- ФИО
- Телефон
- E-mail
- Рейтинг

### Используемые технологии

- Java
- JavaFX
- FXML
- Maven
- IntelliJ IDEA
- Scene Builder
- ObservableList
- TableView
- MVC

### Структура проекта

```text
JavaLab3
│
├── src
│   └── main
│       ├── java
│       │   └── org.example.javalab3
│       │       ├── controller
│       │       │   └── BookOverviewController.java
│       │       │
│       │       ├── model
│       │       │   ├── Book.java
│       │       │   └── Author.java
│       │       │
│       │       └── Launcher.java
│       │
│       └── resources
│           └── org.example.javalab3
│               └── BookOverview.fxml
│
├── module-info.java
├── pom.xml
└── README.md
