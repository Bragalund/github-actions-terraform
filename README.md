# GitHub Actions Demo

Minimal repository showing a simple GitHub Actions workflow that prints the event name and lists repository files on each push.

## Features
- Single workflow (`.github/workflows/github-actions-demo.yml`) triggered on every push
- Logs the triggering event and lists files in the GitHub workspace
- Serves as a starting point for adding more steps (e.g., Terraform plans/apply, builds, tests)

## Getting Started
1) Fork or clone the repository.
2) Push any commit to `main` (or any branch) to trigger the workflow.
3) View workflow runs under **Actions** in GitHub to inspect logs.

## Customizing
- Add new steps under the existing job to build, test, or deploy your project.
- Replace the list-files step with your Terraform `plan`/`apply` commands if using this as a Terraform pipeline starter.

## Contributing
Issues and pull requests are welcome. Please describe the intended workflow change clearly.

## License
This project is open source under the terms of the `LICENSE` file in this repository.
