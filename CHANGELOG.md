# Ursula Changelog

## 0.6.0

- percona refactor 
- iptables lockdown
- install sensu certs to encrypt all sensu traffic

## 0.5.0

- simplified OpenStack API monitoring
- rabbitmq clustering (disabled by default)
- rabbitmq monitoring
- use system users for OpenStack services
- Barbican Support
- add stages to the ursula command
- Monitoring additions ( memcached, iscsid )
- mysql tuning

## 0.2.1

- Corrected memcached listen address
- Corrected horizon memcached config
- Fixed sensu-client OOO on fresh install

## 0.2.0

- Disabled nova conductor service
- Added system tools to common
- Added Ansible integration testing
- API HTTP checks
- Force UTC time
- Conditionally set OS_CACERT
- Sensu client enabled at boot
- Percona: specify the db arbiter host
- Percona montitoring: alert if not enough nodes in cluster
- DRY up log scanning
- Dashboard to use shared memcached servers vs local

## 0.1.0 and 0.1.1

- Initial release
