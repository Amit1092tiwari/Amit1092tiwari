---
trigger: model_decision
description: "Guidelines and tool routing for the Enterprise Agentic Data Fabric & Lakehouse MCP Server."
---

# Agentic Data Fabric Routing & Tool Usage

When the user asks to query lakehouse tables, inspect schemas, analyze SQL execution plans, or audit storage compaction:
1. Use the `agentic-data-fabric` Model Context Protocol (MCP) server configured in `~/.gemini/config/mcp_config.json`.
2. Available Tools:
   - `lakehouse_inspect_schema`: Inspect columns, data types, and row count contracts.
   - `lakehouse_explain_query`: Check for sequential scans, partition pruning, and sargability.
   - `lakehouse_query_sandboxed`: Execute read-only analytical SQL (automatically capped at 100 rows).
   - `governor_audit_pipeline`: Audit small-file fragmentation index and CDC compaction urgency.
   - `governor_trigger_compaction`: Execute autonomous columnar bin-packing with pre/post checksum validation.
