# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/remote/servicestate   |
| Recordable   | 0   |
| Writable   | 0   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
servicestate message
|  id | /gateway/remote/servicestate | Message ID (URL) |
servicestate message
|  recordable | 0 | Recordable parameter (0=No) |
servicestate message
|  type | stringValue | Data type of value |
servicestate message
|  value | Remote service requested |  |
servicestate message
|  writeable | 0 | Writable parameter (0=No) |

### Example
```
{
    "id": "/gateway/remote/servicestate",
    "recordable": 0,
    "type": "stringValue",
    "value": "Remote service requested",
    "writeable": 0
}
```
