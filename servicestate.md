# servicestate



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/remote/servicestate   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/gateway/remote/servicestate` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `Remote service requested` |  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/remote/servicestate",
    "recordable": 0,
    "type": "stringValue",
    "value": "Remote service requested",
    "writeable": 0
}
```
