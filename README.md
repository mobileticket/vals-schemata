# Validation Services  Schemata

This repository contains JSON schemata for Samverkansgruppen Validation Services messages.

N.B. All schemas are written in YAML format to increase readability.


## MQTT Topics

| Schema          | MQTT Topic                          | Direction | Required |
| --------------- | ----------------------------------- | --------- | -------- |
| none            | service/gps/rmc                     | in        | Yes      |
| vehicle         | service/v1/vehicle                  | in        | Yes      |
| journey         | service/v1/journey                  | in        | Yes      |
| at_stop         | service/v1/atStop                   | in        | Yes      |
| last_stop       | service/v1/lastStop                 | in        | Yes      |
| next_stop       | service/v1/nextStop                 | in        | Yes      |
| remaining_stops | service/v1/remainingStops           | in        | Yes      |
| latest_ticket   | service/v1/Validate/latestticket    | out       | Yes      |
| status          | service/v1/Validate/status          | out       | Yes      |
| notification    | service/v1/Validate/notification    | out       | No       |
| run_monitoring  | service/itxpt/v2/avms/runmonitoring | in        | No       |
