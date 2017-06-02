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
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/uiStatus_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _uiUpdate_ | Data type of value |
|  value | _{"CPM": "auto", "CTR": "room", "TOR": "off", "TOT": "21.0", "CTD": "2017-05-29T17:21:02+01:00 Mo", "BLE": "false", "DOT": "false", "BAI": "No", "HED_DB": "", "RS": "off", "BMR": "false", "FAH": "false", "TOD": "0", "DAS": "off", "HMD": "off", "FPA": "off", "BBE": "false", "DHW": "on", "CSP": "8", "ESI": "off", "ARS": "init", "HED_DEV": "false", "PMR": "false", "UMD": "clock", "MMT": "15.0", "TAS": "off", "HED_EN": "false", "IHT": "27.40", "TSP": "20.0", "IHS": "ok"}_ |  |
|  writeable | _0_ | Writable parameter (0=No) |


### uiUpdate type details 

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  ARS | _init_ |  |
|  BAI | _No_ | Boiler Indicator (String 'CH' : 'central heating', 'HW' : 'hot water', 'No' : 'off') |
|  BBE | _false_ | Boiler Block (Boolean) |
|  BLE | _false_ | Boiler Lock (Boolean) |
|  BMR | _false_ | Boiler Maintenance (Boolean) |
|  CPM | _auto_ | Clock Program (String) |
|  CSP | _8_ | Current Switch point (Float) |
|  CTD | _2017-05-29T17:21:02+01:00 Mo_ |  |
|  CTR | _room_ |  |
|  DAS | _off_ |  |
|  DHW | _on_ | hot water active (Boolean) |
|  DOT | _false_ |  |
|  ESI | _off_ |  |
|  FAH | _false_ |  |
|  FPA | _off_ |  |
|  HED_DB | __ |  |
|  HED_DEV | _false_ |  |
|  HED_EN | _false_ |  |
|  HMD | _off_ |  |
|  IHS | _ok_ |  |
|  IHT | _27.40_ | In House Temperature (Float) |
|  MMT | _15.0_ |  |
|  PMR | _false_ |  |
|  RS | _off_ |  |
|  TAS | _off_ |  |
|  TOD | _0_ | Temp Override Duration |
|  TOR | _off_ | Temp Override |
|  TOT | _21.0_ |  |
|  TSP | _20.0_ |  |
|  UMD | _clock_ | User Mode (String) |


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
