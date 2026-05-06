# Route Table, Internet Gateway and Nat Gateway

Route table acts as a traffic director sending network traffic to the right direction. In AWS, a subnet is associated with at least a single route table for network traffic. For public facing resources such as application load balancers and web servers their route table contains two entries, one pointing to the local VPC and another pointing to the internet. For resources that are private, their route table either has a nat gateway that points outbounds towards the public internet or it doesn't have a public connection at all but connects to devices within the AWS cloud.
Security group chaining — the professional way to configure AWS firewalls. Instead of allowing 0.0.0.0/0 everywhere, each tier only accepts traffic from the previous tier (using SG-to-SG rules). Zero internet exposure for the database. Architecture diagram below. #AWSsecurity #VPC #CloudNetworking
![alt text](<WhatsApp Image 2026-05-06 at 16.02.45.jpeg>)
![alt text](<WhatsApp Image 2026-05-06 at 16.50.55 (1).jpeg>)
![alt text](<WhatsApp Image 2026-05-06 at 16.50.55 (2).jpeg>)
![alt text](<WhatsApp Image 2026-05-06 at 16.50.55.jpeg>)
