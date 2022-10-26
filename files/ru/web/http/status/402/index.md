---
title: 402 Payment Required
slug: Web/HTTP/Status/402
translation_of: Web/HTTP/Status/402
---
{{HTTPSidebar}}{{SeeCompatTable}}

HTTP-ответ **`402 Payment Required`** это нестандартная ошибка клиента, зарезервированная для использования в будущем.

Иногда этот код означает, что запрос не может быть выполнен до тех пор, пока клиент не совершит оплату. Изначально создан для активации цифровых средств или (микро) платёжных систем и изображает, что запрошенный контент недоступен пока клиент не совершит оплату. Так или иначе, стандартизованного использования для кода нет, и он может использоваться разными элементами в разном контексте.

## Статус

```
402 Payment Required
```

## Пример ответа

```bash
HTTP/1.1 402 Payment Required
Date: Wed, 21 Oct 2015 07:28:00 GMT
```

## Спецификации

| Спецификация                                                     | Заголовок                       |
| ---------------------------------------------------------------- | ------------------------------- |
| {{RFC("7231", "402 Payment Required" , "6.5.2")}} | HTTP/1.1: Semantics and Content |

## Совместимость с браузером

{{Compat}}

## Смотрите также

- [HTTP Авторизация](/ru/docs/Web/HTTP/%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F)