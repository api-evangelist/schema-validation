# Schema Validation

Schema validation is the practice of verifying that data structures conform to a defined schema, contract, or specification. In API development, schema validation ensures API requests and responses match declared OpenAPI, JSON Schema, AsyncAPI, or GraphQL specifications, enabling contract testing, governance, and runtime integrity.

Key tools include AJV, Hyperjump JSON Schema, Spectral, and Schemathesis, each addressing different validation contexts from CLI pipelines to runtime API testing.

## Tools

| Tool | Language | Use Case |
|---|---|---|
| [AJV](https://ajv.js.org/) | JavaScript | Fastest JS JSON Schema validator |
| [Hyperjump JSON Schema](https://json-schema.hyperjump.io/) | JavaScript | Standards-compliant validator with OpenAPI support |
| [Spectral](https://stoplight.io/open-source/spectral) | JavaScript | Rule-based API governance linting |
| [OpenAPI Schema Validator](https://github.com/seriousme/openapi-schema-validator) | JavaScript | OpenAPI spec validation |
| [Blaze](https://github.com/sourcemeta/blaze) | C++ | Ultra-high-performance JSON Schema validation |
| [AlterSchema](https://github.com/sourcemeta/alterschema) | JavaScript | JSON Schema version migration |

## Resources

- [JSON Schema Organization](https://json-schema.org/)
- [JSON Schema Learn](https://json-schema.org/learn)
- [JSON Schema GitHub](https://github.com/json-schema-org)
- [API Evangelist: Schema Tools](https://apievangelist.com/2026/01/12/exploring-what-schema-tools-are-available/)

## Artifacts

### JSON Schema

- [schema-validation-config-schema.json](json-schema/schema-validation-config-schema.json) — JSON Schema for schema validation pipeline configuration

### JSON Structure

- [schema-validation-config-structure.json](json-structure/schema-validation-config-structure.json) — Document structure for validation configuration

### JSON-LD

- [schema-validation-context.jsonld](json-ld/schema-validation-context.jsonld) — Linked data context for schema validation vocabulary

### Examples

- [schema-validation-ajv-example.json](examples/schema-validation-ajv-example.json) — AJV validation with valid and invalid inputs

### Vocabulary

- [schema-validation-vocabulary.yml](vocabulary/schema-validation-vocabulary.yml) — Domain vocabulary and taxonomy for schema validation

## Maintainers

**Kin Lane** — kin@apievangelist.com
