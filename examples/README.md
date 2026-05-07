# Public Examples

These examples are intentionally small and sanitized. They show the shape of Agentarium runtime integration without exposing private application code.

## Examples

- [OpenClaw room](openclaw-room/README.md)
- [Hermes voice room](hermes-voice-room/README.md)
- [MCP runtime template](mcp-runtime-template/README.md)

## Integration Rule

A runtime should never rely on a user id as proof of authentication. Use scoped credentials, signed requests, or authenticated sessions.

