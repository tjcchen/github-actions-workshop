## github actions workshop
github actions workshop.

## github actions concept
Event - trigger workflows: push, pull_request, issue created, issue closed etc.

Job - a job contains multiple steps.

Steps - steps to run a job, including actions/commands.

Actions - a series of actions for setting up env, like: `uses: actions/checkout@v3, uses: actions/setup-python@v3, uses: actions/setup-node@v3`

Commands - a series of shell commands.

Runner - each job will be run on a virtual machine. Runner could be host by github, like ubuntu-latest, window and macOS, or self-hosted.

**NB: It is worth noting that each action/command of a job runs sequentially, but each job can be performed in parallel in different machines.**

## resources
docs: https://docs.github.com/en/actions

## license
MIT
