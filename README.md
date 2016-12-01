Openvpn client
=========

A very simple openvpn installation that connect the machine to an openvpn server.

Requirements
------------

Tested only on Ubuntu 14.04

Role Variables
--------------

```
# client config name, used as an id by openvpn service.
openvpn_client_config_name: ""

# client config
openvpn_client_config_ovpn: ""

# extra files that can be referenced in client config
# list of dict containing the followig keys
# name: file name
# content: file content
openvpn_client_config_additional_files: []
```


Dependencies
------------

None

License
-------

BSD

Author Information
------------------

STEAMULO - http://www.steamulo.com
