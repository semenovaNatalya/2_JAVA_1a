# Отчёт о тестировании **Money Transfer**

## Краткое описание

28/07/2021 - 28/07/2021 было проведено санитарное тестирование, являющееся частью функционального тестирования приложения Money Transfer.

31/07/2021-31/07/2021 _исправление ошибок_

На тестирование затрачено: 0,5 часа
На исправление ошибок 1,5 часа

В результате тестирования выявлен следующий дефект:
* [Некорректный расчет баланса счета после перевода](https://github.com/semenovaNatalya/2_JAVA_1a/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [позитивный тест-кейс](https://docs.google.com/spreadsheets/d/1dO2GoRM_SWov-F1_Nhz0R-z2FVH1UsG6HRkG04wdns0/edit?usp=sharing)
* [баг-репорт](https://semnaiq20.atlassian.net/jira/software/projects/MT/boards/4/backlog?selectedIssue=MT-1)


В качестве тестовых данных использовались [данные Задачи_1 ДЗ_2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming), а именно
- текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)*
- сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
- переменная для хранения итогового значения - тип int
* ожидаемый результат - значение переменной total 2_500_000_000


Тестирование проводилось в следующем окружении:
* Windows 10 Pro, 64-разрядная операционная система
* Java 11.0.11