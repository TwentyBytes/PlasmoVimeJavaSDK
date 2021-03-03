# PlasmoVimeJavaSDK

---

**Plasmo Vime Java SDK** - это инструмент разработки написанный на Java для быстрой и удобной работы с VimeWorld API (Также известно как Rest API).
Для начала работы с ней, вам нужно импортировать библеотеку предварительно скачав ее из релизов. Репозиторий maven появится позже.

Следующий шаг - создание обьекта главного класса, а там уже все интуитивно понятно по названиям методов.

`PlasmoVimeAPI vimeAPI = PlasmoVimeAPI.construct("Ваш токен. (Может быть **null**)");`

Вот и все! 

---

## Лимиты по запросам:

1. > Без токена - **60** запросов в минуту.
2. > С токеном разработчика - **300** запросов в минуту.

Токен можно получить в игре прописав команду **/api.**

Полная документация появится позже.
Приятной вам работы. :coffee:
