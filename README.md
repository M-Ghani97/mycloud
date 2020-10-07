# OpenStack Deployment
A user-friendly platform to automate the whole process of cloud deployment based on an open-
source software OpenStack. The idea behind our product is to automate the whole process of cloud
development. Our product has automated the process of configuring individual components of OpenStack providing users an
effortless installation of the cloud.
### 1. Install Dependencies
./prep.sh
### 2. Add Target Hosts
./mycloud.sh node add <node_name> <nodes_ip(s)>
* ./mycloud.sh node add controller 1.1.1.1 2.2.2.2
### 3. Introspect Target Nodes
./mycloud.sh node introspect <target_host_username>
* ./mycloud.sh node introspect stack
### 4. Start Deployment
./mycloud.sh deploy 

## Other Commands
### Remove Target Hosts
./mycloud.sh node delete <nodes_ip(s)>
### List Target Hosts
./mycloud node list
