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
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/pirSensitivity_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _high_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



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
