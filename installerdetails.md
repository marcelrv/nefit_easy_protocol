# installerdetails



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/installerdetails   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/installerdetails` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `;;;` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/installerdetails",
    "recordable": 0,
    "type": "stringValue",
    "value": ";;;",
    "writeable": 1
}
```
