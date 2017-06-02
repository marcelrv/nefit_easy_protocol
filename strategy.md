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
| ------------- | :------: | ------------------------------ |
|  id | _/gateway/update/strategy_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _automatic_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



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
