# bootstrap-bigip-via-iworkflow
Work in progress - Postman collection with environment variables for bootstrapping a new BIG-IP with blank configuration via iWorkflow

Requirements:
- iWorkflow already setup and running with:
  - license pool
  - tenant
  - connectivity
- freshly provisioned BIG-IP with management IP connectivity

So far this collection contains the REST calls for:
- adding a BIG-IP to iWorkflow
- add DNS/NTP settings to BIG-IP
- leveraging iWorkflow REST proxy to:
  - add VLANs to BIG-IP
  - add Self IPs to BIG-IP
