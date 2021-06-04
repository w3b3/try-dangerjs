# try-dangerjs

Trying [DangerJS](https://github.com/danger/danger-js).

- Currently set to run on PR creation and pushing commits to a PR.

- Only being triggered against `dev`.

## Current development target

- [ ] Github action should take variable to fill **PR url**.
- [ ] Block the PR if it doesn't match _AB-1234_ as **title prefix**. This is **check#001**.

Nice to have:

- [ ] Add a comment to the PR (or update its BODY), mentioning it passed check#001 (above) on a specific date.
- [ ] It should run in **any branch** other than `main/master`.

## Other possible options

- [ ] Enforce CHANGELOGs
- [ ] Enforce links to Trello/JIRA in PR/MR bodies
- [ ] Enforce using descriptive labels
- [ ] Look out for common anti-patterns
- [ ] Highlight interesting build artifacts
- [ ] Give warnings when specific files change
