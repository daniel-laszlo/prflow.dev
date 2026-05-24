# PRFlow — GitLab Merge Request Notifications for Slack

**Stop GitLab from spamming your Slack channels.** PRFlow replaces GitLab's noisy Slack notifications with one clean, updating message per merge request.

## What is PRFlow?

PRFlow is a Slack integration for GitLab that consolidates merge request notifications into a single, auto-updating Slack message. Instead of 10+ separate messages per MR (opened, pipeline started, pipeline passed, comment, approved, merged...), PRFlow posts one message and updates it in place as the MR progresses.

## Key Features

- **One message per merge request** — PRFlow posts a single Slack message when an MR is opened, then updates it through approval, pipeline status changes, and merge. No duplicate messages.
- **CI/CD pipeline status** — See pipeline pass/fail/running status directly on the Slack notification without opening GitLab.
- **Threaded comment sync** — GitLab code review comments appear in a Slack thread attached to the MR notification. Edited comments update in place.
- **Works with gitlab.com and self-hosted GitLab** — Connect with OAuth or a read-only access token.
- **Channel routing** — Map GitLab projects to specific Slack channels, with an optional default channel for unmapped repos.

## How is PRFlow different from GitLab's official Slack app?

GitLab for Slack sends a new message for every event — easily 10+ messages per merge request. PRFlow sends one message per MR that updates in place, shows CI/CD pipeline status inline, and syncs review comments to a Slack thread.

## Getting Started

Sign up at [prflow.dev](https://prflow.dev).

## Links

- **Website:** [prflow.dev](https://prflow.dev)
- **Support:** hello@prflow.dev
