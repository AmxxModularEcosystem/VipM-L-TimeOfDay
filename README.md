# [VipM-L] Time Of Day

Добавляет условие `ToD-DayTime`, которое срабатывает в указанное время суток из [Time Of Day](https://arkanaplugins.ru/plugin/11).

## Параметры

| Название  | Тип      | По умолчанию | Описание
| :---:     | :---     | :---         | :---
| `DayTime` | Строка   | -            | Название времени суток из Time Of Day.

## Пример

```jsonc
{
    "Limit": "ToD-DayTime",
    "DayTime": "Night"
}
```

_Условие будет верно ночью_
