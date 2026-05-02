# Rockwell Collins

Rockwell Collins was a major American company providing avionics and information technology systems and services to government agencies and aircraft manufacturers. In 2018, Rockwell Collins was acquired by United Technologies and became part of Collins Aerospace, a subsidiary of RTX Corporation (formerly Raytheon Technologies). Collins Aerospace provides flight deck systems, cabin electronics, mission systems, communications, and advanced data services including FlightAware AeroAPI for aviation data.

**Website:** [https://www.rtx.com/collinsaerospace/](https://www.rtx.com/collinsaerospace/)

**Developer Portal:** [https://developer.collins.com/api-products](https://developer.collins.com/api-products)

**Support:** [https://www.rtx.com/collinsaerospace/what-we-do/service-and-support/support/support-lookup](https://www.rtx.com/collinsaerospace/what-we-do/service-and-support/support/support-lookup)

## APIs

### FlightAware AeroAPI
FlightAware AeroAPI (formerly FlightXML) is a RESTful aviation data API acquired by Collins Aerospace in 2021. Provides real-time and historical flight tracking, airport information, operator fleet data, configurable alerts, and ML-based predictive ETAs (Foresight).

- **Documentation:** [https://www.flightaware.com/commercial/aeroapi/](https://www.flightaware.com/commercial/aeroapi/)
- **Portal:** [https://www.flightaware.com/aeroapi/portal](https://www.flightaware.com/aeroapi/portal)
- **OpenAPI:** [openapi/flightaware-aeroapi-openapi.yml](openapi/flightaware-aeroapi-openapi.yml)

### Collins Digital Exchange APIs
API products for aerospace integration via the Collins Digital Exchange developer portal.

- **Portal:** [https://developer.collins.com/api-products](https://developer.collins.com/api-products)

## Artifacts

### OpenAPI Specs
| File | Description |
|------|-------------|
| [openapi/flightaware-aeroapi-openapi.yml](openapi/flightaware-aeroapi-openapi.yml) | FlightAware AeroAPI v4.17.1 OpenAPI specification |

### Rules
| File | Description |
|------|-------------|
| [rules/rockwell-collins-rules.yml](rules/rockwell-collins-rules.yml) | Spectral ruleset enforcing AeroAPI conventions |

### Capabilities
| File | Description |
|------|-------------|
| [capabilities/flight-operations.yaml](capabilities/flight-operations.yaml) | Unified flight operations workflow capability |
| [capabilities/shared/aeroapi.yaml](capabilities/shared/aeroapi.yaml) | FlightAware AeroAPI shared capability definition |

### JSON Schema
| File | Description |
|------|-------------|
| [json-schema/rockwell-collins-flight-schema.json](json-schema/rockwell-collins-flight-schema.json) | AeroAPI flight data schema |

### JSON Structure
| File | Description |
|------|-------------|
| [json-structure/rockwell-collins-flight-structure.json](json-structure/rockwell-collins-flight-structure.json) | AeroAPI flight data structure documentation |

### JSON-LD
| File | Description |
|------|-------------|
| [json-ld/rockwell-collins-context.jsonld](json-ld/rockwell-collins-context.jsonld) | JSON-LD context for aviation data semantics |

### Examples
| File | Description |
|------|-------------|
| [examples/aeroapi-get-flight-example.json](examples/aeroapi-get-flight-example.json) | Get flight information example |

### Vocabulary
| File | Description |
|------|-------------|
| [vocabulary/rockwell-collins-vocabulary.yml](vocabulary/rockwell-collins-vocabulary.yml) | Collins Aerospace and AeroAPI domain vocabulary |

## Capabilities

### Flight Operations (`capabilities/flight-operations.yaml`)
Unified workflow for aviation flight operations monitoring and planning. Combines FlightAware AeroAPI to provide:
- Real-time flight search and tracking
- Airport information and delay monitoring
- Weather conditions
- Operator/airline fleet data
- Configurable flight event alerts

**REST Port:** 8080 | **MCP Port:** 9080 | **Tools:** 13

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
