## SOFTWARE DEVELOPMENT LIFE CYCLE (Online Shopping System) 

The Online Shopping system enables vendors to set up online shops, customers to browse through the shops, and a system administrator to approve and reject requests for new shops and maintain lists of shop categories. Also, on the agenda is designing an online shopping site to manage the items in the shop and also help customers purchase them online without having to visit the shop physically. Our online shopping mall will use the internet as the sole method for selling goods to its consumers. Shopping will be highly personalized and the mall will provide lower prices than most competitors.


![]([Aspose.Words.54e7b9d9-31bc-4eca-83b5-eae7ad3dc277.003.png](https://media4.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif?cid=790b7611503a7f3cf165d6927a9dac42b4b08dce8de36142&rid=giphy.gif&ct=g))



## REQUIREMENT ANALYSIS

This is a small-scale project for Online shopping System. The basic idea is that the candidates can buy products from anywhere during any time by using their card number and password provided to them. The database will maintain the product details information. Customers can view their product details using the card details. This Online shopping system involves two types of users:

`CUSTOMER ROLE` The customers can login/logout the System. His/her can view his/her product details and buy their product. The customer can just view the information whereas he/she could not make changes in the database.

`ADMINISTRATOR ROLE` The administrator plays a vital role in the Online shopping system. The administrator controls the entire database. The report of the product is generated by the administrator itself. The main role of the administrator is to safeguard the database and can add/delete the products from the database.

|Tools|Version|Editor|Description|Size|
| - | - | - | - | - |
|WampServer|2.5| |Application and database server|138ko|
|Gantt Project|2.0.10|Free software foundation|To plan our Project|9.22 Mo|
|Visual Paradigm|12.1| |Modelling software|2.10kb|
|Microsoft office|2019|Microsoft corporation|For typing our report| |
|Netbeans|8.0.2| |IDE|260 Mo|
|Mozilla Firefox|40|Google|Web browser|8687ko|
# Online Shopping Modelling 

Tools
--------------------------------------

- Visual Paradigm for Unified Modeling Language (UML), 
- Gantt Project for Project Planning,
- Microsoft Word for Technical Documentation.
- Mysql workbench 
- Mysql Server 
- DBeaver
- Selenium IDE


Project Delivery
@ -38,201 +22,62 @@ Project Delivery
- Selenium Test Script


- Account Management Package

## PLANNING 
Project plan with Gantt project

![](gantt.png)
![](/AccountManagementPackage.jpg)

- Activity Order

##  MODELING THE REQUIREMENTS
### Login 
It is the login session for the Administrator, customer and Exit.
### Product Details 
It is used to view the product details from the database. 
### Add New Products
It is used to add a product into the database and it includes searching for product details and removing a product from the database. 
### Updating the Quantity
It is used to update the product details from the database


## UML Diagram 
### Use case Diagram 

Use Case diagrams show the various activities the users can perform on the system. The System is something that performs a function. They model the dynamic aspects of the system. It provides a user’s perspective of the system. 

`Actor` is a user of the system playing a particular role. 

`Use case` is a particular activity a user can do on the system. Relationship:
![](/ActivityOrder.jpg)

Relationships are simply illustrated with a line connecting actors to use cases.
- Class Diagram

- UseCase Management Package
![](/ClassDiagram.jpg)

![](/UseCaseManagementPackage.jpg)
- Deployment Diagram

### Class Diagram 
A class diagram shows the building blocks of any object-orientated system. Class diagrams portray a static view of the model, or part of the model, describing what attributes and behavior it has rather than detailing the methods for achieving operations. Class diagrams are most useful in illustrating relationships between classes and interfaces. Generalizations, aggregations, and associations are all valuable in reflecting inheritance, composition or usage, and connections respectively.
![](/DeploymentDiagram.jpg)

- Object Diagram

![](/ClassDiagram.jpg)
![](/ObjectDiagram.jpg)

- Order Management Package

### Package Diagram
![](/OrderManagementPackage.jpg)

**Package diagram** is UML structure **diagram** which shows structure of the designed system at the level of **packages**. The following elements are typically drawn in a **package diagram**: **package**, packageable element, dependency, element import, **package** import, **package** merge.
- Package

![](/Package.jpg)

 Package <<Order Management>>
- product

 ![](/OrderManagementPackage.jpg)
![](/product.jpg)

  
 Package <<Product Management>>
  
- product Management Package

![](/productManagementPackage.jpg)

- Pysical Data Model

### Sequence Diagram 
A sequence diagram in Unified Modeling Language (UML) is a kind of

interaction diagram that shows how processes operate with one another and in what order. It is a construct of a Message Sequence Chart. Sequence diagrams are sometimes called event diagrams, event scenarios, and timing diagrams.
![](/PysicalDataModel.jpg)

 Sequence Order Product
- Sequence Order Product

![](/SequenceOrderProduct.jpg)

 Sequence Order Product Communications
- Sequence Order Product Communications

![](/SequenceOrderProductCommunications.jpg)

 Sequence Search Products
- Sequence Search Products

![](/SequenceSearchProducts.jpg)

 Sequence Search Products Communications
- Sequence Search Products Communications

![](/SequenceSearchProductsCommunications.jpg)

- UseCase Management Package


### Activity Diagram

In UML, an activity diagram is used to display the sequence of activities. Activity diagrams show the workflow from a start point to the finish point detailing the many decision paths that exist in the progression of events contained in the activity. They may be used to detail situations where parallel processing may occur in the execution of some activities. Activity diagrams are useful for business modelling where they are used for detailing the processes involved in business activities.



![](/ActivityOrder.jpg)


### Object Diagram

objects in a system and representing the associations between the objects as links. The interaction between the objects is denoted by arrows. To identify the sequence of invocation of these objects, a number is placed next to each of these arrows.



![](/ObjectDiagram.jpg)



### Communication Diagram 
Communication diagram formerly called collaboration diagram is an interaction diagram that show similar information to the sequence diagram but it main focus is on object relationship. On communication diagram object are shown with association connectors between them, messages are added to the associations and show as short arrows pointing in the direction of the message flow. The sequence of message is shown through a numbering scheme.

Communication diagram <<search product>>


![](SequenceSearchProductsCommunications.jpg)



Communication <<order product>>


![](SequenceOrderProductCommunications.jpg)


### Component Diagram

Component diagrams illustrate the pieces of software, embedded controllers, etc., that will make up a system. A component diagram has a higher level of abstraction than a Class Diagram - usually a component is implemented by one or more classes (or objects) at runtime. They are building blocks so a component can eventually encompass a large portion of a system


![](Components.png)



## SOFTWARE DEPLOYMENT 
### Deployment Diagram

A deployment diagram models the run-time architecture of a system. It shows the configuration of the hardware elements (nodes) and shows how software elements and artifacts are mapped onto those nodes.


![](/DeploymentDiagram.jpg)


### Physical Data Model
The physical data model (PDM) presents all the necessary tables in our database. It provides a technical and concrete solution which enable the implementation of the web application. The Physical Data Model specifies the type of Database Management System (DBMS) to be used in managing the database. This model exposes a detail structure of the different database files.


![](/PysicalDataModel.jpg)


## SOFTWARE TESTING

### Preparing Test Plan 
Preparing the test plan is the first step in the last phase of the software development cycle .The test plan consists of all the activities that had to be done in the software testing phase. This test plan has been documented using the rational test manager software. 

### Perform Validation Testing 
Software is completely assembled as a package interfacing errors have been uncovered and a final series of software test validation testing may begin. Validation successive when the customer is satisfied.

### Validation Test Criteria 
Software validation is achieved through a series of black box test that

demonstrates conformity with requirements. 

### Coverage Analysis 
Coverage analysis is used to identify untested code. Using rational pure

coverage, untested code can easily be identified. 

### Memory Leaks 
Memory leak testing has been done using rational purity software.



 ## User Account
 ------------------------------

![](/UserAccount.png)

### Products
  
![](/Products.png)
  
### Shopping cart
  
![](ShoppingCart.png)

### 6.4. Track order
  
![](TrackOrder.png)
  
### Admin page

![](AdminPage.png)

### Product Management
  
![](ProductManagement.png)
  
### Log file management
  
![](LogFile.png)








![](/UseCaseManagementPackage.jpg)
