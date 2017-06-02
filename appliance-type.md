# appliance-type



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/type   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/system/appliance/type` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `0xCE` |  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/appliance/type",
    "recordable": 0,
    "type": "stringValue",
    "value": "0xCE",
    "writeable": 0
}
```
