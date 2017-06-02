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
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/pm/shorttapping/status_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  timestamp | _2000-01-01T00:00:00_ |  |
|  type | _stringValue_ | Data type of value |
|  value | _false_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



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
