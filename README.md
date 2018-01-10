# BBC R&D Implementations for AMWA NMOS APIs

NMOS is a family name for [specifications][NMOS] produced by the [Advanced Media Workflow Association][AMWA] related to networked media for professional applications. These include APIs for discovery and registration, connection management and network control in networked media systems.

BBC R&D has provided implementations to help with the development and promotion of the NMOS specs. These have been used as the reference for hands-on workshops held by AMWA's [Networked Media Incubator]. BBC is making some implementations open-source on GitHub:

Repo | Description
-----|------------
[nmos-joint-ri](https://github.com/bbc/nmos-joint-ri) | Reference implementation demonstrating both IS-04 and IS-05
[nmos-discovery-registration-ri](https://github.com/bbc/nmos-discovery-registration-ri)  |  Reference implementation of NMOS [IS-04 Discovery and Registration Specification][IS-04]
[nmos-registration](https://github.com/bbc/nmos-registration)  | IS-04 Registration API
[nmos-query](https://github.com/bbc/nmos-query)  | IS-04 Query API
[nmos-node](https://github.com/bbc/nmos-node)  | IS-04 Node API
[nmos-device-connection-management-ri](https://github.com/bbc/nmos-device-connection-management-ri)  |  Reference implementation of NMOS [IS-05 Device Connection Management Specification][IS-05]
[nmos-cm-automated-testing](https://github.com/bbc/nmos-cm-automated-testing) | Automated testing suite for IS-05 implementations
[nmos-common](https://github.com/bbc/nmos-common)  | Common code used for  NMOS implementations
[nmos-mdns-bridge](https://github.com/bbc/nmos-mdns-bridge) | Zeroconf/mDNS bridge for NMOS service types
[nmos-reverse-proxy](https://github.com/bbc/nmos-reverse-proxy) | Reverse proxy used for NMOS implementations

Currently these are all Python implementations, with Apache 2.0 licences. Further details are provided in the individual repositories.

[//]: # (References/Links)

[AMWA]: http://amwa.tv "Advanced Media Workflow Association"

[IS-04]: https://github.com/AMWA-TV/nmos-discovery-registration "IS-04"

[IS-05]: https://github.com/AMWA-TV/nmos-device-connection-management "IS-05"

[Networked Media Incubator]: http://nmos.tv/about_NMI.html "Networked Media Incubator"

[NMOS]: https://github.com/AMWA-TV/nmos "NMOS overview GitHub"
