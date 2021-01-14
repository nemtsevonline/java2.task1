# Отчёт о тестировании приложения Money Transfer

## Краткое описание

14.01.2020 - 14.01.2020. Было проведено функциональное тестирование приложения Money Transfer

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/nemtsevonline/java2.task1/issues1


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Домашнее задание к занятию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком» https://github.com/netology-code/javaqa-homeworks/tree/master/programming

В качестве тестовых данных использовался код базового приложения Money Transfer. 

```public class Main {
    public static void main(String[] args) {
        int balance = 2000_000_000;
        int transfer = 500_000_000;
        int total = balance + transfer;
        System.out.println(total);
    }}
```
Ожидаемый результат - после перевода денежных средств на счет клиента баланс корректный.

Тестирование производилось в следующем окружении:
* Windows 10 Home 64 bit
* Версия Java 11.0.9.1

