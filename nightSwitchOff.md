# nightSwitchOff



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/nightSwitchOff   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/weatherDependent/nightSwitchOff_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _keep on heating_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/nightSwitchOff",
    "recordable": 0,
    "type": "stringValue",
    "value": "keep on heating",
    "writeable": 1
}
```
