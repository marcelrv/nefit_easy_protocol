# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/temperatureAdjustment   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
hc1-temperatureAdjustment message
|  id | /heatingCircuits/hc1/temperatureAdjustment | Message ID (URL) |
hc1-temperatureAdjustment message
|  maxValue | 2 |  |
hc1-temperatureAdjustment message
|  minValue | -2 |  |
hc1-temperatureAdjustment message
|  recordable | 0 | Recordable parameter (0=No) |
hc1-temperatureAdjustment message
|  type | floatValue | Data type of value |
hc1-temperatureAdjustment message
|  unitOfMeasure | C |  |
hc1-temperatureAdjustment message
|  value | 0 |  |
hc1-temperatureAdjustment message
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
