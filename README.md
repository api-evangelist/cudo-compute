# CUDO Compute (cudo-compute)

CUDO Compute is a global GPU and cloud compute platform and marketplace that provisions on-demand and reserved virtual machines, bare metal, and multi-node GPU clusters across a distributed network of data centers. Its versioned, resource-oriented REST API (with a parallel gRPC surface) lets developers create and manage virtual machines, machine types, data centers, disks, networks, images, SSH keys, object storage, and billing programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cudo-compute/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cudo-compute/refs/heads/main/apis.yml)

## Tags

- GPU
- Cloud Compute
- Infrastructure
- Virtual Machines
- Marketplace

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### CUDO Compute Virtual Machines API

Create, list, start, stop, reboot, resize, terminate, and monitor CPU- and GPU-backed virtual machines in a project, including boot disks, NICs, security groups, metadata, expiry, and password retrieval.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Virtual Machines
- Compute
- GPU

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [API Reference](https://www.cudocompute.com/docs/rest-api/introduction)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Machine Types API

Lists available machine types, GPU models, and per-data-center machine-type prices and live utilization used to size virtual machines.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Machine Types
- GPU Models
- Catalog

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Data Centers API

Lists data centers and regions, host counts, clusters, commitment schedules, and utilization across the CUDO global compute network.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Data Centers
- Regions
- Capacity

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Disks & Storage API

Create, list, attach, detach, revert, and delete storage disks, plus create and delete disk snapshots, and manage object storage buckets and users.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Disks
- Storage
- Snapshots

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Networks API

Create, list, start, stop, and delete project networks, and manage security groups that control inbound and outbound traffic to virtual machines.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Networks
- Security Groups
- VPC

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Images API

List public boot images and create, list, update, and delete private VM images used to provision virtual machines.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Images
- Boot Images
- Snapshots

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute SSH Keys API

Create, list, get, and delete account SSH keys and list the SSH keys available to a project for injection into virtual machines.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- SSH Keys
- Access
- Security

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CUDO Compute Billing API

Create and manage billing accounts, payment methods, credit, invoices and outstanding balances, spend details, and credit-balance transactions.

- **Human URL:** [https://www.cudocompute.com/docs/api](https://www.cudocompute.com/docs/api)
- **Base URL:** `https://rest.compute.cudo.org`

#### Tags

- Billing
- FinOps
- Invoices

#### Properties

- [Documentation](https://www.cudocompute.com/docs/api)
- [OpenAPI](openapi/cudo-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cudo-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cudo-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CudoVentures)
- [LinkedIn](https://www.linkedin.com/company/cudo-ventures)
- [Website](https://www.cudocompute.com)
- [Documentation](https://www.cudocompute.com/docs/api)
- [Plans](plans/cudo-compute-plans-pricing.yml)
- [Rate Limits](rate-limits/cudo-compute-rate-limits.yml)
- [Fin Ops](finops/cudo-compute-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
