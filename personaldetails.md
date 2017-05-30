# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/personaldetails   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
personaldetails message
|  id | /ecus/rrc/personaldetails | Message ID (URL) |
personaldetails message
|  recordable | 0 | Recordable parameter (0=No) |
personaldetails message
|  type | stringValue | Data type of value |
personaldetails message
|  value | User Name;tel#;email@example.com |  |
personaldetails message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/personaldetails",
    "recordable": 0,
    "type": "stringValue",
    "value": "User Name;tel#;email@example.com",
    "writeable": 1
}
```
