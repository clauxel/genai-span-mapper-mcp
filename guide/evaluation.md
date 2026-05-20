# Evaluation Guide

Use this page to evaluate whether GenAI Span Mapper MCP fits a real workflow.

## What To Test

- GenAI span mapping MCP
- OpenTelemetry GenAI attributes MCP
- LLM observability schema gate
- GenAI span JSON normalizer

## Expected Evidence

- Submit span samples, provider names, and field dictionaries.
- Map fields into OpenTelemetry GenAI attributes and dashboard schemas.
- Flag missing attributes and provider-version drift.
- Return normalized JSON and archive a mapping receipt.

## Risk Checks

- Do not publish production traces with customer data.
- Keep provider-specific samples minimal and anonymized.
- Validate schema changes against dashboards before rollout.

## Buyer Path

Default plan: Team.

Tracked checkout link:

- https://genaispanmapper.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=genaispanmapper_public_docs&utm_content=evaluation_checkout
