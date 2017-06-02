# dhwOperationMode



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/dhwOperationMode   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/dhwCircuits/dhwA/dhwOperationMode_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _comfort_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/dhwOperationMode",
    "recordable": 0,
    "type": "stringValue",
    "value": "comfort",
    "writeable": 1
}
```
