
https://grafana.com/docs/loki/latest/clients/logstash/

# Configuration Properties

Set by `export` or in a `.env` file.

## LOKI_URL

The url of the Loki server to send logs to. When sending data the push path need to also be provided e.g. http://localhost:3100/loki/api/v1/push.

If you want to send to GrafanaCloud you would use https://logs-prod-us-central1.grafana.net/loki/api/v1/push.

# Credentials

While logged in to your Grafana account, navigate to the Grafana Cloud Portal, which should be located at https://grafana.com/orgs/&lt;your-organization-name&gt;, and complete the following steps.

## LOKI_USERNAME

If using the GrafanaLab’s hosted Loki, the username needs to be set to your instance/user id

Click the User Settings link in the top right and note your Username.

## LOKI_PASSWORD

Obtain an API key, setting its Role to MetricsPublisher. If you want LogStream or an external KMS to manage the API key, configure a key pair that references the API key.
