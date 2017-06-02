# Outdoor Temperature Message

Provides outdoor temperature information from physical sensor or internet

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/sensors/temperatures/outdoor_t1   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/system/sensors/temperatures/outdoor_t1_ | Message ID (URL) |
|  maxValue | _50_ | Maximum allowed value |
|  minValue | _-25_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  srcType | _physical_ | Source of the temperature information (possible values: physical, ...) |
|  status | _ok_ | Status of the temperature measurement (possible values: ok, ...) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _25_ | Measured temperature |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/sensors/temperatures/outdoor_t1",
    "maxValue": 50,
    "minValue": -25,
    "recordable": 0,
    "srcType": "physical",
    "status": "ok",
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 25,
    "writeable": 0
}
```
