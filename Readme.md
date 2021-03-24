# Отчёт о тестировании Money Transfer

## Краткое описание

24.03.21 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1

В результате тестирования выявлены следующие дефекты:
* [Итоговый результат рассчитывается неверно](https://github.com/anfimova/1.2.MoneyTransfer/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Код для подсчёта итогового баланса

В качестве тестовых данных использовались данные:
* balance = 2_000_000_000, transfer = 500_000_000

Тестирование производилось в следующем окружении:
* Windows 10 x64
* Java 11