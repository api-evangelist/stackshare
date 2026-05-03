# StackShare

StackShare is a platform where developers and companies share information about the technologies and tools they use to build software. It aggregates tech stack data from over 1.5 million companies and provides a GraphQL API for programmatic access to tool and company stack data.

**Website:** [https://stackshare.io/](https://stackshare.io/)
**Documentation:** [https://docs.stackshare.io/](https://docs.stackshare.io/)
**GitHub:** [https://github.com/stackshare](https://github.com/stackshare)

## Tags

- Developer Tools, Software Discovery, Tech Stacks

## APIs

### StackShare GraphQL API
Single GraphQL endpoint at `https://api.stackshare.io/graphql`. Authentication via API key query parameter. Exposes Leads, Enrichment, Tools, and Search queries.

- **Endpoint:** `https://api.stackshare.io/graphql`
- **Method:** POST
- **Authentication:** API key via `api_key` query parameter
- **Docs:** [https://docs.stackshare.io/](https://docs.stackshare.io/)

Note: StackShare exposes only a GraphQL API, not a REST API, so no OpenAPI spec is applicable.

## JSON Schema

| Schema | Path |
|---|---|
| Tool | [json-schema/stackshare-tool-schema.json](json-schema/stackshare-tool-schema.json) |
| Company | [json-schema/stackshare-company-schema.json](json-schema/stackshare-company-schema.json) |

## JSON Structure

| Structure | Path |
|---|---|
| Tool | [json-structure/stackshare-tool-structure.json](json-structure/stackshare-tool-structure.json) |

## JSON-LD

| Context | Path |
|---|---|
| StackShare Context | [json-ld/stackshare-context.jsonld](json-ld/stackshare-context.jsonld) |

## Examples

| Example | Path |
|---|---|
| Tech Stack Enrichment | [examples/stackshare-enrichment-example.json](examples/stackshare-enrichment-example.json) |

## Vocabulary

| Vocabulary | Path |
|---|---|
| StackShare Vocabulary | [vocabulary/stackshare-vocabulary.yml](vocabulary/stackshare-vocabulary.yml) |

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-02
