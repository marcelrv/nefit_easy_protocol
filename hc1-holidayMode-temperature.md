# hc1-holidayMode-temperature



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/holidayMode/temperature   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /heatingCircuits/hc1/holidayMode/temperature | Message ID (URL) |
|  maxValue | 30 | Maximum allowed value |
|  minValue | 5 | Minimum allowed value |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C | Unit of Measure |
|  value | 10 |  |
|  writeable | 1 | Writable parameter (0=No) |



### Example
```
{
    "id": "/heatingCircuits/hc1/holidayMode/temperature",
    "maxValue": 30,
    "minValue": 5,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 10,
    "writeable": 1
}
```
