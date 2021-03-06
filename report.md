# Отчёт о тестировании <Key validator>

12.04.2020 было проведено <тестирование документации/тестирование установки/ручное тестирование согласно документации> приложения Credit Card Number Validator.

### На тестирование затрачено: 1 час

#### В результате тестирования выявлены следующие дефекты:

[1.Несоответствие валидных ключей в приложении KeyValidator](https://github.com/ViktorUdovin/Homeworkjava1.1/issues/1)
[2.Несоответствие невалидных ключей в приложении KeyValidator](https://github.com/ViktorUdovin/Homeworkjava1.1/issues/2)

Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты*:


2.Отчет по тестированию

### В качестве тестовых данных использовались данные из:

1.[Руководство по установке IntelliJ IDEA.](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

2.[Генератор номеров карт.](https://www.freeformatter.com/credit-card-number-generator-validator.html)

1. Используя [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md), была проверена документация установки IntelliJ IDEA, проблем выявлено не было, установка прошла как надо.

2. Использовались следующие номера карт с [генератора номеров карт.](https://www.freeformatter.com/credit-card-number-generator-validator.html), в качестве результата использовались два итога: `OK` и `FAIL`

### Проверка номеров карт и результаты:
1. VISA: 4929276143357917 - `OK`; 4716845363507802 - `OK`; 4119873296534592995 - `FAIL`; 

2. Discover: 6011976339227691 - `OK`; 6011824826853506 - `OK`; 6011149824411488741 - `FAIL`;

3. Diners Club - Carte Blanche: 30166567648764 - `FAIL`; 30064727479479 - `FAIL`; 30208141383037 - `FAIL`;

4. Visa Electron: 4026769843399074 - `OK`; 4175005416535714 - `OK`; 4026670162925509 - `OK`;

5. MasterCard: 5423790065923645 - `OK`; 5472638554772009 - `OK`; 5252279059249932 - `OK`;

6. JCB: 3536717676572759 - `OK`; 3533746271662700 - `OK`; 3528799316106225453 - `FAIL`;

7. Diners Club - International: 36902317430861 - `FAIL`; 36004364967851 - `FAIL`; 36511085761470 - `FAIL`;

8. InstaPayment: 6371342491126847 - `OK`; 6388766854863599 - `OK`; 6398341707362161 - `OK`;

9. American Express (AMEX): 379457454651261 - `FAIL`; 342860427437441 - `FAIL`; 340940313978559 - `FAIL`;

10. Diners Club - North America: 5522647039442567 - `OK`; 5403324527134437 - `OK`; 5510125970369614 - `OK`;

11. Maestro: 6761747029386580 - `OK`; 6759053270117566 - `OK`; 6759117637478449 - `OK`;

## К сожалению, я не до конца понимаю остальной код, и соответственно не могу выявить, что здесь явлеятся багом, а что нет. При других тестах: "Тестирование документации" и "Тестирование установки" - багов выявлено не было.



   

### Тестирование производилось в следующем окружении:

Устройство: MacBook Pro (Retina, 15-inch, Mid 2014).

ОС: MacOS mojave версия 10.14.6

Java: openjdk version "11.0.6" 2020-01-14