# system-monitor
System monitor utilising InfluxDB, Telegraf and Grafana.
To use:
1. Edit .env file and change the grafana and influxdb username and password.
2. Source .env
3. Run `docker-compose -d up` or `make up` (note: makefile runs docker-compose with sudo)
4. Navigate to http://localhost:3000 to log into Grafana and create your dashboard.
