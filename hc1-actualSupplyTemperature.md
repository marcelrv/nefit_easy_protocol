# hc1-actualSupplyTemperature



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/actualSupplyTemperature   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/heatingCircuits/hc1/actualSupplyTemperature_ | Message ID (URL) |
|  maxValue | _100_ | Maximum allowed value |
|  minValue | _0_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _30_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/heatingCircuits/hc1/actualSupplyTemperature",
    "maxValue": 100,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 30,
    "writeable": 0
}
```
