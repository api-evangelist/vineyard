# Vineyard (vineyard)

Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyard enables seamless object sharing between computation engines through a metadata-payload separation architecture, supporting Python, C++, Rust, and Go clients. The Vineyard Operator provides Kubernetes-native deployment with CRDs for managing clusters, sidecars, backups, and data operations.

**APIs.json:** [https://v6d.io/](https://v6d.io/)

## Scope

- **Type:** Index

## Tags

- Big Data
- CNCF
- Cloud Native
- Data Engineering
- Distributed Systems
- In-Memory Storage
- Kubernetes
- Machine Learning
- Metadata Management
- Python
- Zero-Copy

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### Vineyard Python Client API

The Vineyard Python client API provides programmatic access to the Vineyard in-memory data manager. It supports IPC (UNIX domain socket) and RPC (TCP) connections for storing, retrieving, and managing distributed in-memory objects. Key operations include put, get, delete, persist, and metadata inspection.

- **Human URL:** [https://v6d.io/notes/references/python-api.html](https://v6d.io/notes/references/python-api.html)

#### Tags

- Python
- Client
- In-Memory Storage
- Distributed Systems

#### Properties

- [OpenAPI](openapi/vineyard-python-client-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vineyard-python-client.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vineyard-python-client.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://v6d.io/notes/references/python-api.html)
- [Getting Started](https://v6d.io/notes/getting-started.html)

### Vineyard Kubernetes Operator

The Vineyard Kubernetes Operator manages vineyard cluster lifecycle and orchestrates shared objects on Kubernetes. It defines CRDs including Vineyardd, Sidecar, GlobalObject, LocalObject, Backup, Recover, Operation, and CSIDriver for deploying and managing Vineyard in cloud-native environments.

- **Human URL:** [https://v6d.io/notes/cloud-native/vineyard-operator.html](https://v6d.io/notes/cloud-native/vineyard-operator.html)

#### Tags

- Kubernetes
- Operator
- Cloud Native
- CNCF

#### Properties

- [Documentation](https://v6d.io/notes/cloud-native/vineyard-operator.html)
- [Documentation](https://v6d.io/notes/references/crds.html)
- [Kubernetes C R D](crd/vineyardd-crd.yaml)
- [Kubernetes C R D](crd/localobject-crd.yaml)
- [Kubernetes C R D](crd/globalobject-crd.yaml)
- [Kubernetes C R D](crd/sidecar-crd.yaml)
- [Kubernetes C R D](crd/operation-crd.yaml)
- [Kubernetes C R D](crd/backup-crd.yaml)
- [Kubernetes C R D](crd/recover-crd.yaml)
- [Postman Collection](collections/vineyard-python-client.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vineyard-python-client.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vineyard-vines)
- [Website](https://v6d.io/)
- [Documentation](https://v6d.io/docs.html)
- [Git Hub Org](https://github.com/v6d-io)
- [Git Hub](https://github.com/v6d-io/v6d)
- [Getting Started](https://v6d.io/notes/getting-started.html)
- [JSON Schema](json-schema/vineyard-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/vineyard-metadata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vineyard-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/vineyard-vocabulary.yml)
- [Spectral Rules](rules/vineyard-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
