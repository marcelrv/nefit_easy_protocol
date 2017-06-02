# Hot Water Status



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/extraDhw/status   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/dhwCircuits/dhwA/extraDhw/status_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _off_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/extraDhw/status",
    "recordable": 0,
    "type": "stringValue",
    "value": "off",
    "writeable": 1
}
```
