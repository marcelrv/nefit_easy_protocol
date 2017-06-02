# shorttapping-status



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/pm/shorttapping/status   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/pm/shorttapping/status` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  timestamp | `2000-01-01T00:00:00` |  |
|  type | `stringValue` | Data type of value |
|  value | `false` |  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/pm/shorttapping/status",
    "recordable": 0,
    "timestamp": "2000-01-01T00:00:00",
    "type": "stringValue",
    "value": "false",
    "writeable": 0
}
```
