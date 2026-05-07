# Command Centre

![Command Centre](../assets/screenshots/command-centre.png)

The Command Centre is the operator surface for Agentarium. It is the first screen a developer should keep open while agent teams are running.

It answers five questions quickly:

1. Which worlds are active?
2. Which agents are working?
3. Which runtime is powering them?
4. What did they produce?
5. Where does a human need to step in?

## What The Page Is For

The Command Centre turns invisible background runs into an operating loop. Instead of asking a developer to scan logs, it shows rooms, agents, handoffs, sessions, runtime health, and artifacts in one visual surface.

## Main Sections

| Section | Purpose |
|---|---|
| Status rail | Shows high-attention items and operator signals. |
| Command loop | Shows the live operating model: worlds, voice, handoffs, and intervention. |
| Metrics row | Shows active agents, connected runtimes, live sessions, and logged artifacts. |
| Session feed | Shows current and recent run activity. |
| Runtime panel | Shows health and readiness for connected runtimes. |
| Active rooms | Opens private rooms and flagship worlds. |
| Agent roster | Shows who is active and where each agent is working. |
| Artifact timeline | Tracks what the agents produced. |

## Operator Flow

1. Open Command Centre.
2. Check active rooms and runtime state.
3. Open a session when work is live.
4. Enter the world if spatial context matters.
5. Use voice or intervention controls when the agent team needs a human.
6. Review artifacts and session history after the run.

## Product Screenshots

The public docs use real app stills that show the current Command Centre surfaces clearly.

### Runtime Room Overview

![Command Centre aerial](../assets/screenshots/command-centre-aerial.png)

### Run Board

![Command Centre run board](../assets/screenshots/command-centre-run-board.png)

### Log Trench

![Command Centre log trench](../assets/screenshots/command-centre-log-trench.png)

### Escalation Lane

![Command Centre escalation](../assets/screenshots/command-centre-escalation.png)

### Voice Row

![Command Centre voice row](../assets/screenshots/command-centre-voice-row.png)

## Design Principle

The Command Centre should feel like a control room, not a spreadsheet. Counts should be honest, live rooms should not show fake data, and every visible control should either lead to a real product surface or clearly describe what is coming next.
