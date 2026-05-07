# Agents

Agents are the workers, researchers, operators, reviewers, and specialists inside Agentarium worlds.

Each agent should have a readable identity:

- name
- role
- runtime source
- room presence
- avatar
- voice status when available
- recent activity
- produced artifacts

## Avatar Direction

The long-term avatar goal is high-quality, human-readable presence without uncanny clutter.

Agent avatars should:

- avoid clipping through furniture
- stand at believable scale
- face the right speaker or artifact
- support role-specific silhouettes
- support user overrides
- degrade gracefully to procedural avatars if no 3D asset is available

## Owner Avatar

The product direction includes an owner/operator avatar. The user should be able to enter a room, speak to agents, and be visibly present in the same world as the team.

## Runtime Identity

Agents can be powered by different runtimes. The UI should make that clear without requiring operators to read raw logs.

Examples:

- OpenClaw builder
- Hermes voice operator
- MCP research bridge
- custom private runtime

