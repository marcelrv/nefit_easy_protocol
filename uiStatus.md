# Status Message

Provides status information

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/uiStatus   |
| Recordable   | 0   |
| Writable   | 0   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
uiStatus message
|  id | /ecus/rrc/uiStatus | Message ID (URL) |
uiStatus message
|  recordable | 0 | Recordable parameter (0=No) |
uiStatus message
|  type | uiUpdate | Data type of value |
uiStatus message
|  value | {u'CPM': u'auto', u'CTR': u'room', u'TOR': u'off', u'TOT': u'21.0', u'CTD': u'2017-05-29T17:21:02+01:00 Mo', u'BLE': u'false', u'DOT': u'false', u'BAI': u'No', u'HED_DB': u'', u'RS': u'off', u'BMR': u'false', u'FAH': u'false', u'TOD': u'0', u'DAS': u'off', u'HMD': u'off', u'FPA': u'off', u'BBE': u'false', u'DHW': u'on', u'CSP': u'8', u'ESI': u'off', u'ARS': u'init', u'HED_DEV': u'false', u'PMR': u'false', u'UMD': u'clock', u'MMT': u'15.0', u'TAS': u'off', u'HED_EN': u'false', u'IHT': u'27.40', u'TSP': u'20.0', u'IHS': u'ok'} |  |
uiStatus message
|  writeable | 0 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/uiStatus",
    "recordable": 0,
    "type": "uiUpdate",
    "value": {
        "ARS": "init",
        "BAI": "No",
        "BBE": "false",
        "BLE": "false",
        "BMR": "false",
        "CPM": "auto",
        "CSP": "8",
        "CTD": "2017-05-29T17:21:02+01:00 Mo",
        "CTR": "room",
        "DAS": "off",
        "DHW": "on",
        "DOT": "false",
        "ESI": "off",
        "FAH": "false",
        "FPA": "off",
        "HED_DB": "",
        "HED_DEV": "false",
        "HED_EN": "false",
        "HMD": "off",
        "IHS": "ok",
        "IHT": "27.40",
        "MMT": "15.0",
        "PMR": "false",
        "RS": "off",
        "TAS": "off",
        "TOD": "0",
        "TOR": "off",
        "TOT": "21.0",
        "TSP": "20.0",
        "UMD": "clock"
    },
    "writeable": 0
}
```
