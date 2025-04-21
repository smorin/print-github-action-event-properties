# print-github-action-event-properties
Github Actions that print all github action event properties.

Used for testing purposes of `github actions` see `.github/workflows/`

## Example GitHub Action Event Contexts

These files contain example JSON payloads for the `github.event` context object available in GitHub Actions for different trigger types:

*   [`opened_pr_github_action_event.json`](./opened_pr_github_action_event.json): Event context when a pull request is opened.
*   [`merged_pr_github_action_event.json`](./merged_pr_github_action_event.json): Event context when a pull request is merged (closed).
*   [`opened_issue_github_action_event.json`](./opened_issue_github_action_event.json): Event context when an issue is opened.
*   [`closed_issue_github_action_event.json`](./closed_issue_github_action_event.json): Event context when an issue is closed.

Github Documentation:
- [Triggering a workflow](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/triggering-a-workflow)
- [Jobs in workflows](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/using-jobs-in-a-workflow)
