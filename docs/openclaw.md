# OpenClaw

OpenClaw is a target runtime for deploying agent teams into Agentarium rooms.

The public integration goal is simple:

1. OpenClaw runs the agent team.
2. Agentarium receives authenticated room events.
3. The Command Centre shows live state.
4. The world layer renders agents, handoffs, artifacts, and interventions.

## Expected Capabilities

- agent lifecycle events
- task state updates
- handoff and escalation signals
- room presence
- artifact metadata
- optional voice state
- replay checkpoints

## Example

See [the public OpenClaw room example](../examples/openclaw-room/README.md).

## Product Goal

OpenClaw should feel like a raid team you can watch work. Developers should see who is active, where the handoff is, what stalled, and when to step in.

