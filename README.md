# HL7_FHIR

Fast Helathcare Interopability Resources.

Goal to create a standard that is quick to understand and master.

FHIR has five components 
 - a robust data model for describing health and admin data
 - a RESTful API for interacting with the data using either JSON or XML
 - open source tools to implement and test FHIR applications
 - a network of servers across the globe that you can interact with.
 - collaborative community of implementers
 
 Has over 150 different resources used to describe almost anything related to health data.
 Each resource has a specific purpose - eg. patient resource contains items like hospital or family doc visits.
 
 FHIR resources are inherently readable and presented on a publicly accessible website.
 
 Not only resource navigation simple, but data types are alsow very flexible and allow for many diff use cases
 
 Narritives, are a type of resource that offers human readable versions of stuructured data, allowing non fhir experts to roughly interpret the clinical data for a 
 basic level o f interoperability
 
 What are resource identifiers? allow true semantic interoperability.
 
 FHIR performs a logical delete ( deleted = 1)
 
 Another feature is the search API, many search params are built into SMILE CDR HAPI FHIR.
 
 FHIR is extrememly loose so an implementation guide that constrains the FHIR spec for specific use can be put into action.
 There are 4 IGs that are present in the healthcare space.
 
 The US Core impl guide - used for national EMR implementation guides.
 International Patient Summary impl guide - bare minimum record offering a snapshot of someones health that could follow across borders.
 Carin Alliance impl - consumer access to their health data in US
 Gravity project impl - examines inequalities in our healthcare system. 
 HAPI FHIR implemention - such as smile CDR
 
 HAPI FHIR is licensed under the Apache Software lic 2.0
 
 
 
 For every org that implements FHIR standard, even if the data models are not the same - there is a similar base understanding and protocol.

http://hapi.fhir.org/baseR4/Patient/example
 
 
