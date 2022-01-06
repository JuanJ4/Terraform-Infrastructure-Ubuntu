## Automated AWS Cloud Infrastructure With Terraform

1. Created a VPC
2. Created Internet Gateway
3. Created Custom Route Table
4. Created a Subnet
5. Associated Subnet with Route Table
6. Created Security Group to allow port 22,80,443 (SSH, HTTP, HTTPS)
7. Created a network interface with an ip in the subnet that was created in step 4
8. Assigned an elastic IP to the network interfacecreated in step 7
9. Created ubuntu server and installed/enabled apache2
