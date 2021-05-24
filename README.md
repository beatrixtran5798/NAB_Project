# NAB_Project
This is my NAB Java coding challenge project.
=====================================================================
Project's ERD:



![ERDDiagram](https://user-images.githubusercontent.com/51369830/119114584-7cdde900-ba50-11eb-9f9e-cc6d01522706.jpg)



DB Design:


![DB](https://user-images.githubusercontent.com/51369830/119294958-da0bb180-bc7f-11eb-9ece-a40d993c1569.PNG)

===========================================================================
Software development principles, patterns & practices being applied:

3 layers : Controllers - Services - Repositories.

===========================================================================

Folder structure and the key Java libraries and frameworks being used:

Folders:

_ configuration:	Configuration classes for specific technologies configuration.
_ dto:	Contains DTOs (Data Transfer Object) as POJO Java class, there're sub folders corresponding to their functionality (httprequest, httpresponse, entity ...).
_ property:	Configurable properties, can be reloaded via refresh endpoint.
_ repository:	Jpa Repository interfaces for Spring Data Jpa implementations.
_ service:	Main logic computation here.
_ utility:	Utility classes.

Libraries/Frameworks:

_ Spring Boot:	Today's de-facto standard that Java applications cannot be without.
_ Spring Data Jpa:	More abstraction above Hibernate ORM libs leads to faster development.

===========================================================================

Required steps in order to get the application run on a local computer:

(updating...)
