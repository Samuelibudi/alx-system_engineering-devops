# HTTPS SSL

The following tasks were undertaken to familiarise learners with network security concepts.

| Tasks | Description |
| ----- | ----------- |
| 0-world_wide_web | Configures domain zone such that subdomain points to load balancer |
| 1-haproxy_ssl_termination | Creates a certificate using certbot and configures HAproxy to accept encrypted traffic for subdomain www |
| 100-redirect_http_to_https | configures HAproxy to automatically redirect HTTP traffic to HTTPS |
