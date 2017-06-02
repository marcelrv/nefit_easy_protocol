# thermaldesinfect-time



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/thermaldesinfect/time   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/dhwCircuits/dhwA/thermaldesinfect/time` | Message ID (URL) |
|  maxValue | `1440` | Maximum allowed value |
|  minValue | `0` | Minimum allowed value |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `floatValue` | Data type of value |
|  unitOfMeasure | `Min` | Unit of Measure |
|  value | `60` |  |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/thermaldesinfect/time",
    "maxValue": 1440,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "Min",
    "value": 60,
    "writeable": 1
}
```
