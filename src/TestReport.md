# Отчёт о тестировании Bonus system for clients.

## Краткое описание

<15.07.2021> - <15.07.2021> было проведено функциональное тестирование приложения Bonus system for clients..

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* [Неверный результат вычисления итогового значения специального бонуса для своих клиентов](https://github.com/KseniaShepherd/Precision/issues/1)


## Описание процесса тестирования

В качестве тестовых данных использовались данные из [задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision) :
* обычный бонус 0.3
* специальный бонус 0.6
* переменная для хранения итогового значения - тип double, ожидаемый результат 0.9

Тестирование производилось в следующем окружении:
* Mac OC Catalina Version 10.15.7 (19H1030)
* OpenJDK version "11.0.11" 2021-04-20
* IntelliJ IDEA 2018.3.6 (Ultimate Edition)