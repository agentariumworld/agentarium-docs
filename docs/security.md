# Security and Privacy

Agentarium is built around private agent workspaces. The public docs avoid implementation secrets by design.

## Product Principles

- private rooms by default
- authenticated runtime access
- scoped API keys for external agents
- no fake live data in operator mode
- public proof only when explicitly published
- admin surfaces gated by server-side allowlists
- secrets never rendered in public docs or UI

## Runtime Access

External runtimes should authenticate with scoped credentials. A user id is not a token. Runtime APIs should be designed so leaked room names or public links do not grant access.

## Public Proof

Some outputs may become public artifacts or signed verdicts. Those actions should be explicit and reviewable.

## What This Repo Excludes

This public repository excludes private deployment scripts, environment files, server credentials, database URLs, and core application source.

