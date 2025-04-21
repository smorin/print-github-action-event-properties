# print-github-action-event-proprties
Github Actions that print all github action event properties.

Used for testing purposes of `github actions` see `.github/workflows/`

## Example GitHub Action Event Contexts

These files contain example JSON payloads for the `github.event` context object available in GitHub Actions for different trigger types:

*   [`opened_pr_github_action_event.json`](./opened_pr_github_action_event.json): Event context when a pull request is opened.
*   [`merged_pr_github_action_event.json`](./merged_pr_github_action_event.json): Event context when a pull request is merged (closed).
*   [`opened_issue_github_action_event.json`](./opened_issue_github_action_event.json): Event context when an issue is opened.
*   [`closed_issue_github_action_event.json`](./closed_issue_github_action_event.json): Event context when an issue is closed.