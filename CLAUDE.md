# Claude Code Guidelines - tfc

## Project Overview
This project uses Terraform Cloud and Rust. Most operations are wrapped in Docker containers via a `Taskfile.yml`.

## Development Commands
- **Build Rust**: `task rust-build`
- **Full SDLC (Format, Lint, Test)**: `task rust-all`
- **Run Tests**: `task rust-test`
- **Lint**: `task rust-lint`
- **Format**: `task rust-format`
- **Terraform Init**: `task tf-init`
- **Terraform Plan**: `task tf-plan`
- **Terraform Apply**: `task tf-apply`

## Code Style & Patterns
- Match the existing comment density and naming conventions of the surrounding code.
- Use Docker-based task targets for consistency across environments.
- Follow Rust idioms for the `/rust` directory.

## References
- Project overview: [[README.md]]
- Agent guidelines: [[AGENTS.md]]