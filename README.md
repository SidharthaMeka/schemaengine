# SchemaEngine
SchemaEngine is a platform that could be used to build and deploy  scalable social / commerce / enterprise applications without having to write any code.

## Motivation
Instead of spending months coding a concept, we are able to deploy web-scale applications in a matter of days and weeks.

## Description
SchemaEngine is an  application platform as a service (aPaaS) framework to configure and launch enterprise and web-scale applications without any coding.

The codeless application configuration platform used to launch SaaS applications without having to write any code. 

* The business objects are modelled in JSON schemas that may be modified at runtime. 
* Most data types including structs and arrays may be defined. The data types may be flagged for search indexing and filtering of records. 
* The inter-relationships between the schema objects are modelled as 1-many, many-to-many, or 1-1 relationships. 
* View and results-set caching may be enabled to ensure under 10ms response time.
* These may be modified at run-time that allows the application’s behaviour to be updated without a restart.
* The application screens are also configured as a set of JSON templates that are interpreted at run-time allowing for a highly dynamic user-interface generation.

## Tech / Frameworks used
It is built using facebook's ReactJS,  Couchbase NoSQL cluster and elasticsearch

## Features / Capabilities
* Configure object / schema model and generate UI using a drag and drop interface.
* Responsive web, native iOS and Android
* Authentication 
* Multi-Org Authorizations 
* Roles & Workflows
* Notifications, messaging, 
* Integration with Quickbooks cloud accounting, payment processing gateways 
* CDN based delivery of rich media
* Mapping and geo-representation of information
* SEO ready with schema.org micro tagging ability.
* Integration with facebook’s Chatbot, Mixpanel and many more 

## Installation
Series of steps on how to get the development env running
Coming soon..

## How to Use?
Step by step guide to use the project

### Setup Schema
Create property fields
Select from one of the data-types
Number
Text
Date
Phone number
Attachement 
Ratings
Setup formula fields to enable default values assignment
and many more.

Setup additional attributes such as "Prompt-Text" and display style
Enable share and like system functions
Enable SEO on the property

Define the schema objects as AbstractObject /  DerivedObject
Derived Objects inherit properties from the base class Abstact Object

### Setup schema methods
Setup get / set methods on a property or a group of properties
Methods / functions will be specified at the schema level.

Methods will be specified as part of the CRUD set.
The properties and relations that may be created, read, updated or deleted will be mentioned as part of the method itself.

Record level security (for update, read & delete methods) will be defined at the record level.

### Setup Schema Relationships
Remote object lookups
1-1 relationship
1-many relationship
many-many relationships, setup junction records

Setup default value assignment


### Define schema view type
Gallery view (Pinterest style)
Calendar view for dates
Post-casd view
Blog page view
and many more

### Authorizations - System roles and security
Assign schema methods to specific roles and mention properties that each role should have access to.

Levels of security
Record level security
Org level security
Role level security
User level security
Domain level access, User level content (all schema records) is public unless otherwise specified

### Setup state transition definitions
Setup schema states that define the lifecycle of the business object.
Eg. A purchase order object will migrate within the following states:
CREATED / DRAFT
SENT FOR APPROVAL
PENDING APPROVAL
APPROVED
REJECTED
AWATING VENDOR PICKUP
and many more

### Setup External Integrations, via trigger definition configured in JSON
Available out-of-the-box
-Quickbooks, pass accounting entries
-Mailgun, outbound emailing
-eXotel, phone calling and SMS
and many more

### Setup Master data via mass data ingestion
Import master data / create records from xls


## Support
Email support@cloudseed.io

## Roadmap
1. Replatform to Redux for application state management
2. Upgrade React and Boostrap libraries
3. Integrate with a charting framework

## License
Apache 2.0
