# Отчет о тестировании программы Precision

Краткое описание

25.01.2021 было проведено функциональное тестирование приложения Prescion в программе IntelliJ IDEA

На тестирование затрачен 1 час

Выявлен дефект:
Во время сложения чисел 0.3 и 0.6 программа выдает результат 0.8999999999999999, вместо 0.9.

* [Некорректный расчет итогового бонуса. #1](https://github.com/DarcenRal/Precision_Jva2.2/issues)

## Описание процесса тестирования

В IntelliJ IDEA версия 2020.3 было создано базовое приложение, позволяющее воспроизвести ситуацию.
Код для приложения был взят в задании.
Приложение работает согласно руководству использования.

## Pезультаты тестирования 

Ожидаемый результат

Во время сложения чисел 0.3 и 0.6 программа выдает результат 0.9

Фактический результат

Во время сложения чисел 0.3 и 0.6 программа выдает результат 0.8999999999999999

## Тестирование производилось в следующем окружении

Windows 10 версия 10.0.18363.1256
java -version openjdk version "11.0.9.1" 2020-11-04
IntelliJ IDEA community edition 2020.03