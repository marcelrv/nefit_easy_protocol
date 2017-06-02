# pirSensitivity



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/pirSensitivity   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/pirSensitivity` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `high` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/pirSensitivity",
    "recordable": 0,
    "type": "stringValue",
    "value": "high",
    "writeable": 1
}
```
