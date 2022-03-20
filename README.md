# LOAD-BALANCER-SOLUTION-WITH-APACHE
Project 8: Adding Load Balancer to [**Project 7:** DevOps Tooling Website Solution](https://github.com/hectorproko/Devops-Tooling-Website-Solution/blob/main/Project7_Step.md)  

In our set up in **Project 7** we had 2 Web Servers and each of them had its own public IP address and public DNS name. We had to access them by using different URLs, which is not a nice user experience to remember addresses/names of even 2 server.
In order to hide all this complexity and to have a single point of access with a single public IP address/name, a **Load Balancer** can be used. A Load Balancer (LB) distributes clients’ requests among underlying Web Servers and makes sure that the load is distributed in an optimal way.

Technologies/Tools used:
* AWS (EC2)
* Ubuntu
* Apache (Load Balancer)
* GitBash