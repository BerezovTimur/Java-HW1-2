### Отчёт о тестировании приложения Credit Card Number Validator

03/04/2020 было проведено:
- тестирование установки Credit Card Number Validatorание документации Credit Card Number Validatorтестирование Credit Card Number Validatorрование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

- ошибка в документации https://github.com/BerezovTimur/Java-HW1-2/issues/1
- удачное выполнение теста с номером карты 5555555555555557 80b427f8-92cd-3aae-ba04-03927fbe17c6 https://github.com/BerezovTimur/Java_HW1/issues/2
- удачное выполнение теста с номером карты 4444444444443333 387eedc6-12e9-3b32-9881-63b6b5e85317 https://github.com/BerezovTimur/Java_HW1/issues/3
- удачное выполнение теста с номером карты 4444444444444422 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 https://github.com/BerezovTimur/Java_HW1/issues/4

В процессе тестирования использовались следующие тест-план:

 1. Инсталлировать IDEA по инструкции https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md
 2. В IDEA вставить код Credit Card Number Validatorке номер 4 подставить номера карт согласно тестовым данным
 4. Запустить выполенение программы: нажмите на зелёную стрелку на первой строке, выберите "Run 'Main.main()'":
 5. Наблюдать результат

В качестве тестовых данных использовались следующие данные полученные из тестовых карт Альфа-Банка (https://pay.alfabank.ru/ecommerce/instructions/merchantManual/pages/index/test_cards.html):

Валидные номера карт:

- 4111111111111111
- 5555555555555599
- 2200000000000038

Невалидные номера карт:

- 5555555555555557
- 4444444444443333
- 4444444444444422


Тестирование производилось в следующем окружении:

- Windows 10 64 bit
-  Java 11.0.6
- IntelliJ IDEA 2013.3.4
