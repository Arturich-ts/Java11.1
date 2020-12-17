# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17.12.2020 - 17.12.2020 было проведено  функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* Номера карт некоторых систем не проходят валидацию


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тест-кейс](https://docs.google.com/spreadsheets/d/1Xe33BMiizjCPeEg2VqM2WEif04rawGqXDjOoTij4dA4/edit?usp=sharing)

В качестве тестовых данных использовались данные [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* 4485597934038275 - Visa
* 4532483401531634 - Visa
* 5246834088530766 - MasterCard
* 5439983832213166 - MasterCard
* 36696394405297 - Diners Club - International
* 36920976215902 - Diners Club - International
* 347137452970405 - American Express (AMEX)
* 347494238998329 - American Express (AMEX)
* 6011872430322555686 - Discover
* 6011904195478430 - Discover
* 6763856308410322 - Maestro
* 6762867010089776 - Maestro
* 6395627266808310 - InstaPayment 
* 6382082162477825 - InstaPayment 
* 3532987723124464820 - JCB
* 3532445940178286 - JCB
* 4175009677033815 - Visa Electron
* 4917328028186152 - Visa Electron

Тестирование производилось в следующем окружении:

* Windows  10 Pro, x64
* Java 11