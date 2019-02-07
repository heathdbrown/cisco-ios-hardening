config_services
=========

Configures 'services' used by the management plane of the a switch/router device.

Role Variables
--------------

By default the config_services/defaults/main.yml all services are set to the most permissive settings.

|service password-recovery|enabled|
|service tcp-small-servers: disabled|
|ip finger|disabled|12.1+ disabled by default|
|ip bootp server|disabled|
|ip dhcp bootp ignore| disabled|12.2(8)T+|
|no service dhcp| disabled|
|no mop enabled| disabled|
|no ip domain-lookup| disabled|
|no service pad|disabled|
|no ip http servers|disabled|
|no service config|disabled|
|service tcp-keepalives-in|enabled|
|service tcp-keepalives-out|enabled|
|cdp|enabled|
|lldp|enabled|
