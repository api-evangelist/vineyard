# Vineyard

Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows.

**Website:** https://v6d.io/  
**GitHub:** https://github.com/v6d-io/v6d  
**Documentation:** https://v6d.io/docs.html

## APIs

### Vineyard Python Client API

The Python client provides IPC (UNIX domain socket) and RPC (TCP) access to vineyard for storing, retrieving, and managing distributed in-memory objects.

- **OpenAPI Spec:** [openapi/vineyard-python-client-openapi.yml](openapi/vineyard-python-client-openapi.yml)
- **Documentation:** https://v6d.io/notes/references/python-api.html
- **Getting Started:** https://v6d.io/notes/getting-started.html

### Vineyard Kubernetes Operator

The Vineyard Operator manages vineyard cluster lifecycle on Kubernetes using CRDs.

- **Documentation:** https://v6d.io/notes/cloud-native/vineyard-operator.html
- **CRD Reference:** https://v6d.io/notes/references/crds.html

## Kubernetes CRDs

| CRD | File | Description |
|-----|------|-------------|
| Vineyardd | [crd/vineyardd-crd.yaml](crd/vineyardd-crd.yaml) | Deploy a vineyard cluster on Kubernetes |
| LocalObject | [crd/localobject-crd.yaml](crd/localobject-crd.yaml) | Local vineyard object metadata |
| GlobalObject | [crd/globalobject-crd.yaml](crd/globalobject-crd.yaml) | Cluster-wide distributed object metadata |
| Sidecar | [crd/sidecar-crd.yaml](crd/sidecar-crd.yaml) | Vineyard sidecar container configuration |
| Operation | [crd/operation-crd.yaml](crd/operation-crd.yaml) | Assembly and repartition operations |
| Backup | [crd/backup-crd.yaml](crd/backup-crd.yaml) | Backup vineyard objects to PersistentVolumes |
| Recover | [crd/recover-crd.yaml](crd/recover-crd.yaml) | Restore vineyard objects from backups |

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/vineyard-python-client.yaml](capabilities/shared/vineyard-python-client.yaml) | Per-API capability definition for the Python Client API |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/data-sharing-workflow.yaml](capabilities/data-sharing-workflow.yaml) | Data sharing and object lifecycle management for ML and data engineering workflows |

## JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/vineyard-object-schema.json](json-schema/vineyard-object-schema.json) | Schema for Vineyard in-memory objects |
| [json-schema/vineyard-metadata-schema.json](json-schema/vineyard-metadata-schema.json) | Schema for object metadata containers |

## JSON Structure

| File | Description |
|------|-------------|
| [json-structure/vineyard-object-structure.json](json-structure/vineyard-object-structure.json) | Structure documentation for Vineyard objects |

## JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/vineyard-context.jsonld](json-ld/vineyard-context.jsonld) | Linked data context mapping vineyard concepts to schema.org |

## Examples

| File | Description |
|------|-------------|
| [examples/vineyard-connect-to-server-example.json](examples/vineyard-connect-to-server-example.json) | Connect to vineyard server |
| [examples/vineyard-put-object-example.json](examples/vineyard-put-object-example.json) | Store an object in vineyard |
| [examples/vineyard-get-object-example.json](examples/vineyard-get-object-example.json) | Retrieve an object by ID |
| [examples/vineyard-get-object-metadata-example.json](examples/vineyard-get-object-metadata-example.json) | Inspect object metadata |
| [examples/vineyard-put-name-example.json](examples/vineyard-put-name-example.json) | Associate a name with an object |
| [examples/vineyard-get-by-name-example.json](examples/vineyard-get-by-name-example.json) | Resolve a name to an ObjectID |

## Rules

| File | Description |
|------|-------------|
| [rules/vineyard-rules.yml](rules/vineyard-rules.yml) | Spectral ruleset enforcing vineyard API conventions |

## Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/vineyard-vocabulary.yml](vocabulary/vineyard-vocabulary.yml) | Domain vocabulary for vineyard concepts |

## Tags

Big Data, CNCF, Cloud Native, Data Engineering, Distributed Systems, In-Memory Storage, Kubernetes, Machine Learning, Metadata Management, Python, Zero-Copy

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
