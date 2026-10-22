# Web infrastructure design

Whiteboard designs of web infrastructures for `www.foobar.com`, from a single server to a secured, monitored and scaled-up stack.

## Tasks

| # | File | Design |
|---|------|--------|
| 0 | `0-simple_web_stack` | One server with Nginx, application server, code base and MySQL (LAMP-style stack) |
| 1 | `1-distributed_web_infrastructure` | HAProxy load balancer + 2 servers, MySQL Primary-Replica |
| 2 | `2-secured_and_monitored_web_infrastructure` | 3 firewalls, SSL certificate (HTTPS), 3 monitoring clients |
| 3 | `3-scale_up` | HAProxy cluster + web, application and database servers split onto their own machines |

Each file starts with the link to its diagram (stored in `images/`), followed by the explanation of every component and the issues of the design.

## Key concepts

- **LAMP**: Linux, Apache, MySQL, PHP/Python (a classic web stack)
- **SPOF**: Single Point Of Failure
- **QPS**: Queries Per Second

## Author

Antonio Torres
