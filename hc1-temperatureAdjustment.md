# hc1-temperatureAdjustment



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/temperatureAdjustment   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /heatingCircuits/hc1/temperatureAdjustment | Message ID (URL) |
|  maxValue | 2 |  |
|  minValue | -2 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C |  |
|  value | 0 |  |
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/heatingCircuits/hc1/temperatureAdjustment",
    "maxValue": 2,
    "minValue": -2,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 0,
    "writeable": 1
}
```
