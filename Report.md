# Отчёт о тестировании Credit Card Number Validator

## Краткое описание
<p>11.01.2021 - 13.01.2021 было проведено инсталяционное тестирование приложения OpenJDK11 и функциональное тестирование валидных и невалидных ключей с помощью приложения KeyValidator.

<p>На тестирование затрачено: - 1,5 часа

В результате тестирования выявлены следующие дефекты:

* <a href="https://github.com/aov4in/KeyValidator/issues/1#issue-784624528">Баг-репорт 1</a>
* <a href="https://github.com/aov4in/KeyValidator/issues/1#issue-784624528">Баг-репорт 2</a>


<b>Описание процесса тестирования</b>
В процессе тестирования использовались следующие артефакты*:
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md">Инструкция по установке OpenJDK 11</a>
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md">Руководство использования</a>

В качестве тестовых данных использовались данные из <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md">Руководство использования</a> :
## Ключи для проверки

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1


Тестирование производилось в следующем окружении:

* Windows 10 32-разрядная, версия 19042
* OpenJDK version "11.0.9.1"
* Git for Windows v2.29.2(3) Release Notes