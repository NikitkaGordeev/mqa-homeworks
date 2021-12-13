
# Домашнее задание к занятию 1.4."Инструменты для ручного тестирования мобильных приложений"


Правила выполнения:

Скопируйте шаблон таблицы по [ссылке](https://docs.google.com/spreadsheets/d/1pFHiF_d3dchSexI22Yq5gqAN8OWMR2ksb3jCp8RIGUc/edit?usp=sharing) на свой Google-диск , укажите в названии файла свои фамилию, имя и группу вместо Name, Surname, Group.

В своей таблице прикрепляйте ссылки на выполненную работу по каждому заданию.

Вам необходимо выполнить 3 задания для получения зачета. Задания со звездочкой(*) выполняются по желанию, но очень способствует дополнительной практике :)

Прикрепите в личном кабинете ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.

Прикладывайте, пожалуйста, прямые ссылки на скриншоты


## Предварительное условие:

1. Устанавливаем и настраиваем Charles для выполнения домашнего задания.
(https://www.charlesproxy.com/) 
Выполните все необходимые настройки вашего тестового девайса для отслеживания запросов


2.Установите тестовое приложение, изучите его функционал.

Объект тестирования: приложение **Everybook**

[Everybook в GooglePlay](https://play.google.com/store/apps/details?id=tech.everybook&hl=ru&gl=US)


[Everybook в Appstore](https://apps.apple.com/ru/app/everybook-%D0%BA%D0%BD%D0%B8%D0%B3%D0%B8-%D0%BD%D0%B0%D0%BF%D1%80%D0%BE%D0%BA%D0%B0%D1%82/id1453855130)


## Задание 1.
 Вам необходимо убедиться, что разработчики предусмотрели обработку различных ошибок сети.
Смоделируйте показ ошибки тайм -аута в  приложении.


**Выполнение задания:**

1.скриншот необходимых для данной проверки настроек в Charles

2.скриншот данной ошибки в приложении.


## Задание 2.
Вам необходимо проверить, что в аккаунте приложения при значениях баланса более 100 000 монеток(при желании можно и больше) верстка будет отображаться корректно

Найдите нужный запрос, отвечающий за эти данные и сделайте подмену значений.

**Выполнение задания:**

cкриншот аккаунта пользователя с тестовыми значениями.


## Задание 3
Вам необходимо  проверить кейс, что пользователь  оформил в приложении книгу в аренду и по истечении срока аренды она более ему недоступна.
Ждать окончания срока аренды книги нет возможности. Ваши действия?

 
**Выполнение задания:**

1.алгоритм ваших действий

2.Скриншот оформленной в аренду книги+скриншот книги со сроком окончания аренды




## Задание 4*
Позади долгое тестирование и отладка функционала вашего приложения. Впереди столь долгожданный релиз, осталась лишь маленькая, но важная часть.
Вам необходимо  провести заключительное тестирование и убедиться, что в релизной сборке не осталось отладочной информации и журналов работы приложения.
Важно проверить ,что адреса тестовых стендов и других внутренних компонентов, API-ключи тестовых сервисов  или сообщения, которые использовались при отладке приложения нигде не фигурируют в логах так как такие доступные  данные могут использоваться злоумышленниками при поиске уязвимостей и позволяют расширить поверхность атак.

Android Studio/XCode невозможно использовать.
Какие альтернативные инструменты для проверки логирования вы будете использовать?


**Выполнение задания:**

1.Привести примеры инструментов, которые будем использовать.

2.Проверить тестовое приложение на предмет наличия отладочных данных

 

## Задание 5* 
Работа в adb.
 
Через командную строку отправить на устройство Android картинку, которую вы планируете использовать для мок тестирования.

Сделать скриншот/скринкаст на девайсе через консоль adb

**Выполнение задания:**

скриншоты выполненных  команд в adb
