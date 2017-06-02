# timezone



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/time/timezone   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/gateway/time/timezone_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _Europe/Amsterdam_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/time/timezone",
    "recordable": 0,
    "type": "stringValue",
    "value": "Europe/Amsterdam",
    "writeable": 1
}
```
