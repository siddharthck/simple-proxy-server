## Local Squid Proxy setup
- docker-compose up -d
- Proxy runs on -> http://127.0.0.1:8080
- basic auth user: test
- basic auth pw: test


## Squid access logs :
 - in dir : /var/log/squid/access.log

## How to check if proxy is working ? 

 - curl "www.gogle.com" -x "http://test:test@127.0.0.1:8080"

 You would see some entries in /var/log/squid/access.log
