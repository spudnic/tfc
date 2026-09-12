# AI Agents Guidelines - tfc

## Agent Context
This repository is designed to be agent-friendly. Most complex operations are abstracted into the `Taskfile.yml` to provide a consistent interface for both humans and AI agents.

## Interaction Patterns
- **Task-First**: Before attempting to run a shell command, check `Taskfile.yml` to see if a task target already exists for that action.
- **Isolation**: Prefer using the provided Docker-based tasks over installing tools locally.
- **Verification**: Always run `task rust-test` (for Rust) or `task tf-plan` (for Terraform) before suggesting changes to critical infrastructure or logic.

## References
- Project overview: [[README.md]]
- Developer guidelines: [[CLAUDE.md]]