

## Service-Oriented Architecture (SOA)

  A Service-Oriented Architecture (SOA) is a design pattern in software design where application components provide services to other components through a communication protocol over a network. The concept of SOA is independent of any other programming language or platform.

  As in **object-oriented programming (OOP)** we are concerned with the **object**, similarly, in Service Oriented Architecture we are concerned with **services**.

### Core values of Service-Oriented Architecture

  * Business value
  * Flexibility
  * Strategic goals
  * Self-contained
  * Supports inter-operability
  * Location-transparent
  * Shared services

* * *

### Service-Oriented Architecture Patterns

  ![SOA patterns](https://www.researchgate.net/profile/Khaled-Elleithy/publication/314288067/figure/fig3/AS:469626577526784@1488979109147/Service-Oriented-Architecture-SOA-15.png)

  There are three roles in every Service-Oriented Architecture pattern:
    - service provider
    - service broker, service registry
    - service requester/consumer

  - The service provider works simultaneously with the service registry, questioning why and how the services are being offered such as security, availability, what to charge, etc.

  - The service broker accumulates information regarding the services which are available to those requesting it. The scope of the service broker is determined by whoever implements it.

  - The service requester marks entries in the broker registry and then binds them to the service provider. They may or may not be able to access multiple services depending on the capability of the service requester.

* * *

### Components of service-oriented architecture

  ![components os SOA](https://static.javatpoint.com/webservicepages/images/soa3.png)

  The service-oriented architecture stack can be categorized into two parts - functional aspects and quality of service aspects

  #### Functional aspects

  - **Transport:** It transports the service requests from the service consumer to the service provider and service responses from the service provider to the service consumer.

  - **Service Communication Protocol:** It allows the service provider and the service consumer to communicate with each other.

  - **Service Description:** It describes the service and data required to invoke it.

  - **Service:** It is an actual service.

  - **Business Process:** It represents the group of services that are called in a particular sequence associated with particular rules to meet the business requirements.

  - **Service Registry:** It contains the description of data that is used by service providers to publish their services.

  #### Quality of Service aspects

  - **Policy:** It represents the set of protocols according to which a service provider makes and provides the services to consumers.

  - **Security:** It represents the set of protocols required for identification and authorization.

  - **Transaction:** It provides the surety of consistent results. This means, if we use the group of services to complete a business function, either all must be completed or none of them would be completed.

  - **Management:** It defines the set of attributes used to manage the services.

* * *

### Implementation

  As SOA is independent of platforms and technologies, a wide variety of products can be used depending on the end goals of the system to implement the architecture. SOA implementations can use one or more protocols and can also use any file system tool to communicate data. The key to a successful implementation is to use independent services that perform tasks in a standardized way, without needing information about the calling application, and vice versa.

  Generally, the SOA is implemented with web services like **Simple Object Access Protocol (SOAP)** and **Web Services Description Language (WSDL)**.

  #### Some applications of Service-Oriented Architecture

  * SOA allows devices to use GPS.

  * Healthcare organizations use SOA to improve healthcare delivery.

  * Museums use SOA to create a virtualized storage system for their information and content.

  * Web services business use SOA  
    - to create reusable code
    - to promote interaction
    - for scalability
    - to reduce costs

### Benefits of Service-Oriented Architecture

  * High availability
  * Increased reliability
  * Service Reusability
  * Highly Scalable
  * Easily maintained
  * Promotes interoperability

* * *

As we can imagine, service-oriented architecture can be a hard rock to break, but once we understand its foundation blocks and the benefits it can provide our company, we'll be astonished we discovered it.

* * *

### References

  * Youtube
    * [Service-Oriented Architecture by Tech Cave](https://www.youtube.com/watch?v=jNiEMmoTDoE)  
    * [SOA | Software Engineering lectures by LMT](https://www.youtube.com/watch?v=A5Nom1hdJn8)

  * Blogs
    * [SOA introduction wikipedia](https://en.wikipedia.org/wiki/Service-oriented_architecture)  
    * [Service-Oriented Architecture](https://searchapparchitecture.techtarget.com/definition/service-oriented-architecture-SOA)  
    * [Service-Oriented Architecture importance and benefits](https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec)



