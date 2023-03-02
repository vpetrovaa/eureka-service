# Service Registry Pattern

<a href="https://microservices.io/patterns/service-registry.html">
The pattern full description
</a>

During creating monolithic application we used one service run in specific fixed location.
However, in microservice architecture we use several services. Their network locations are dynamically assigned
and it is often hard to keep track of microservice locations beforehand.
So, the service discovery pattern was introduced, and it allows developers to find the network locations of microservices without injecting or coupling services.

