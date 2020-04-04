# sb-eureka-server-sample

This Server is needed to be up and running 

Any Producer can be registered - which can bring data from DB.
Some consumer which needs data - instead of directly calling - the other Micro Service, can register to this Eureka Server.

All Requests are going through Eureka Server since Producer and Consumer are registered to this project.

