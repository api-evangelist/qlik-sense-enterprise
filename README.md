# Qlik Sense Enterprise (qlik-sense-enterprise)
Collection of APIs for Qlik Sense Enterprise, a modern analytics platform for business intelligence and data visualization.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/apis.yml)

## Tags:

 - Analytics, Business Intelligence, Data Visualization, Enterprise, REST API

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Qlik Sense Repository Service
Core REST API for managing Qlik Sense Enterprise resources including apps, streams, users, security rules, and all configuration available through the Qlik Management Console.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Introduction.htm](https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Introduction.htm)

#### Tags:

 - Management, Repository, Security

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Introduction.htm)
- [OpenAPI](openapi/qlik-sense-enterprise-repository-service-openapi.yml)
- [Authentication](https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Connect-API-Authenticate.htm)

### Qlik Sense Engine JSON API
WebSocket protocol API using JSON-RPC for interacting with the Qlik Associative Engine.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/EngineJSONAPI/Content/introduction.htm](https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/EngineJSONAPI/Content/introduction.htm)

#### Tags:

 - Engine, JSON-RPC, WebSocket

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/EngineJSONAPI/Content/introduction.htm)

### Qlik Sense Proxy Service
REST API for managing sessions, virtual proxies, and authentication in Qlik Sense Enterprise deployments.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/Subsystems/ProxyServiceAPI/Content/Sense_ProxyServiceAPI/ProxyServiceAPI-Introduction.htm](https://help.qlik.com/en-US/sense-developer/Subsystems/ProxyServiceAPI/Content/Sense_ProxyServiceAPI/ProxyServiceAPI-Introduction.htm)

#### Tags:

 - Proxy, Authentication, Sessions

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/Subsystems/ProxyServiceAPI/Content/Sense_ProxyServiceAPI/ProxyServiceAPI-Introduction.htm)
- [OpenAPI](openapi/qlik-sense-enterprise-proxy-service-openapi.yml)

### Qlik Sense About Service
Service that exposes metadata about the running Qlik Sense Enterprise deployment including versions and supported APIs.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/About-API/About-API-Introduction.htm](https://help.qlik.com/en-US/sense-developer/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/About-API/About-API-Introduction.htm)

#### Tags:

 - Metadata, Service

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/About-API/About-API-Introduction.htm)
- [OpenAPI](openapi/qlik-sense-enterprise-about-service-openapi.yml)

### Qlik Sense Data Connection
API for managing data connections and data sources.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html](https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html)

#### Tags:

 - Data Connections, Integration

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html)
- [OpenAPI](openapi/qlik-sense-enterprise-data-connection-openapi.yml)

### Qlik Sense Licenses
API for managing licenses, license allocations, and user access in Qlik Sense Enterprise.

**Human URL:** [https://help.qlik.com/en-US/sense-admin/Content/Sense_AdministerQSE/Licensing/Licensing.htm](https://help.qlik.com/en-US/sense-admin/Content/Sense_AdministerQSE/Licensing/Licensing.htm)

#### Tags:

 - Licensing, Allocation

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-admin/Content/Sense_AdministerQSE/Licensing/Licensing.htm)
- [OpenAPI](openapi/qlik-sense-enterprise-licenses-openapi.yml)

### Qlik Sense ODAG
On-Demand App Generation service API for orchestrating dynamic app generation against large data sources.

**Human URL:** [https://help.qlik.com/en-US/sense/Content/Sense_Helpsites/On-demand-apps.htm](https://help.qlik.com/en-US/sense/Content/Sense_Helpsites/On-demand-apps.htm)

#### Tags:

 - ODAG, On-Demand, Apps

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense/Content/Sense_Helpsites/On-demand-apps.htm)
- [OpenAPI](openapi/qlik-sense-enterprise-odag-service-openapi.yml)

### Qlik Sense Capabilities
High-level JavaScript API for embedding and extending Qlik Sense visualizations and mashups.

**Human URL:** [https://help.qlik.com/en-US/sense-developer/APIs/CapabilityAPIs/index.html](https://help.qlik.com/en-US/sense-developer/APIs/CapabilityAPIs/index.html)

#### Tags:

 - Visualization, Mashup, Embedding

#### Properties

- [Documentation](https://help.qlik.com/en-US/sense-developer/APIs/CapabilityAPIs/index.html)

## Artifacts

- [OpenAPI: Repository Service](openapi/qlik-sense-enterprise-repository-service-openapi.yml)
- [OpenAPI: Proxy Service](openapi/qlik-sense-enterprise-proxy-service-openapi.yml)
- [OpenAPI: About Service](openapi/qlik-sense-enterprise-about-service-openapi.yml)
- [OpenAPI: Data Connection](openapi/qlik-sense-enterprise-data-connection-openapi.yml)
- [OpenAPI: Licenses](openapi/qlik-sense-enterprise-licenses-openapi.yml)
- [OpenAPI: ODAG Service](openapi/qlik-sense-enterprise-odag-service-openapi.yml)
- [JSON Schema: App](json-schema/qlik-sense-enterprise-app-schema.json)
- [JSON Schema: Data Connection](json-schema/qlik-sense-enterprise-data-connection-schema.json)
- [JSON Schema: Reload Task](json-schema/qlik-sense-enterprise-reload-task-schema.json)
- [JSON Schema: Security Rule](json-schema/qlik-sense-enterprise-security-rule-schema.json)
- [JSON Schema: Session](json-schema/qlik-sense-enterprise-session-schema.json)
- [JSON Schema: Stream](json-schema/qlik-sense-enterprise-stream-schema.json)
- [JSON Schema: User](json-schema/qlik-sense-enterprise-user-schema.json)
- [JSON-LD Context](json-ld/qlik-sense-enterprise-context.jsonld)

## Common Properties

- [Portal](https://qlik.dev/)
- [Documentation](https://help.qlik.com/en-US/sense-developer/November2025/Content/Sense_Helpsites/APIs-and-SDKs.htm)
- [Authentication](https://qlik.dev/toolkits/qlik-api/authentication/)
- [Blog](https://www.qlik.com/blog)
- [Status](https://status.qlikcloud.com/)
- [Support](https://community.qlik.com/t5/Support/ct-p/qlikSupport)
- [Terms of Service](https://www.qlik.com/us/legal/terms-of-use)
- [Privacy Policy](https://www.qlik.com/us/legal/privacy)
- [GitHub](https://github.com/qlik-oss)
- [Community](https://community.qlik.com/)
- [Website](https://www.qlik.com/)
- [Login](https://qlikid.qlik.com/)
- [Sign Up](https://register.myqlik.qlik.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
