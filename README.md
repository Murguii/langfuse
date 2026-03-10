# Langfuse

Langfuse project repository.

## GitHub Actions

This repository includes the workflow from the [GitHub Actions Quickstart](https://docs.github.com/en/actions/get-started/quickstart) guide.

The workflow is defined in `.github/workflows/github-actions-demo.yml`. It triggers on every `push` and runs a job called `Explore-GitHub-Actions` on an `ubuntu-latest` runner that:

1. Prints the event type, OS, branch, and repository name.
2. Checks out the repository code using `actions/checkout@v5`.
3. Lists all files in the repository workspace.
4. Reports the final job status.

### Running the workflow

Push any commit to this repository and navigate to the **Actions** tab on GitHub to see the workflow run and its step-by-step logs.

