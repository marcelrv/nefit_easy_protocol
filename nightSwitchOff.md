# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/nightSwitchOff   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
nightSwitchOff message
|  id | /ecus/rrc/weatherDependent/nightSwitchOff | Message ID (URL) |
nightSwitchOff message
|  recordable | 0 | Recordable parameter (0=No) |
nightSwitchOff message
|  type | stringValue | Data type of value |
nightSwitchOff message
|  value | keep on heating |  |
nightSwitchOff message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/weatherDependent/nightSwitchOff",
    "recordable": 0,
    "type": "stringValue",
    "value": "keep on heating",
    "writeable": 1
}
```
