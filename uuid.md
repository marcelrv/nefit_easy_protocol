# uuid



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/uuid   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/gateway/uuid_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _123456789_ | Unique ID  |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/uuid",
    "recordable": 0,
    "type": "stringValue",
    "value": "123456789",
    "writeable": 0
}
```
