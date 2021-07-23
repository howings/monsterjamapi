# MonsterJamAPIDesign
The Ultimate Toy Monster Truck API design project. By using SwaggerHub - the API design and documentation platform built for teams to drive consistency and discipline across their API development workflow. 

Objective: Design an API that allows users to obtain/retrieve information about all discontinued,
existing, physical, and virtual toy monster trucks from Spin Master in company DB. The virtual
properties are especially difficult to track, so a well-structured database along with API functions
should be implemented.

Estimated Team:
API Designer
API Documentation
API Development

Planning Resource: Monster Truck

GET - gives info for an array of trucks
Query Parameters - body
Responses - 200 payload: ID, Name, Type, Year, Status, Image File Name
404 not found

GET - gives info for a single truck
Query Parameters - ID
Responses - 200 payload: ID, Name, Type, Year, Status, Image File Name
404 not found

POST - insert info for a single truck
Query Parameters - ID, Name, Type, Year, Status, Image File Name
Responses - 200
400 invalid input
404 not found

PUT - Update info for a single truck
Query Parameters - ID, Name, Type, Year, Status, Image File Name
Responses - 200
404 not found

DELETE - remove info for a single truck
Query Parameters - ID
Responses - 200
404 not found

Implementation: Spin Master Monster Jam Encyclopedia App (Internal consumption)
Spin Master can create this application to help employees familiarize themselves with all the
Monster Jam Trucks that are created instead of flipping through documentations after
documentations. In the design department, errors in truck name referencing and or duplication
can be avoided.

Limitation:

Technical - This Monster Jam API starts with a basic structure and will expand in the future as an
open-source API when a stable version has been released.

Legal - At this point, the Monster Jam API is only available for internal use only. All third-party
usage is prohibited.

Pricing - Free for all Spin Master employees to use.

***API design only practice, no actual API was created.***
