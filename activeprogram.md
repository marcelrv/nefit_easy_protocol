# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/activeprogram   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
activeprogram message
|  id | /ecus/rrc/userprogram/activeprogram | Message ID (URL) |
activeprogram message
|  maxValue | 2 |  |
activeprogram message
|  minValue | 0 |  |
activeprogram message
|  recordable | 0 | Recordable parameter (0=No) |
activeprogram message
|  type | floatValue | Data type of value |
activeprogram message
|  unitOfMeasure |  |  |
activeprogram message
|  value | 0 |  |
activeprogram message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/userprogram/activeprogram",
    "maxValue": 2,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "",
    "value": 0,
    "writeable": 1
}
```
