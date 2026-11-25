# https_ssl

Project on HTTPS and SSL termination with HAProxy.

| File | Description |
|------|-------------|
| `0-world_wide_web` | Bash script that displays DNS record information of subdomains |
| `1-haproxy_ssl_termination` | HAProxy config that terminates SSL on port 443 |
| `2-redirect_http_to_https` | HAProxy config that redirects HTTP to HTTPS with a 301 |
