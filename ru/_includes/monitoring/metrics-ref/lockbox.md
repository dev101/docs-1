Общие метки для всех метрик {{ lockbox-name }}:

| Метка | Значение |
| --- | --- |
service | Идентификатор сервиса: `lockbox`
secret | Идентификатор [секрета](../../../lockbox/concepts/secret.md) |

Метрики сервиса:

| Имя метрики<br>Тип, единицы измерения | Описание |
| --- | --- |
| `key.active_versions_count`<br>`DGAUGE`, штуки | Количество активных версий секрета. |
| `key.payload_operations_rate`<br>`DGAUGE`, операций/с | Скорость выполнения операций с содержимым секрета. Специальная метка `operation` — тип операции с секретом, возможное значение: `get_payload`. |