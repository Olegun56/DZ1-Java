# Отчёт о тестировании приема платежей банковскими картами

## Краткое описание

22.03.2021 - 23.03.2021 было проведено функциональное тестирование приложения приема платежей банковскими картами.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Банковские карты банков (American Express, Diners Club - Carte Blanche, Diners Club - International) имеющие номера более или менее 16 цифр не подходят для платежей.](https://github.com/Olegun56/DZ1-Java/issues/1)



## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Код из ДЗ](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)


В качестве тестовых данных использовались данные с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:




### Тестирование производилось в следующем окружении:
* Windows 7 x64
* Java 11
* IntelliJ IDEA Community Edition 2020.3