# summerSwitchOff



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/summerSwitchOff   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/weatherDependent/summerSwitchOff_ | Message ID (URL) |
|  maxValue | _30_ | Maximum allowed value |
|  minValue | _10_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _16_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/summerSwitchOff",
    "maxValue": 30,
    "minValue": 10,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 16,
    "writeable": 1
}
```
