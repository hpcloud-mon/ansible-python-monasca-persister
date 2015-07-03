#monasca-persister
Installs the python version of the monasca-persister as a pypi package which is 
part of the [Monasca](https://wiki.openstack.org/wiki/Monasca) project.


##Python Requirements

Requires Variables be defined for:
- zookeeper_hosts - A comma seperated list of kafka hosts with optional port
- kafka_hosts - A comma seperated list of kafka hosts with optional port
- influxdb_host
- influxdb_user
- influxdb_password

## Optional

- run_mode: One of Deploy, Stop, Install, Configure or Start. The default is Deploy which will do Install, Configure, then Start.

##License
Apache

##Author Information
Angelo Mendonca
Monasca Team email monasca@lists.launchpad.net
