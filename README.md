# Domain and information model

Summary:
Introduction to the concept of "domain" and learn how to identify domain entities. System Information Model building and testing it using CRUD.

## Contents

1. [Chapter I](#chapter-i) \
   1.1. [Task 1. Haircut Appointment](#41) \
   1.2. [Task 2. Delivery of Orders](#42)
2. [Chapter II](#chapter-ii) \
   2.1. [Exercise 00 — Entity Identification](#51) \
   2.2. [Exercise 01 — Entity Testing by CRUD](#52) \
   2.3. [Exercise 02 — Building a Data Dictionary](#53) \
   2.4. [Exercise 03 — Building a Logical Data Model](#54)
## Chapter I <div id="chapter-i"></div>

### Description of tasks

### Task 1. Haircut Appointment <div id="41"></div>

The management of a chain of barbershops decided to implement an online booking system. The main objective is to develop the business by expanding the customer base through the possibility of online registration, as well as to reduce employee labour costs and manual labour by automatically informing customers through communication channels. 

Both registered and unregistered visitors can book an appointment on the website. When making an appointment, they can select the type of service: hairdressing or cosmetology, as well as the service itself, the master and the time from the available intervals. The system should provide automatic sending of reminders to clients through the communication channel chosen by the client (Telegram, WhatsApp, VK, SMS) according to the schedule set by the manager. After receiving a service, the system offers the client to evaluate the service and write suggestions on how to improve the work.

The schedule of masters and the services provided by each master should be entered by the manager, who may be more than one person. This person is also responsible for keeping the schedule up to date and adjusting it if necessary, communicating with customers manually, marking the service, charging and accepting payment, sending the payment data to the accounting department. The manager can also receive reports on completed services and view customer feedback.

Each master has the ability to view the schedule and appointments for their services, as well as customer reviews.

### Task 2. Delivery of Orders <div id="42"></div>

During the lockdown, many grocery stores and food companies dramatically increased their online sales and the need for quick delivery of small quantities to individual customers increased. 

A group of students got together and decided to create a delivery service startup. The idea is to quickly receive information about orders, pickup location and time, delivery location, desired delivery dates, and distribute this information to couriers who will pick up the order at the pickup location and deliver it to the delivery location. They decided to develop an online system where orders could be collected and quickly sorted for delivery by couriers.

The first step was to collect orders from stores and caterers in any way possible and have the operator enter them into the system in a consistent format, as well as developing a mobile application for the courier. The courier should be able to view order information, select an order from those available, book it, pick it up at the collection point and deliver it to the customer. The result of the courier's actions should be immediately reflected in the system via a mobile application. The system should also include a dispatcher who controls the couriers and reassigns orders if necessary. Information on received orders should be sent to the accounting department (to another IT system) to calculate delivery charges with order suppliers. Order delivery information should also be sent to the accounting department to calculate payment to couriers. Accrued payment should be transferred to the system and displayed in the courier's personal account. And there should also be an administrator's workstation, where couriers are registered and access rights are assigned to all of them.

## Chapter II <div id="chapter-ii"></div>

### Exercise 00 — Entity Identification <div id="51"></div>

**For each task:**

1. Identify at least 7 entities (following the order of entity selection) with which the system will work.
2. Define a name for each entity, specify the purpose.
3. Define the main (key) attributes for each entity.
4. Indicate your answers in the turn-in file ex00\_<product predix>\_entity.xlsx.

### Exercise 01 — Entity Testing by CRUD <div id="52"></div>

**For task 1:**

1. Perform a CRUD test of the completeness of actions for each entity.
2. Specify in a table (similar to the one shown in Fig. 2 in item 3) for CRUD testing:
   1. Specify in the table the stakeholder roles and actions under which the CRUD operation is performed;
   2. In case it is not clear from the task or interview conditions who performs the operation and when, suggest a hypothesis or indicate the need for clarification from stakeholders (highlight in color).
3. Indicate your answers in the turn-in file ex01\_<product prefix>\_crud.xlsx.

### Exercise 02 — Building a Data Dictionary <div id="53"></div>

**For each task:**

1. Build a data dictionary.
2. Include entity name, mnemonics, concept description, data type, and obligingness in the data dictionary.
3. Place the table in the turn-in file ex02\_<product prefix>\_dict.xxx (xxx is an extension).

### Exercise 03 — Building a Logical Data Model <div id="54"></div>

**For each task:**

1. Build an ER diagram — a logical data model.
2. Include your selected entities in the ER diagram, supporting directories and decoupling tables for M:M relationships.
3. Specify the multiplicity of relationships between entities in the ER diagram.
4. Describe with verbs the relationships between entities in the ER diagram.
5. Place the diagram in the turn-in файле ex03\_<product prefix>\_model.xxx (xxx is an extension).
