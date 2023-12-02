## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- SOA, also known as Service Oriented Architecture. It is a software development method that makes use of software components which we also call 'services' that create any business applications. Each and every service can provide business capabilities. Along with this, the services can communicate with each other by using platforms and languages. In short, Service Oriented Architecture is a process for generating software programs that intends to accomplish obsolete objectives. Moreover, it encourages reusable software and business adaptability.

2. List and discuss the characteristics of SOA.
- According to XenonStack, there are seven (7) characteristics of Service Oriented Architecture. Initially, it supports loose coupling everywhere in the project. It also features interoperability support. SOA increases the quality of service, and it supports vendor diversity. Furthermore, it promotes discovery and federation. The good side of it is, SOA is location-transparent, and it is still a maturing and achievable idea.

3. Define Microservices.
- In accordance with Java, the concept of "microservices" alludes to an architecture design in which a program is developed as a group of distinct or isolated services. For instance, a big enterprise like Netflix is adopting microservices to increase revenue, company versatility, and scalability.

4. List and discuss the benefits of using Microservices.
- What benefits do enterprises get from using Microservices architectural design? Based on Dream Factory blog page, there are seven (7) key benefits of Microservices. Here are the following: 

A. Improved Scalability - Microservices offer a clear advantage for companies that expect to experience rapid growth. It denormalized data leading to faster performance. Its loose coupling leads to easier development and deployments. Moreover, it centralized logging and monitoring. Along with this, it increased fault tolerance. 

B. Better Fault Isolation for More Resilient Applications - With a microservices architecture, the failure of one service is less likely to negatively impact other parts of the application because each microservice runs autonomously from the others. 

C. Programming Language and Technology Agnostic - When creating a microservices-based application, developers can connect microservices programmed in any language. They can also connect to microservices running on any platform. This offers more flexibility to use the programming languages and technologies that best fit the project’s needs and your team’s skill set. 

D. Better Data Security and Compliance - One of the most significant benefits of microservices is that it enables businesses to take a more granular approach to data security. Since each service is responsible for a specific task, it is easier to implement security measures at the service level. 

E. Faster Time to Market and “Future-Proofing” - The pluggability of a microservices application architecture allows for easier, faster application development and upgrades. Developers can quickly build or change a microservice, then plug it into the architecture with less risk of coding conflicts and service outages. 

F. Greater Business Agility and Support for DevOps - As enterprises strive to become more agile, they are turning to microservices to increase their speed-to-market. A microservices application architecture supports the rapid delivery of software by allowing developers to work on small, independent pieces of an application. These pieces can be quickly deployed and tested without affecting the rest of the application. 

G. Support for Two-Pizza Development Teams - With microservices, each team can work independently on its own service. They can move quickly and make decisions without having to coordinate with other groups. This increases efficiency and allows for more rapid innovation.

5. List and discuss the similarities and differences of SOA and Microservices.
- Similarities 
- SOA and microservices are both split large-scale, intricate programs into more manageable or flexible programs. 
- SOA and microservices provide increased scalability to support the firm in developing and implementing apps more swiftly. 
- SOA and microservices are both cloud-based or hybrid cloud-based agile development frameworks. 

Differences: 
- Reusability vs Data Duplication * In an SOA model, developers reuse components as a means of enhancing scalability and efficiency. On the other hand, in a microservices architecture, developers reuse code or duplicate data to increase efficiency and maintain high levels of independence. 

- Synchronous Calls vs Asynchronous Communication * In SOA, services are made available throughout the enterprise via synchronous protocols. However, in a microservices architecture, synchronous calls will create real-time dependencies, which in turn reduces reliability and resiliency. 

- Source Data vs Local Data * In SOA, all applications should be able to receive and update data at the source level at the same time. However, this approach also creates dependencies across services, which is not ideal in a microservices architecture. 

- ESB vs API * In an SOA, services are organized and coordinated through a common communication channel called an enterprise service bus (ESB). Since all communication is centralized within the ESB, this introduces the risk of a single point of failure for all services. To avoid this issue and maintain independent operation, microservices communicate via API.

6. Define Web Services.
- Based on my research, web devices are the method of communication between the two systems, and this is also how communication between the two systems works using the internet software.

7. List and discuss the benefits of using Web Services.
- This is the benefits using the Web Services, this is the creation and fusion of software across many platforms, Heres the follow:

Interoperability:
    Whatever the underlying technologies or programming languages of various applications and systems, web services enable interoperability between them. They make use of common protocols like XML, SOAP, and HTTP to facilitate smoother communication between heterogeneous systems.
Platform Independence:
    This is the good benefits using the web service because its supported with the wide rage of platforms and operating systems.
Loose Coupling:
    This loose coupling, its easy to maintenance and updates without disruptinig the system
Reusability:
    tihs kind of web service it can make allow to access the functionality with the developers

8. List and discuss the characteristics of Web Services.
- There are five characteristics of Web Services according to Javapoint website. The first characteristic on the list was XML-based. In order to signify data and transmit records, a web service requires XML. Coarse-grained was also a characteristic of Web Services, in which it offers greater features than more precise assistance. Loosely Coupled happens when XML messages are transmitted between both parties via a web API for communication. Moreover, capability to be synchronous and asynchronous was also part of Web Services characteristics. While waiting for a response, the user can invoke synchronous Web services across current Web interfaces. RPC-oriented message is used to support synchronous Web services. Instead of waiting for a response, customers may request asynchronous Web services through current Web processes. Furthermore, Supports RPC was the last characteristic on the list. Through the provision of specific amenities that are comparable to those of a traditional component, a web service facilitates RPC.

9. List and discuss the distinct roles in Web Services Architecture.
- The service provider, service registry, and service requester are the three roles that play a part in the architecture of web services. The web service provider develops and generates the web service accessible to customer applications. The client application that has the capability of getting in touch with a web service is known as a requestor. Any language-based program that searches an online platform for the features can be used as the client application. The application provides an address to the UDDI, but the brokerage firm is unavailable.

10. List and discuss the Web Services Components.
- SOAP also known as Simple Object Access Protocol was one of Web Services Components. It is a platform and language independent protocol in which it employs XML to access web services. UDDI is a abbreviation for Universal Description, Integration, and Discovery is also a part of Web Services Components. It describes, publishes, and locates webservices using an XML-based interface. WSDL in which stands for Web Services Description Language was the last component of Web Services. WSDL presents webservices and demonstrates how to access them using an XML-based interface.

Source/Reference: 
2. https://www.xenonstack.com/insights/service-oriented-architecture 
4. https://blog.dreamfactory.com/7-key-benefits-of-microservices/ 
5. https://www.crowdstrike.com/cybersecurity-101/cloud-security/soa-vs-microservices/
7. https://www.educba.com/advantages-of-web-service/
8. https://www.javatpoint.com/restful-web-services-characteristics-of-web-services
9. https://www.shine.com/blog/what-are-web-services
10. https://tutorialshut.com/what-are-web-services-types-and-components/