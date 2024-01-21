
## Types Of Load Balancer.


![typesloadbal](https://github.com/parimallpradhan/AWS-DevOps-Engineer/assets/153976296/217bac54-7982-42a4-bb1f-5ec10fd042e0)


## Difference between Application Load Balancer and Network Load Balancer.

![Loadbalnew](https://github.com/parimallpradhan/AWS-DevOps-Engineer/assets/153976296/f3d80e1d-9b19-4624-acf9-c40003e04125)


| Application Load Balancer                     |     Network Load Balancer |
| --------------------------------------------- | -------------------------------------- |
| It operates at Layer 7th of the OSI Model.    | It operates at Layer 4th of the OSI Model. |
| It is best suited for HTTP / HTTPS request.   | It is best suited for TCP / UDP request.  |
| Supports Health check at Application Layer    | Supports Health check at Transport Layer
| Uses content based routing algoritham.        | Uses flow based algoritham for routing traffic.  |
| Suitable for web application.                 | Suitable for High Performance and low latency applications like gaming.  |
| It supports content based , path based        | 
| and ssl termination.                          | 


# AWS CODE DEPLOY
This service is used to deploy the code on Production Servers.
## Deployment Types :

### Inplace
### Blue Green Deployment
