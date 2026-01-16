# Grafana in a homelab

This repo is my personal configuration for using grafana
on my homelab.
Prometheus is an open-source visualisation and analytics software.
The
[grafana docs](https://grafana.com/docs/grafana/latest/fundamentals/)
are pretty good and can explain a bit more about what that
means.

## Environment Variables

I've set up the environment variables to configure grafana with
SSO via Authentik.

## Dashboards

I currently have no custom dashboards, just imported ones:
- [Authentik](https://grafana.com/grafana/dashboards/14837-authentik/)
- [Traefik](https://grafana.com/grafana/dashboards/17346-traefik-official-standalone-dashboard/)
- [Prometheus](https://grafana.com/grafana/dashboards/19268-prometheus/)
- [Gitea](https://grafana.com/grafana/dashboards/13192-gitea/)
- [Crowdsec](https://github.com/crowdsecurity/grafana-dashboards)

Perhaps in the future I will store the json for custom dashboards here.