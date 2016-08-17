# OpenStack-Installation

Automated OpenStack Services Installation Scripts focusing on OpenStack Mitaka Release.

## Requirement
Ubuntu 14.04 LTS

## How to Use
Modify parameters such as Interfaces (ex., Management, Control and Data) and passwords, and run it.

example)
$ vim keystone.sh
$ ./keystone.sh

## The execution order of scripts: OpenStack Control Node
update_package.sh
mysql.sh
keystone.sh
glacne.sh
nova_controller.sh
neutron_controller.sh
ovs_config.sh
dashboard.sh

## The Execution order of Scripts: OpenStack Compute Node
update_package.sh
nova_compute.sh
neutron_compute.sh
ovs_config.sh
