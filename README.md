# Отчёт о тестировании "KeyValidator"
## Краткое описание

3/11/2020  было проведено функциональное тестирование приложения "KeyValidator".

На тестирование затрачено:1

В результате тестирования дефектов не выявлено.

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
 Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 Result Ok
* 80b427f8-92cd-3aae-ba04-3927fbe17c6  Result Fail
* b295bc63-9f03-3b4b-af80-969b39f8c262 Result Ok
* 387eedc6-12e9-3b32-9881-63b6b5e85317 Result Fail
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 Result Ok

 Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a Result Fail
* e66075b6-ddad-445e-baf6-161b3289522b Result Fail
* b6d53250-f07e-4352-a293-6102ddf7f1ca Result Fail
* c2bc778a-1cb9-46c6-b435-0489649d2a42 Result Fail
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 Result Fail


В качестве тестовых данных использовались данные:
 Валидные:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 Result Ok
* 80b427f8-92cd-3aae-ba04-3927fbe17c6  Result Ok
* b295bc63-9f03-3b4b-af80-969b39f8c262 Result Ok
* 387eedc6-12e9-3b32-9881-63b6b5e85317 Result Ok
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 REsult Ok

 Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a Result Fail
* e66075b6-ddad-445e-baf6-161b3289522b Result Fail
* b6d53250-f07e-4352-a293-6102ddf7f1ca Result Fail
* c2bc778a-1cb9-46c6-b435-0489649d2a42 Result Fail
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 Result Fail

Тестирование производилось в следующем окружении:
* Ubuntu 20.04 amd 64bit
* Java 11.09
* Linux Terminal Emulator

