# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /heatingCircuits/hc1/control   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
hc1-control message
|  id | /heatingCircuits/hc1/control | Message ID (URL) |
hc1-control message
|  recordable | 0 | Recordable parameter (0=No) |
hc1-control message
|  type | stringValue | Data type of value |
hc1-control message
|  value | room |  |
hc1-control message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/heatingCircuits/hc1/control",
    "recordable": 0,
    "type": "stringValue",
    "value": "room",
    "writeable": 1
}
```
