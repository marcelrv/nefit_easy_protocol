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
| ------------- | :------: | ------------------------------ |
|  id | _/gateway/remote/servicestate_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _Remote service requested_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



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
