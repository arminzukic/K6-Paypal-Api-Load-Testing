# K6-Paypal-Api-Load-Testing
The Load Testing Project of the PayPal API with K6 Tool

- `docker-compose up -d influxdb grafana`
- Load http://localhost:3000, and import the `grafana_dashboard-v1.json` config to a new dashboard.
- `docker-compose run k6 run /tests/load-test.js`