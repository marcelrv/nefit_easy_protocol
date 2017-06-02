# basePointSupply



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/basePointSupply   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/weatherDependent/basePointSupply_ | Message ID (URL) |
|  maxValue | _90_ | Maximum allowed value |
|  minValue | _20_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _20_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/basePointSupply",
    "maxValue": 90,
    "minValue": 20,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 20,
    "writeable": 1
}
```
