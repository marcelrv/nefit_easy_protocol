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
|  id | _/ecus/rrc/userprogram/fireplacefunction_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _off_ | Is the fireplace function on or off. |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/userprogram/fireplacefunction",
    "recordable": 0,
    "type": "stringValue",
    "value": "off",
    "writeable": 1
}
```
