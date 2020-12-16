# Отчёт о установке JDK и тестировании KeyValidator

## Краткое описание

15.12.2020 - 16.12.2020 было проведено исследовательское тестировани приложения KeyValidator.

На тестирование затрачено: 2ч

В результате тестирования выявлены следующие дефекты:
* [Невалидные ключи в списке валидных](https://github.com/Bogdmoen/jvqa1.1/issues/1)
* [Валидные ключи в списке невалидных](https://github.com/Bogdmoen/jvqa1.1/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке java](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные [список лицензионных ключей](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

1. Установка OpenJDK производилась на ситсему WIN10 x64.
В проецессе установки по инструкции проблем не возникло.

![](files/java11done.png)

2. Приложение KeyValidator запускается и польностью совместимо с java 11.


3. Проверка функционала выполнялась путем ввода в консоль ключей  с помощью комманды: java KeyValidator <номер ключа>

![](files/valapp1.png)


Тестирование производилось в следующем окружении:
* Win 10 x64
* Java 11.0.9.1

