# CUDO Compute (cudo-compute)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
