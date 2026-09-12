lets # [Terraform Cloud Workspace tfc](https://app.terraform.io/app/sdinc/workspaces/tfc)

This workspace manages the Terraform infrastructure for SDinc.

## Dependencies

* **docker**: Required for running Terraform and Rust tools in isolated environments. [Install Docker Desktop](https://www.docker.com/products/docker-desktop/).
* **task**: Used for task orchestration. Install via:
  ```sh
  sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b ~/.local/bin
  ```
  More details at [taskfile.dev](https://taskfile.dev/installation/#get-the-binary).

## Getting Started

To see all available tasks for this project, run:
```bash
task
```

## Documentation

* For developer guidelines and project-specific commands, see [[CLAUDE.md]].
* For information regarding AI agent interactions, see [[AGENTS.md]].