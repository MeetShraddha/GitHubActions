# GitHubActions

### What is github actions?

GitHub Actions is a CI/CD (Continuous Integration/Continuous Delivery) platform built directly into GitHub. It lets you automate workflows triggered by events in your repository.
 
### Core concepts:

Workflows — YAML files in .github/workflows/ that define your automation

Triggers (Events) — what kicks off a workflow: a push, pull request, schedule, manual trigger, etc.

Jobs — a set of steps that run on a virtual machine (runner)

Steps — individual commands or pre-built actions within a job

Actions — reusable units of work you can pull from the GitHub Marketplace (e.g. actions/checkout, actions/setup-node)

### Common use cases:

Run tests automatically on every pull request
Build and deploy apps to AWS, GCP, Vercel, etc.
Publish packages to npm or PyPI
Lint and format code
Send notifications (Slack, email) on events
Automate issue/PR labeling
