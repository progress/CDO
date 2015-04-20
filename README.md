
Cloud Data Object (CDO)
===========

Cloud Data Object (CDO) is a protocol definition and and client-side data management API to manage complex business transactions when working in an n-tier application architecture. The protocol involves a client and a server and it is language agnostic.

The CDO protocol and API are cross-platform friendly and can be layered on existing standards-based technologies. The CDO  functionality extends business application client communication past simple CRUD (create, read, update, delete) with transactional data synchronization and business logic invocation, something that many protocols claim but do little to help actually manage synchronization across device boundaries. This makes CDO a compelling protocol for integrating new clients and services into existing business solutions.

The original implementation by Progress®, the JSDO, involved a JavaScript client running on a browser against a Progress OpenEdge® server. Other implementations include a client in a mobile Hybrid App (a variation of the browser client), a Telerik® NativeScript client, a Node.js server, and a Java server. The JSDO has successfully been used with servers other than OpenEdge such as Node.js to export data created / aggregated in Modulus™ to a Progress® Rollbase Application.
The CDO is a multi-purpose definition that supports data management between any client and any server. The CDO specification supports a complex data model and API to manipulate data while maintaining data integrity with the server. Data synchronization of related records is a fundamental requirement of business applications and is fully supported in the CDO. Data transaction and business logic support is realized through invoke and submit operations. Submit sends multiple data changes to the server and manages record-level errors returned from the server. Invoke is used to pass data and recieve data from critical business logic on the server. 

The CDO catalog defines the logical schema and operation mapping to the remote data source. The catalog maps simple Create, Read, Update and Delete (CRUD) operations in a RESTful style. Submit and Invoke methods utilize an extension to the typical RESTful API.

The CDO Session manages and simplifies the connection to a remote server. A CDO Session establishes and maintains session context with a server so that the user only needs to provide their credentials once. The Session also hides all the complexity of the communicating with a server. 

The CDO is purposed for business applications in the cloud that require complex data transaction management and access to business logic and validation on the server. Cloud business applications without the CDO are limited to simple data management one record at a time. 

* Getting Started: [Getting Started](#gettingstarted)
* Documentation: ([CDO Catalog Definition](http://progress.github.io/docs/cdo/Overview/catalog.html)) ([CDO API](http://progress.github.io/docs/cdo/api.html))
* Website and blog: ([progress.com](http://progress.github.io/cdo/index.html))  ([Blog](http://progress.github.io/cdo/blog.html))
* CDO BSD License: [License](#license)
* 


Getting More Information
========================

* [contact us](https://www.progress.com/)




Samples using the CDO in JavaScript
-----------------------------

The JavaScript Data Object (JSDO) is a sample implementation of the Cloud Data Object Specification V4.0
ResearchKit [`ORKCatalog`](samples/ORKCatalog) sample app is a
good place to start. Find the project in ResearchKit's
[`samples`](samples) directory. This project includes a list of all
the types of steps supported by the ResearchKit framework in one tab, and displays a
browser for the results of the last completed task in the other tab.



License<a name="license"></a>
=======

The source in the Cloud Data Object repository is made available under the
following license unless another license is explicitly identified:

``` (UPDATE NECESSARY)
Copyright (c) 2015, Apple Inc. All rights reserved.
 
Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:
 
1.  Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.
 
2.  Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation and/or
other materials provided with the distribution.
 
3. Neither the name of the copyright holder(s) nor the names of any contributors
may be used to endorse or promote products derived from this software without
specific prior written permission. No license is granted to the trademarks of
the copyright holders even if such marks are included in this software.
 
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
