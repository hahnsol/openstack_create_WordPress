### create "WordPress" on the openstack with CentOS7

<br>
<br>


#### 1. vm1-web 
- image: CentOS-7-x86_64-GenericCloud-2003.qcow2  (openstack images)
- flavor: vCPU=1, Mem=2046, Root Disk=10G)
- network: internal network connecting router connected external network
- security group : SSH&HTTP&ICMP
- key-pair
- volume X
- allocate floating ip 

<br>

#### 2. vm2-mariadb 
- image: CentOS-7-x86_64-GenericCloud-2003.qcow2  (openstack images)
- flavor: vCPU=1, Mem=2046, Root Disk=10G)
- network: internal network connecting router connected external network
- security group : SSH&HTTP&ICMP
- key-pair
- volume X
- allocate floating ip 
