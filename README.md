# @apilki/yandex-market — Postman Collection

**Запросов: 161 · Собрано: 2026-11-20**

Готовая [Postman Collection v2.1](postman/collection.json) для **Yandex Market
Partner API** (сторона продавца): все 161 операция официальной спецификации.
Собрана пайплайном apilki (`@apidevtools/swagger-parser` + `openapi-to-postmanv2`)
и проверена на полноту скриптом `postman-check`: число запросов = число операций.

Перезаписывается пайплайном при каждом изменении API Яндекс Маркета.

## Как импортировать

1. Скачайте [`postman/collection.json`](postman/collection.json).
2. Postman → **Import** → выберите файл.
3. Задайте `apiKey` в авторизации коллекции (тип **API Key**, ключ `Api-Key`,
   значение — ваш ключ из кабинета Яндекс Маркета). Авторизация применена на всю
   коллекцию, отдельные запросы править не нужно.
4. `baseUrl` = `https://api.partner.market.yandex.ru` — уже проставлен.

## Связанное

- Типизированный клиент с тем же покрытием: [apilki/yandex-market-typescript](https://github.com/apilki/yandex-market-typescript)
- Официальная документация API: <https://yandex.ru/dev/market/partner-api/>

## Лицензия

MIT © apilki. Спецификация API принадлежит ООО «ЯНДЕКС».
