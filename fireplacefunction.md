# Fireplace Mode

This mssage switches the fireplace mode On/Off.

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/fireplacefunction   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | {value : on/off} |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/userprogram/fireplacefunction | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | off | Is the fireplace function on or off. |
|  writeable | 1 | Writable parameter (0=No) |



### Example
```
{
    "id": "/ecus/rrc/userprogram/fireplacefunction",
    "recordable": 0,
    "type": "stringValue",
    "value": "off",
    "writeable": 1
}
```
