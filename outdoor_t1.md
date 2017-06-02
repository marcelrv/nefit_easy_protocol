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
| ------------- | :------: | :------------------------------ |
|  id | `/system/sensors/temperatures/outdoor_t1` | Message ID (URL) |
|  maxValue | `50` | Maximum allowed value |
|  minValue | `-25` | Minimum allowed value |
|  recordable | `0` | Recordable parameter (0=No) |
|  srcType | `physical` | Source of the temperature information (possible values: physical, ...) |
|  status | `ok` | Status of the temperature measurement (possible values: ok, ...) |
|  type | `floatValue` | Data type of value |
|  unitOfMeasure | `C` | Unit of Measure |
|  value | `25` | Measured temperature |
|  writeable | `0` | Writable parameter (0=No) |



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
