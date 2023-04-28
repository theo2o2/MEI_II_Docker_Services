# Docker Services for iIndustry
- Node red
- Eclipse Mosquitto
- CrateDB
- Grafana
- Postgres for odoo
- Odoo

## Node Red
### Links
- http://localhost:1880 - Main app
- http://localhost:1880/ui - Dashboards
 
## Mosquitto
Listen to a Mosquito topic via cmd

```bash
mosquitto_sub -h localhost -t "sensor/temperature"
```

Publish into a Mosquito topic via cmd

```bash
mosquitto_pub -h localhost -t sensor/temperature -m 23
```

## CrateDB
To connect go to http://localhost:4200

## Grafana
Get started https://grafana.com/docs/grafana/latest/getting-started/build-first-dashboard/

## Odoo
- http://localhost:8069/ - Main app