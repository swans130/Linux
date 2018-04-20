# Linux
- Access
  - ec2-54-201-34-240.us-west-2.compute.amazonaws.com
  - 54.201.34.240
  - SSH : 2200

- Installations
  - Apache
  - Postgres
  - Python + packages

- Configurations
  - Change SSH to port 2200
  - Block remote login for root
  - Require RSA authentication (no password)
  - Limit postgres access for catalog db to only catalog user
  - Deny all incoming traffic besides ports 2200, 80, 123 with UFW
 
- Third Party
  - Cloud Provider : Amazon EC2
