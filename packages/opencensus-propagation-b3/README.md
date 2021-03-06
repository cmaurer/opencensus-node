# OpenCensus B3 Format Propagation for Node.js
[![Gitter chat][gitter-image]][gitter-url]

OpenCensus B3 Format Propagation sends a span context on the wire in an HTTP request, allowing other services to create spans with the right context.

This project is still at an early stage of development. It's subject to change.

Note: This code was tested on the following Node versions:
- v6.10.0 (for console exporter only)
- v9.8.0 (for Stackdriver and Zipkin exporters)


## Useful links
- To know more about B3 Format propagation, visit: <https://github.com/openzipkin/b3-propagation>
- For more information on OpenCensus, visit: <https://opencensus.io/>
- To checkout the OpenCensus for Node.js, visit: <https://github.com/census-instrumentation/opencensus-node>
- For help or feedback on this project, join us on [gitter](https://gitter.im/census-instrumentation/Lobby)

[gitter-image]: https://badges.gitter.im/census-instrumentation/lobby.svg
[gitter-url]: https://gitter.im/census-instrumentation/lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
