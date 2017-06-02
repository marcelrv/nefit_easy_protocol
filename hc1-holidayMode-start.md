# hc1-holidayMode-start



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/holidayMode/start   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/heatingCircuits/hc1/holidayMode/start_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _2000-01-01T00:00:00_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/heatingCircuits/hc1/holidayMode/start",
    "recordable": 0,
    "type": "stringValue",
    "value": "2000-01-01T00:00:00",
    "writeable": 1
}
```
