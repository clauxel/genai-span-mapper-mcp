# GenAI Span Mapper MCP

Normalize GenAI spans before dashboards tell competing stories.

Paid remote MCP for OpenTelemetry GenAI span mapping, provider normalization, missing attribute detection, dashboard schemas, and mapping receipts.

## Public Endpoints

- Website: https://genaispanmapper.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://genaispanmapper.clauxel.com/mcp
- Server card: https://genaispanmapper.clauxel.com/server-card.json
- Registry name: `com.clauxel.genaispanmapper/genaispanmapper-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `map_genai_span_fields`
- `normalize_provider_attributes`
- `detect_missing_genai_attributes`
- `issue_mapping_receipt`
- `export_observability_schema`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://genaispanmapper.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://genaispanmapper.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://genaispanmapper.clauxel.com/server-card.json
- MCP endpoint: https://genaispanmapper.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
