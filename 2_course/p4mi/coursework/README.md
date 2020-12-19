## Курсовая работа по дисциплине "Проектирование человеко-машинного интерфейса" на тему "Конференция"
### Контакты:
ФИО: Балашов Андрей Евгеньевич

Телефон: 89196890142

### Информация о программном продукте:
Для запуска необходимо иметь на компьютере установленную JRE ([ссылка](https://www.oracle.com/ru/java/technologies/javase-jre8-downloads.html))
и JDK 11 версии ([ссылка](https://www.oracle.com/ru/java/technologies/javase-jdk11-downloads.html))

### Запуск программы:

###### Компиляция:
* `javac -d out --module-path src/lib/javafx --add-modules javafx.controls,javafx.fxml,javafx.graphics src/AddConference.java src/Conference.java src/ConferenceController.java src/Database.java src/DateUtils.java src/EditConference.java src/LoginController.java src/Main.java src/MainController.java src/User.java`
* `cp -r src/views out`
* `cp -r src/css out`
* `cp -r src/img out`

###### Запуск:
* `java -cp out:src/lib/mysql/mysql.connector.jar --module-path src/lib/javafx --add-modules javafx.controls,javafx.fxml,javafx.graphics Main`
