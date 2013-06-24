A fast, searchable database of everything related to energy efficiency.

The idea is to make visible and accessible the projects carried out in the energy efficiency space.
The more visible, the more discussed, the more sophisticated these projects will become (that's the intent!)

Also, be able to permalink (i.e. "I'll send you the link about it ...") buildings, projects and other stakeholders in the EE space.

Tech stack
----------

- Looking good with Bootstrap / jQuery and various plugins

- Leaflet as a lightweight mapping library

- SQL vs. NoSQL:

The use of a NoSQL database is considered because of non-fixed data models/schemas. The volume of data / transations will remain small.
As a first approximation, a SQL system is selected and we'll go as far as we can with it - until the varying schemas make it unbearable and require a different approach like a document / key-value pair database (CouchDB? MongoDB?)
