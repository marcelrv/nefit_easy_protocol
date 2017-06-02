# hc1-temperatureAdjustment



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/temperatureAdjustment   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/heatingCircuits/hc1/temperatureAdjustment_ | Message ID (URL) |
|  maxValue | _2_ | Maximum allowed value |
|  minValue | _-2_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _0_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
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
