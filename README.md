# KeyValidator2

# Отчёт о тестировании **приложения "KeyValidator"**

## Краткое описание

20.09.2020 - 20.09.2020 было проведено инсталяционное тестирование приложения KeyValidator.

На тестирование затрачено: 0,5 часа.

В результате тестирования выявлены следующие дефекты:
* [FAIL при вводе валидного значения 00000000-0000-0000-0000-000000000000](https://github.com/AlexAlekseyenok/KeyValidator2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Документация: "[Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)";
* Установочный файл приложения: [KeyValidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class).

В качестве тестовых данных использовались данные из "Руководство использования KeyValidator":
* При вводе в терминале команды:
```
java KeyValidator 00000000-0000-0000-0000-000000000000 00000000-0000-0000-0000-000000000001
```
Получено значение:
```
Result for 00000000-0000-0000-0000-000000000000: FAIL
Result for 00000000-0000-0000-0000-000000000001: FAIL
```

Тестирование производилось в следующем окружении:
* Windows 10 версия 1903, разрядность ОС: x64;
* Java 11.0.8.
