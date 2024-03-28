
This project demonstartes how to setup a VPC so that you use it in production environment to setup servers

In this project, I have deployed a web server inside a VPC in AWS. To increase the resilency and availablity, the VPC is created in 2 avaialbility zones. For additional security, the application is deployed in a Private subnet. It recieves traffic through an Application Load Balancer and can connect to the internet via NAT gateway. By attaching an Auto-scaling group through Launch template, the application is made highly scalable. 

# Visit my blog for Proof of Concept(POC)

https://sowmya-mb-techblogs.hashnode.dev/part1-deploying-an-application-in-a-vpc
