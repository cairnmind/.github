# Cairnmind

### Project memory for AI coding agents

**Decisions with evidence, plans with checks, and context that survives between sessions.**

Cairnmind runs next to the coding agents you already use (Claude Code, Codex and others, through MCP). It keeps what a project has decided and why, gives each new session the context it needs, and does not call a task done because an agent said so: a status follows from a check run, a recorded acceptance or a person.

It starts on one developer's laptop. The same core is meant to grow into a shared project database for a team, and from there into views for the people who lead teams and departments, without moving to a different product.

---

## Where it stands

| Stage | Who it is for | State |
| :--- | :--- | :--- |
| **Local** | One developer, several agents, several repositories | Available: [cairnmind](https://github.com/piotrwozn/cairnmind) |
| **Shared database** | The same project memory on a server, models local or remote | In progress |
| **Team** | Several developers on one project: identity, authorship, conflicts | Planned for 1.0 |
| **Views above a team** | Team leads, department heads, company: what each project is for, what is already solved elsewhere, what could come next | Direction after 1.0 |

What is being built now: [roadmap](https://github.com/users/piotrwozn/projects/1). Where it is meant to go: [features after 1.0](https://github.com/users/piotrwozn/projects/2).

---

## Principles

* **One core.** A project that starts with one developer keeps its memory when a team joins. Nothing is migrated to another product.
* **Evidence before status.** A task is not complete because a model claims it. Completion needs a check that ran on the current code, a recorded acceptance with its sources, or a person.
* **Answers name their sources.** A decision, a fact or a summary points to the record it comes from and says how fresh that record is. Without a source there is no answer.
* **Only what was written down travels upward.** Views for a team lead or above read plans and decisions. They do not read conversations, and above the team they do not show who works on what.
