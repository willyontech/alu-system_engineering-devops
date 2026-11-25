# Load Balancer

This project introduces load balancing using HAProxy and Nginx.

## Tasks

- 0-custom_http_response_header: Configure Nginx to return the hostname in the X-Served-By HTTP response header.
- 1-install_load_balancer: Install and configure HAProxy to distribute traffic between two web servers using round-robin.

## Servers

| Server | Role |
|---|---|
| 6902-web-01 | Web server 1 |
| 6902-web-02 | Web server 2 |
| 6902-lb-01 | Load balancer |

## Technologies

- Bash
- Nginx
- HAProxy
- Ubuntu
- SSH
- HTTP
