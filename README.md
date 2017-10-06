# BBC R&D Implementations for AMWA NMOS APIs

NMOS is a family name for specifications produced by the [Advanced Media Workflow Association][AMWA] related to networked media for professional applications. These include APIs for discovery and registration, connection management and network control in networked media systems.

BBC R&D has provided implementations to help with the development and promotion of the NMOS specs. These have been used as the reference for hands-on workshops held by AMWA's [Networked Media Incubator]. BBC is making some implementations open-source on GitHub:

Repo | Description
-----|------------
[nmos-discovery-registration-ri](https://github.com/bbc/nmos-discovery-registration-ri)  |  Reference implementation of NMOS [IS-04 Discovery and Registration Specification][IS-04]\*
[nmos-registration](https://github.com/bbc/nmos-registration)  | IS-04 Registration API
[nmos-query](https://github.com/bbc/nmos-query)  | IS-04 Query API
[nmos-node](https://github.com/bbc/nmos-node)  | IS-04 Node API
[nmos-device-connection-management-ri](https://github.com/bbc/nmos-device-connection-management-ri)  |  Reference implementation of NMOS [IS-05 Device Connection Management Specification][IS-04]
[nmos-common](https://github.com/bbc/nmos-common)  | Common code used for  NMOS implementations

\*Our NMOS repos are currently being refactored: currently nmos-discovery-registration-ri includes its own registration, query, node, mdns-bridge and common code. This will be removed in the future.

Currently these are all Python implementations, with Apache 2.0 licences. Further details are provided in the individual repositories.

[//]: # (References/Links)

[AMWA]: http://amwa.tv "Advanced Media Workflow Association"

[IS-04]: https://github.com/AMWA-TV/nmos-discovery-registration "IS-04"

[Networked Media Incubator]: http://nmos.tv/about_NMI.html "Networked Media Incubator"
