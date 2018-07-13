taxii-openapi
-------------
![tds-logo](./resources/logo.png)

# Description

This repository contains a non-trivial [OpenAPI](https://www.openapis.org/) version 2.0 document describing the Taxii 
2.0 specification ([./swagger.yaml](./swagger.yaml)), which allows for developers to take advantage of the extensive 
tooling provided by the Swagger/OpenAPI ecosystem, just as:
- [swagger-codegen](https://github.com/swagger-api/swagger-codegen) to generate "full-featured" HTTP client libraries
    and server-side stubs in a wide variety of languages
- [swagger-ui](https://github.com/swagger-api/swagger-ui) for "automagically" generated HTML documentation for Taxii 2.0

More importantly, by using HTTP API contract tooling such as OpenAPI, the Taxii 2.0 specification can be ingested in a 
format that is the industry standard for documenting and describing HTTP APIs. 

# Todo

The OpenAPI document is missing terms of service as well as other information regarding the
Oasis [Cyber Threat Intelligence Technical Committee](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cti).

# Contributing

This OpenAPI document has been put together as a best-effort project, and pull requests are welcome. Feel free to open
issues, though we do ask that you be as verbose and specific as possible about what issues you're having.

# Attribution

This is a project by [Threat Data Science](https://www.threatdatascience.io) and relies heavily on the original Taxii 
2.0 specification document provided by the Oasis 
[Cyber Threat Intelligence Technical Committee](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cti), which 
can be found [here](https://oasis-open.github.io/cti-documentation/resources.html#taxii-20-specification).