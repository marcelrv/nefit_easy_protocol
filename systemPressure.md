# System Pressure



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/systemPressure   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/system/appliance/systemPressure_ | Message ID (URL) |
|  maxValue | _25_ | Maximum allowed value |
|  minValue | _0_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _bar_ | Unit of Measure |
|  value | _25.5_ | Water Pressure |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/appliance/systemPressure",
    "maxValue": 25,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "bar",
    "value": 25.5,
    "writeable": 0
}
```
