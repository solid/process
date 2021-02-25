# Solid Editors

Below is a listing of the Solid Editorial Team and their respective assignments. See [Reviewing Proposals](README.md#reviewing-proposals.md) for an explanation of how the editorial process is used to review and accept changes to Solid Specifications, the Solid Roadmap, and Supporting Documentation.

## Editorial Team

| Name      | WebID      |
| --------- | ---------- |
| [Tim Berners-Lee](https://github.com/timbl) | [WebID](https://www.w3.org/People/Berners-Lee/card#i) |
| [Justin Bingham](https://github.com/justinwb) | [WebID](https://justin.inrupt.net/profile/card#me) |
| [Dmitri Zagidulin](https://github.com/dmitrizagidulin) | [WebID](https://dz.solid.community/profile/card#me) |
| [Kjetil Kjernsmo](https://github.com/kjetilk) | [WebID](https://solid.kjernsmo.net/profile/card#me) |
| [Sarven Capadisli](https://github.com/csarven) | [WebID](https://csarven.ca/#i) |
| [Ruben Verborgh](https://github.com/RubenVerborgh) | [WebID](https://ruben.verborgh.org/profile/#me) |

## Editorial Assignments

Editorial assignments are broken into three sections; [Solid Specification](#solid-specification), [Solid Roadmap](#solid-roadmap), and [Supporting Documentation](#supporting-documentation).

### Solid Specification

The Solid Specification covers a broad range of topics, from resource access and decentralized authentication to data portability and querying. Consequently, it requires a group of individuals with a wide range of skillsets to provide thorough editorial review of proposals to extend or alter the specification.

Editorial assignments to the specification are by topic. A given editor may be assigned to one or more topics. Some topics may have dedicated primary documents, while other topics may occur throughout the specification.

-   [Resource Access](#resource-access)
-   [Identity](#identity)
-   [Authentication](#authentication)
-   [Authorization](#authorization)
-   [Events and Notifications](#events-and-notifications)
-   [Data Interoperability](#data-interoperability)
-   [Data Portability](#data-portability)
-   [Auditing](#auditing)
-   [Querying](#querying)
-   [Cryptography](#cryptography)
-   [Security](#security)

#### Resource Access
Pertaining to the access of resources in a data pod over a network via HTTP

__Assigned Editors:__ Sarven Capadisli, Kjetil Kjernsmo, Ruben Verborgh   
__Primary Documents:__  [solid/specification/resource-access](https://github.com/solid/specification/blob/master/main/resource-access.bs)

#### Identity
Pertaining to mechanisms that universally identify people or applications.  

__Assigned Editors:__  Dmitri Zagidulin, Sarven Capadisli
__Primary Documents:__

#### Authentication
Pertaining to mechanisms that authenticate a person or application for the purposes of accessing resources in a data pod.
__Assigned Editors:__  Justin Bingham, Dmitri Zagidulin
__Primary Documents:__ [Solid-OIDC](https://solid.github.io/authentication-panel/solid-oidc/), [solid/specification/webid-tls](https://github.com/solid/specification/tree/master/webid-tls)

#### Authorization
Pertaining to mechanisms that control the access a given agent has to read or manipulate resources in a data pod.
__Assigned Editors:__  Sarven Capadisli, Kjetil Kjernsmo, Dmitri Zagidulin
__Primary Documents:__ [solid/specification/resource-access](https://github.com/solid/specification/blob/master/main/resource-access.bs), [solid/specification/wac](https://github.com/solid/specification/tree/master/wac), [solid/web-access-control-spec](https://github.com/solid/web-access-control-spec)

#### Events and Notifications
Pertaining to mechanisms that process and/or emit events between pods and agents, or other pods.  
__Assigned Editors:__  Sarven Capadisli, Ruben Verborgh, Dmitri Zagidulin
__Primary Documents:__

#### Data Interoperability
Pertaining to mechanisms that ensure disparate applications or agents can safely and seamlessly read and write the data they need.  
__Assigned Editors:__ Kjetil Kjernsmo, Ruben Verborgh, Justin Bingham, Sarven Capadisli   
__Primary Documents:__

#### Data Portability
Pertaining to mechanisms that ensure the portability of data stored in a data pod such that it can be safely migrated between conformant Solid server implementations, as well as exported to other mediums.  
__Assigned Editors:__  Justin Bingham   
__Primary Documents:__

#### Data Models
Pertaining to core vocabularies and data shapes essential to a working ecosystem of data pods and applications.  
__Assigned Editors:__  Kjetil Kjernsmo, Justin Bingham, Sarven Capadisli   
__Primary Documents:__ [solid/vocab](https://github.com/solid/vocab)

#### Auditing
Pertaining to the mechanisms through which access and manipulation events of resources in a data pod are recorded and accessible.
__Assigned Editors:__  Dmitri Zagidulin
__Primary Documents:__

#### Querying
Pertaining to the mechanisms, such as SPARQL and TPF, through which a given agent can provide query parameters to a data pod and receive results satisfying the same.  
__Assigned Editors:__ Kjetil Kjernsmo, Ruben Verborgh   
__Primary Documents:__

#### Cryptography
Pertaining to the mechanisms through which cryptographic techniques are employed to provide data privacy, data integrity, and verifiable information.  
__Assigned Editors:__ Dmitri Zagidulin
__Primary Documents:__

#### Security
Pertaining to mechanisms used and considerations taken when securing a data pod, a conformant server implementation, and/or the immediate ecosystem around them.  
__Assigned Editors:__ Justin Bingham, Sarven Capadisli, Dmitri Zagidulin 
__Primary Documents:__ [solid/specification/security](https://github.com/solid/specification/blob/master/main/security.bs)
