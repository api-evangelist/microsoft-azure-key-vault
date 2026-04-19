# Azure Key Vault (azure-key-vault)
Azure Key Vault is a cloud service for securely storing and accessing secrets, keys, and certificates. It helps safeguard cryptographic keys and secrets used by cloud applications and services.

**URL:** [Visit APIs.json URL](https://azure.microsoft.com/en-us/services/key-vault/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Certificates, Cloud Security, Cryptography, Key Management, Secrets Management, Security

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Azure Key Vault API
REST API for managing vaults, keys, secrets, and certificates in Azure Key Vault.

**Human URL:** [https://azure.microsoft.com/en-us/services/key-vault/](https://azure.microsoft.com/en-us/services/key-vault/)

#### Tags:

 - Certificates, Keys, Secrets, Vaults

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/key-vault/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/key-vault/)
- [GettingStarted](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)
- [Authentication](https://docs.microsoft.com/en-us/azure/key-vault/general/authentication)
- [BestPractices](https://docs.microsoft.com/en-us/azure/key-vault/general/best-practices)
- [Security](https://learn.microsoft.com/en-us/azure/key-vault/general/secure-key-vault)

### Azure Key Vault Data Plane API
API for performing cryptographic operations and managing keys, secrets, and certificates within a specific Key Vault instance.

**Human URL:** [https://docs.microsoft.com/en-us/rest/api/keyvault/](https://docs.microsoft.com/en-us/rest/api/keyvault/)

#### Tags:

 - Certificate Operations, Cryptographic Operations, Key Operations, Secret Operations

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/keyvault/)
- [OpenAPI](openapi/azure-key-vault-data-plane-openapi.yml)
- [APIReference](https://docs.microsoft.com/en-us/rest/api/keyvault/keys)
- [.NET SDK](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/security.keyvault.keys-readme)
- [Python SDK](https://learn.microsoft.com/en-us/python/api/overview/azure/keyvault-keys-readme)
- [Java SDK](https://learn.microsoft.com/en-us/java/api/overview/azure/security-keyvault-keys-readme)
- [JavaScript SDK](https://learn.microsoft.com/en-us/javascript/api/overview/azure/keyvault-keys-readme)

### Azure Key Vault Keys API
REST API for creating, importing, updating, and performing cryptographic operations with keys in Azure Key Vault.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/keys](https://learn.microsoft.com/en-us/rest/api/keyvault/keys)

#### Tags:

 - Cryptographic Operations, Encryption, HSM, Keys, Signing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/keys/about-keys)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/keyvault/keys)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/key-vault/keys/quick-create-net)

### Azure Key Vault Secrets API
REST API for securely storing and managing secrets such as passwords, connection strings, and API keys in Azure Key Vault.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/secrets](https://learn.microsoft.com/en-us/rest/api/keyvault/secrets)

#### Tags:

 - Connection Strings, Passwords, Secrets, Secure Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/secrets/about-secrets)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/keyvault/secrets)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/key-vault/secrets/quick-create-net)

### Azure Key Vault Certificates API
REST API for creating, importing, managing, and renewing certificates in Azure Key Vault.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/keyvault/certificates](https://learn.microsoft.com/en-us/rest/api/keyvault/certificates)

#### Tags:

 - Certificate Authorities, Certificate Management, Certificates, SSL, TLS

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/key-vault/certificates/about-certificates)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/keyvault/certificates)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/key-vault/certificates/quick-create-net)

## Common Properties

- [StatusPage](https://status.azure.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/)
- [TermsOfService](https://azure.microsoft.com/en-us/support/legal/)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [ChangeLog](https://docs.microsoft.com/en-us/azure/key-vault/general/whats-new)
- [Portal](https://portal.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/key-vault/)

## Features

| Name | Description |
|------|-------------|
| Key Management | Create, import, and manage cryptographic keys with support for RSA, EC, and symmetric key types. |
| Secrets Management | Securely store and control access to passwords, connection strings, API keys, and other secrets. |
| Certificate Lifecycle | Automate certificate creation, renewal, and management with certificate authority integration. |
| Cryptographic Operations | Perform encrypt, decrypt, sign, verify, wrap, and unwrap operations using managed keys. |
| HSM-Backed Keys | Use hardware security modules for FIPS 140-2 Level 2 validated key protection. |
| Soft Delete and Purge Protection | Recover accidentally deleted vaults, keys, secrets, and certificates with configurable retention. |

## Use Cases

| Name | Description |
|------|-------------|
| Application Secret Management | Centralize and secure application secrets with audited access and automatic rotation. |
| Data Encryption | Encrypt data at rest and in transit using customer-managed keys stored in Key Vault. |
| TLS Certificate Management | Automate TLS certificate provisioning and renewal for web applications and services. |
| Code and Document Signing | Sign code, documents, and artifacts using keys stored securely in Key Vault. |

## Integrations

| Name | Description |
|------|-------------|
| Azure App Service | Reference Key Vault secrets and certificates directly from App Service configuration. |
| Azure Kubernetes Service | Mount Key Vault secrets as volumes in AKS pods using the Secrets Store CSI Driver. |
| Azure DevOps | Use Key Vault secrets in CI/CD pipelines for secure deployment automation. |
| Azure Disk Encryption | Encrypt Azure VM disks using customer-managed keys stored in Key Vault. |
| Azure SQL Database | Enable Transparent Data Encryption with customer-managed keys from Key Vault. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Key Vault Data Plane OpenAPI](openapi/azure-key-vault-data-plane-openapi.yml)

### JSON Schema

- [Key Vault Secret Schema](json-schema/azure-key-vault-secret-schema.json)
- [Key Bundle Schema](json-schema/azure-key-vault-data-plane-key-bundle-schema.json)
- [Certificate Bundle Schema](json-schema/azure-key-vault-data-plane-certificate-bundle-schema.json)

### JSON-LD

- [Azure Key Vault Context](json-ld/azure-key-vault-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Key Vault Data Plane API](capabilities/shared/key-vault-data-plane.yaml) — 16 operations for key, secret, and certificate management with cryptographic operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Secrets and Keys](capabilities/secrets-and-keys.yaml) | Key Vault Data Plane | 16 | Security Engineer |

## Vocabulary

- [Azure Key Vault Vocabulary](vocabulary/azure-key-vault-vocabulary.yaml)

## Rules

- [Azure Key Vault Spectral Rules](rules/azure-key-vault-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
