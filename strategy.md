# strategy



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/update/strategy   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/gateway/update/strategy` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `automatic` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/update/strategy",
    "recordable": 0,
    "type": "stringValue",
    "value": "automatic",
    "writeable": 1
}
```
