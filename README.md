# Azure Key Vault (azure-key-vault)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Azure Key Vault is a cloud service for securely storing and accessing secrets, keys, and certificates. It helps safeguard cryptographic keys and secrets used by cloud applications and services.

**APIs.json:** [https://azure.microsoft.com/en-us/services/key-vault/](https://azure.microsoft.com/en-us/services/key-vault/)

## Tags

- Certificates
- Cloud Security
- Cryptography
- Key Management
- Secrets Management
- Security

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Azure Key Vault API

REST API for managing vaults, keys, secrets, and certificates in Azure Key Vault.

- **Human URL:** [https://azure.microsoft.com/en-us/services/key-vault/](https://azure.microsoft.com/en-us/services/key-vault/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Certificates
- Keys
- Secrets
- Vaults

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/key-vault/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/resource-manager/Microsoft.KeyVault/stable/2023-02-01/keyvault.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/key-vault/)
- [Getting Started](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)
- [Authentication](https://docs.microsoft.com/en-us/azure/key-vault/general/authentication)
- [Best Practices](https://docs.microsoft.com/en-us/azure/key-vault/general/best-practices)
- [Security](https://learn.microsoft.com/en-us/azure/key-vault/general/secure-key-vault)
- [Postman Collection](collections/azure-key-vault-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-key-vault-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Key Vault Data Plane API

API for performing cryptographic operations and managing keys, secrets, and certificates within a specific Key Vault instance.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/keyvault/](https://docs.microsoft.com/en-us/rest/api/keyvault/)
- **Base URL:** `https://{vault-name}.vault.azure.net`

#### Tags

- Certificate Operations
- Cryptographic Operations
- Key Operations
- Secret Operations

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/keyvault/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/data-plane/Microsoft.KeyVault/stable/7.4/keyvault.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-key-vault-data-plane-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-key-vault-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-key-vault-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://docs.microsoft.com/en-us/rest/api/keyvault/keys)
- [JSON Schema](json-schema/azure-key-vault-secret-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-create-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-list-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-operation-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-operations-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-sign-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-update-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-verify-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-verify-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-properties-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-release-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-json-web-key-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-json-web-key-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-json-web-key-operation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-json-web-key-curve-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-set-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-update-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-list-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-properties-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-secret-restore-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-backup-secret-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-create-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-import-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-update-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-list-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-operation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-certificate-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-issuer-parameters-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-lifetime-action-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-subject-alternative-names-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-x509-certificate-properties-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-deleted-key-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-deleted-secret-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-deleted-certificate-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-deletion-recovery-level-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-key-vault-data-plane-key-vault-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-key-vault-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/azure-key-vault-data-plane-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [SDK](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/security.keyvault.keys-readme)
- [SDK](https://learn.microsoft.com/en-us/python/api/overview/azure/keyvault-keys-readme)
- [SDK](https://learn.microsoft.com/en-us/java/api/overview/azure/security-keyvault-keys-readme)
- [SDK](https://learn.microsoft.com/en-us/javascript/api/overview/azure/keyvault-keys-readme)

### Azure Key Vault Keys API

REST API for creating, importing, updating, and performing cryptographic operations with keys in Azure Key Vault. Supports RSA, EC, and symmetric key types with operations including encrypt, decrypt, sign, verify, wrap, and unwrap.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/keys](https://learn.microsoft.com/en-us/rest/api/keyvault/keys)
- **Base URL:** `https://{vault-name}.vault.azure.net`

#### Tags

- Cryptographic Operations
- Encryption
- HSM
- Keys
- Signing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/keys/about-keys)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/keyvault/keys)
- [Getting Started](https://learn.microsoft.com/en-us/azure/key-vault/keys/quick-create-net)
- [Postman Collection](collections/azure-key-vault-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-key-vault-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Key Vault Secrets API

REST API for securely storing and managing secrets such as passwords, connection strings, and API keys in Azure Key Vault.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/secrets](https://learn.microsoft.com/en-us/rest/api/keyvault/secrets)
- **Base URL:** `https://{vault-name}.vault.azure.net`

#### Tags

- Connection Strings
- Passwords
- Secrets
- Secure Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/secrets/about-secrets)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/keyvault/secrets)
- [Getting Started](https://learn.microsoft.com/en-us/azure/key-vault/secrets/quick-create-net)
- [Postman Collection](collections/azure-key-vault-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-key-vault-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Key Vault Certificates API

REST API for creating, importing, managing, and renewing certificates in Azure Key Vault.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/certificates](https://learn.microsoft.com/en-us/rest/api/keyvault/certificates)
- **Base URL:** `https://{vault-name}.vault.azure.net`

#### Tags

- Certificate Authorities
- Certificate Management
- Certificates
- SSL
- TLS

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/certificates/about-certificates)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/keyvault/certificates)
- [Getting Started](https://learn.microsoft.com/en-us/azure/key-vault/certificates/quick-create-net)
- [Postman Collection](collections/azure-key-vault-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-key-vault-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Status Page](https://status.azure.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Changelog](https://docs.microsoft.com/en-us/azure/key-vault/general/whats-new)
- [Portal](https://portal.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/key-vault/)
- [Spectral Rules](rules/azure-key-vault-spectral-rules.yml)
- [Vocabulary](vocabulary/azure-key-vault-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
