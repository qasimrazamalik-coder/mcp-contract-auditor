# Contract

## Purpose
Tool manifests often hide dangerous permissions behind vague descriptions and unconstrained parameters.

## Input
JSON MCP manifest containing server name and tools with name, description, scopes, side_effect and parameters.

## Output
Machine-readable findings with severity, rule ID, affected tool and remediation.

## Failure behavior
Reject malformed JSON. Report missing or unsafe fields explicitly. Never invent evidence or authorization.
