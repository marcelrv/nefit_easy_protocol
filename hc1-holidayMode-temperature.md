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
|  id | _/heatingCircuits/hc1/holidayMode/temperature_ | Message ID (URL) |
|  maxValue | _30_ | Maximum allowed value |
|  minValue | _5_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _10_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
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
