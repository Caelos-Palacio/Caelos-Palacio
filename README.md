# Carlos Palacio

I build deterministic, verifiable tooling for AI coding agents: small tools that return measured results instead of model guesses, and that say "not validated" when they cannot know. Physics student, so I like claims that come with evidence.

*Español: construyo herramientas deterministas y verificables para agentes de IA; los repositorios están documentados en inglés y español.*

<a href="https://github.com/Caelos-Palacio/opus-studio"><img src="https://raw.githubusercontent.com/Caelos-Palacio/opus-studio/main/docs/media/demo.gif" width="640" alt="opus-studio: every frame is a pure function of time, seek(t)"></a>

<sub>Rendered with <a href="https://github.com/Caelos-Palacio/opus-studio">opus-studio</a>: every frame is a pure function of time. Each repository below has its own demo.</sub>

## What I build

**Agent safety and credentials**
- [agent-credential-broker](https://github.com/Caelos-Palacio/agent-credential-broker) - lets an agent perform authenticated actions without ever holding the API key or password (local encrypted vault, scoped tasks, quotas, metadata audit). Experimental, not independently audited.
- [enlace](https://github.com/Caelos-Palacio/enlace) - connects agents to applications by researching the interface first, then planning and executing exact operations (SDK, CLI, MCP). Experimental.

**Observability and sessions**
- [agent-observer](https://github.com/Caelos-Palacio/agent-observer) - provider-neutral local logging of agent metadata and evidence-based operational reviews.
- [pi-session-workspace](https://github.com/Caelos-Palacio/pi-session-workspace) - session navigation, checkpoints and a local mailbox inside the Pi terminal agent.
- [claude-agent-continuity](https://github.com/Caelos-Palacio/claude-agent-continuity) - keeps the work of a cut-off Claude Code subagent: safe WIP commits per git worktree, status, resume prompts and a hook.

**Deterministic guardrails**
- [rosetta-guards](https://github.com/Caelos-Palacio/rosetta-guards) - detects identifiers lost when an LLM compacts context, plus a controlled-vocabulary linter. No LLM, no dependencies.
- [realign](https://github.com/Caelos-Palacio/realign) - checks declared relationships between project files and repairs only derived text blocks, with verifiable evidence.

**3D and CAD for agents**
- [agentcad](https://github.com/Caelos-Palacio/agentcad) - deterministic checks for OpenSCAD/STL designs (interference, printability, spec-as-code). A digital result is never labelled physical.

**Programmatic motion graphics**
- [opus-studio](https://github.com/Caelos-Palacio/opus-studio) - code-driven film production engine for autonomous agents: pure `seek(t)` rendering, direction lint, fragment-based editing.

## Principles that repeat across the work

- **Deterministic.** Checks are plain code, so the same input gives the same answer and a gate can rely on it.
- **Provider-neutral.** No dependence on one model, agent framework, terminal or account.
- **Zero or minimal dependencies.** Standard library wherever possible.
- **Evidence over claims.** Limits are documented, unknowns are reported as unknown, and experimental status is stated up front.

## Stack

JavaScript / Node.js, Python, OpenSCAD, Linux, git, MCP.

## Contact

Open an issue or discussion on any of the repositories above.
