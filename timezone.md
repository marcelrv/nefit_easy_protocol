# timezone



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/time/timezone   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /gateway/time/timezone | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | Europe/Amsterdam |  |
|  writeable | 1 | Writable parameter (0=No) |



### Example
```
{
    "id": "/gateway/time/timezone",
    "recordable": 0,
    "type": "stringValue",
    "value": "Europe/Amsterdam",
    "writeable": 1
}
```
