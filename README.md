# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
16/12/2020 - 16/12/2020 было проведено тестирование установки IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA и санитарное тестирование  

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

<ссылка на описание дефекта>
<ссылка на описание дефекта>
<ссылка на описание дефекта>
## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

* Руководство по установке IntelliJ IDEA>
* Сгенерированные номера кредитных карт с  ( https://www.freeformatter.com/credit-card-number-generator-validator.html)
* Java код (https://github.com/netology-code/javaqa-homeworks/tree/master/intro) см код в разделе Задача №2 - Credit Card Number Validator

В качестве тестовых данных использовались данные ( https://www.freeformatter.com/credit-card-number-generator-validator.html):

* Валидные значения карт VISA:
4716098183008847

4929592451212894
* Валидные значения карт MasterCard:
2221004285181021

5203010888899757

* Не валидные значения карт Visa и JCB
4929185812338422372
3542312226368094886


Тестирование производилось в следующем окружении:

* ОС Win7 32bit
* openjdk version "11.0.9.1" 2020-11-04
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
* OpenJDK Client VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
* IntelliJ IDEA Community Edition 2019.3.5