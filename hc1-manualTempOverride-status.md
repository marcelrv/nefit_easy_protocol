# hc1-manualTempOverride-status



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/manualTempOverride/status   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/heatingCircuits/hc1/manualTempOverride/status` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `off` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/heatingCircuits/hc1/manualTempOverride/status",
    "recordable": 0,
    "type": "stringValue",
    "value": "off",
    "writeable": 1
}
```
