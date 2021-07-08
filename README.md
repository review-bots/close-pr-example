# close-pr-example

This is a working example of how you could use the [Label Bot](https://github.com/apps/the-label-bot).

## Scenario

You want to ensure everyone creates small Pull Requests.

So, you could create a Github workflow that will automatically close too large PRs.

## Setup

1. Install the Label Bot application.
1. Create [.github/workflows/close-pr.yaml](.github/workflows/close-pr.yaml) to automatically close Pull Requests.

This example closes `XL` Pull Requests, but you could change the conditions or use other labels for your workflow.

## Example Pull Request

[Pull Request #5](https://github.com/review-bots/close-pr-example/pull/5) shows what happens when a PR is labelled with `size/XL`.