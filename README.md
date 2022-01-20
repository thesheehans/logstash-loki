
https://grafana.com/docs/loki/latest/clients/logstash/

# Configuration Properties
## url
The url of the Loki server to send logs to. When sending data the push path need to also be provided e.g. http://localhost:3100/loki/api/v1/push.

If you want to send to GrafanaCloud you would use https://logs-prod-us-central1.grafana.net/loki/api/v1/push.

## username / password

Specify a username and password if the Loki server requires basic authentication. If using the GrafanaLab’s hosted Loki, the username needs to be set to your instance/user id and the password should be a Grafana.com api key.

https://<org>.grafana.net/org/apikeys


