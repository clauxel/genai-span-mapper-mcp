# GenAI Span Mapper MCP

Normalize GenAI spans before dashboards tell competing stories.

GenAI Span Mapper is a paid remote MCP schema mapper for OpenTelemetry GenAI spans, provider attributes, missing fields, dashboard schemas, and mapping receipts.

This is a public documentation project for GenAI Span Mapper MCP. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://genaispanmapper.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=genaispanmapper_public_docs&utm_content=readme_primary_home
- Pricing: https://genaispanmapper.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=genaispanmapper_public_docs&utm_content=readme_pricing
- Checkout: https://genaispanmapper.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=genaispanmapper_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://genaispanmapper.clauxel.com/mcp
- Server card: https://genaispanmapper.clauxel.com/server-card.json
- Registry name: `com.clauxel.genaispanmapper/genaispanmapper-mcp`
- Tools: `map_genai_span_fields`, `normalize_provider_attributes`, `detect_missing_genai_attributes`, `issue_mapping_receipt`, `export_observability_schema`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

observability teams, LLM platform teams, data engineers, and SREs.

## Capabilities

- span schema mapper
- provider rules
- missing attribute detection
- normalized JSON
- dashboard schema export

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
