Cloud Data Object (CDO)
===========

The Cloud Data Object (CDO) defines a specification to manage complex business transactions when working in an n-tier application architecture. The CDO specification includes a *Data Object* on the client, and a *Data Service Catalog* for a remote *Data Service*. The specification is language agnostic and is useful when the client and the server are implemented in different technologies. 

The Data Object and Data Catalog specifications are cross-platform and can be layered on existing standards-based technologies for the communication protocol. The Data Object extends business application client functionality past simple CRUD (create, read, update, delete) operations with support for transactional data synchronization and business logic invocation to help actually manage synchronization across device boundaries. This makes CDO a compelling specification for integrating new client apps into existing business solutions.

The reference implementation of CDO specification is a JavaScript client running in a web browser against a Progress OpenEdge® server. This was developed and is known as the by Progress® JSDO - JavaScript Data Object. The JSDO uses REST for communications between the client and a Progress OpenEdge data service. Other reference implementations include a client in a mobile Hybrid App (a variation of the browser client), a Telerik® NativeScript client, a Node.js server (acting as a client), and a Java server (again acting as a client). The JSDO has successfully been used with servers other than OpenEdge such as a Progress® Rollbase Application and to a Node.js server to export data created/aggregated in Modulus™.

The specifications in the Cloud Data Object repository is made available under the
Apache License Version 2.0
