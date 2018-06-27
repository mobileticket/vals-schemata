# Validation Services  Schemata

This repository contains JSON schemata for Samverkansgruppen Validation Services messages.

N.B. All schemas are written in YAML format to increase readability.


## MQTT Topics

| Schema        | MQTT Topic                       | Direction |
| ------------- | -------------------------------- | --------- |
| journey       | service/v1/journey               | in        |
| at_stop       | service/v1/atStop                | in        |
| last_stop     | service/v1/lastStop              | in        |
| next_stop     | service/v1/nextStop              | in        |
| latest_ticket | service/v1/Validate/latestticket | out       |
| status        | service/v1/Validate/status       | out       |
