# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/preheating   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
preheating message
|  id | /ecus/rrc/userprogram/preheating | Message ID (URL) |
preheating message
|  recordable | 0 | Recordable parameter (0=No) |
preheating message
|  type | stringValue | Data type of value |
preheating message
|  value | on |  |
preheating message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/userprogram/preheating",
    "recordable": 0,
    "type": "stringValue",
    "value": "on",
    "writeable": 1
}
```
