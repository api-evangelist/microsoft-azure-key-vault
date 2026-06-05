# Azure Key Vault (azure-key-vault)

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
