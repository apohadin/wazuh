# Wazuh Vagrant Simulation for testing purposes

Wazuh master
Wazuh worker
Wazuh client

Wazuh master
- composes 
  a. Kibana
  b. Wazuh manager with api
  c. Elasticsearch
  d. Filebeat
Wazuh worker
- compses the same content with master but on active standby

Wazuh client is the basic client monitored for testing purposes
