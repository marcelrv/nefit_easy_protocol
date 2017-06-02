# roomInfluence



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/roomInfluence   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/weatherDependent/roomInfluence_ | Message ID (URL) |
|  maxValue | _3_ | Maximum allowed value |
|  minValue | _0_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | __ | Unit of Measure |
|  value | _0_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/roomInfluence",
    "maxValue": 3,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "",
    "value": 0,
    "writeable": 1
}
```
