# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
16/12/2020 - 16/12/2020 было проведено тестирование установки IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA и санитарное тестирование  

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

* [Сложности при установке IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA](https://github.com/Chikhareva/Credit-Card-Number-Validator/issues/1)
* [Ошибка проверки номера карты в приложении Credit Card Number Validator](https://github.com/Chikhareva/Credit-Card-Number-Validator/issues/2)


## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

* Руководство по установке IntelliJ IDEA>
* [Сгенерированные номера кредитных карт с]( https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [Java код](https://github.com/netology-code/javaqa-homeworks/tree/master/intro) см код в разделе Задача №2 - Credit Card Number Validator

## [В качестве тестовых данных использовались данные]( https://www.freeformatter.com/credit-card-number-generator-validator.html):

### VISA:

- 4929692320049038
- 4929020869944379
- 4485456693889005724
### MasterCard:

- 5415954604909164
- 5245860560560873
- 5562644472819196
### Visa Electron:
- 4175008175672462
- 4026194169889402
- 4026939875831035
### JCB:
- 3535065125222175
- 3541567252319916
- 3529015573975388954


## Тестирование производилось в следующем окружении:

* ОС Win7 32bit
* openjdk version "11.0.9.1" 2020-11-04
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
* OpenJDK Client VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
* IntelliJ IDEA Community Edition 2019.3.5