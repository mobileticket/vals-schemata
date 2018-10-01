# Validation Services  Schemata

This repository contains JSON schemata for Samverkansgruppen Validation Services messages.

N.B. All schemas are written in YAML format to increase readability.


## MQTT Topics

| Schema          | MQTT Topic                           | Direction |
| --------------- | ------------------------------------ | --------- |
| none            | service/gps/rmc                      | in        |
| vehicle         | service/v1/vehicle                   | in        |
| journey         | service/v1/journey                   | in        |
| at_stop         | service/v1/atStop                    | in        |
| last_stop       | service/v1/lastStop                  | in        |
| next_stop       | service/v1/nextStop                  | in        |
| remaining_stops | service/v1/remainingStops            | in        |
| latest_ticket   | service/v1/Validate/latestticket     | out       |
| status          | service/v1/Validate/status           | out       |
| run_monitoring  | service/itxpt/v2/avms/runmonitoring  | in        |
