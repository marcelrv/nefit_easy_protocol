# gasusagePointer



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/recordings/gasusagePointer   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/recordings/gasusagePointer_ | Message ID (URL) |
|  maxValue | _6400_ | Maximum allowed value |
|  minValue | _1_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | __ | Unit of Measure |
|  value | _7_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/recordings/gasusagePointer",
    "maxValue": 6400,
    "minValue": 1,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "",
    "value": 7,
    "writeable": 0
}
```
