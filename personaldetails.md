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
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/personaldetails | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | User Name;tel#;email@example.com |  |
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
