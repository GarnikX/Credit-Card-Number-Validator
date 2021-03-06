## Отчёт о тестировании Credit Card Number Validator

### Краткое описание

14.12.21 - 14.12.21 было проведено функциональное, белого ящика, позитивное и негативное, статическое тестирования с использованием среды разработки IntelliJ IDEA Community Edition приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

### В результате тестирования выявлены следующие дефекты:
* [Не проходит валидация банковских карт с номером неравным 16 закам](https://github.com/GarnikX/Credit-Card-Number-Validator/issues/1#issue-1083839340)

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Использовалась техника анализа граничных значений
* Использование пробела
* Использование кириллических и латинских символов
* Незаполнение номера карты


### В качестве тестовых данных использовались данные:
* [Код приложения:](https://snipit.io/public/snippets/61196)
* [Номера карт:](https://www.getcreditcardnumbers.com/generated-credit-card-numbers)

### Тестирование производилось в следующем окружении:
* Операционная система: Win7 HB 64
* IDE: IntelliJ IDEA 2021.3 (Community Edition)
* Java: OpenJDK 11.0.13