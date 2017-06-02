# Status Message

Provides status information

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/uiStatus   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/uiStatus` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `uiUpdate` | Data type of value |
|  value | `{"CPM": "auto", "CTR": "room", "TOR": "off", "TOT": "21.0", "CTD": "2017-05-29T17:21:02+01:00 Mo", "BLE": "false", "DOT": "false", "BAI": "No", "HED_DB": "", "RS": "off", "BMR": "false", "FAH": "false", "TOD": "0", "DAS": "off", "HMD": "off", "FPA": "off", "BBE": "false", "DHW": "on", "CSP": "8", "ESI": "off", "ARS": "init", "HED_DEV": "false", "PMR": "false", "UMD": "clock", "MMT": "15.0", "TAS": "off", "HED_EN": "false", "IHT": "27.40", "TSP": "20.0", "IHS": "ok"}` |  |
|  writeable | `0` | Writable parameter (0=No) |


### uiUpdate type details 

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  ARS | `init` |  |
|  BAI | `No` | Boiler Indicator (String 'CH' : 'central heating', 'HW' : 'hot water', 'No' : 'off') |
|  BBE | `false` | Boiler Block (Boolean) |
|  BLE | `false` | Boiler Lock (Boolean) |
|  BMR | `false` | Boiler Maintenance (Boolean) |
|  CPM | `auto` | Clock Program (String) |
|  CSP | `8` | Current Switch point (Float) |
|  CTD | `2017-05-29T17:21:02+01:00 Mo` |  |
|  CTR | `room` |  |
|  DAS | `off` |  |
|  DHW | `on` | hot water active (Boolean) |
|  DOT | `false` |  |
|  ESI | `off` |  |
|  FAH | `false` |  |
|  FPA | `off` |  |
|  HED_DB | `` |  |
|  HED_DEV | `false` |  |
|  HED_EN | `false` |  |
|  HMD | `off` |  |
|  IHS | `ok` |  |
|  IHT | `27.40` | In House Temperature (Float) |
|  MMT | `15.0` |  |
|  PMR | `false` |  |
|  RS | `off` |  |
|  TAS | `off` |  |
|  TOD | `0` | Temp Override Duration |
|  TOR | `off` | Temp Override |
|  TOT | `21.0` |  |
|  TSP | `20.0` |  |
|  UMD | `clock` | User Mode (String) |


### Example Message Content
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
