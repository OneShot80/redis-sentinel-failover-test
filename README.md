# redis-sentinel-failover-test

Starts 2 x 3 instance master slave replication services and configures a single sentinel instance to monitor both services

## Ports Mapped

| Container   | HostPort |
| ----------- | -------- |
| Sentinel    | 26390    |
| redmaster1  | 6390     |
| redmaster2  | 6391     |
| redslave1   | 6392     |
| redslave1   | 6393     |
| redslave1   | 6394     |
| redslave1   | 6395     |
