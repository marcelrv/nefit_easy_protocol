# cm-type



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/cm/type   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/system/appliance/cm/type` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `0x0054` |  |
|  writeable | `0` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/appliance/cm/type",
    "recordable": 0,
    "type": "stringValue",
    "value": "0x0054",
    "writeable": 0
}
```
