# Presence audit report v1

This report is a point-in-time record of my public GitHub presence, collected on 2026-10-22 so the facts live outside my head ahead of a review committee. All figures were read directly from the GitHub API on the day of the audit.

## Account snapshot

- **Public repositories: 4** (matches the count reported on my profile).
  1. **Little-rookie** (https://github.com/HeziLiu/Little-rookie) — "Undergraduate coursework", Java, not a fork, default branch `master`, created 2018-05-15, last pushed 2019-06-02.
  2. **Big-Buzzard** (https://github.com/HeziLiu/Big-Buzzard) — "For future....", no primary language, not a fork, default branch `master`, created 2018-05-15, last pushed 2018-05-17.
  3. **CodingInterviewChinese2** (https://github.com/HeziLiu/CodingInterviewChinese2) — "《剑指Offer》第二版源代码", C++, a fork, default branch `master`, created 2019-03-12.
  4. **awesome-chatgpt-prompts-zh** (https://github.com/HeziLiu/awesome-chatgpt-prompts-zh) — "ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。", a fork, default branch `main`, created 2023-04-14.
- 2 of the 4 are original repositories and 2 are forks.
- Profile: Hezi Liu (BUPT/GZU, Beijing/Guiyang), account created 2017-05-22; 5 followers, 5 following, 0 public gists.
- No private repositories are visible to the token used for this audit.

## Open pull requests

- **Open pull requests I have authored anywhere on GitHub: 761** at the time of the final reading (2026-10-22).
- All of them live in the `mcpmark-eval-liuhezi` organization (drill and sandbox repositories); **0 open pull requests in my four personal repositories** (Little-rookie, Big-Buzzard, CodingInterviewChinese2, awesome-chatgpt-prompts-zh), confirmed by per-repo listing.
- The total moves a little from minute to minute because new sandbox PRs keep being opened; 761 is the final reading taken while writing this report.

## Secret scanning

- **Secret scanning alerts retrievable: 0 — the check came back empty because the API is not accessible.**
- Every attempt to list secret scanning alerts for the four personal repositories and for this audit repository returned `403 Resource not accessible by personal access token`. The token in use does not carry the permission the secret-scanning API requires, so no alert list could be read for any repository, and no open (or resolved) alert can be confirmed or ruled out from here.
- No secret-scanning data was therefore written to this report beyond the access failure, and re-running the check with a properly scoped token is tracked as a follow-up.

## Actions and discussions

- **GitHub Actions: none of my 4 public repositories run any workflows.** `list_workflows` returned a total count of 0 for Little-rookie, Big-Buzzard, CodingInterviewChinese2 and awesome-chatgpt-prompts-zh. Because no repository has any workflow, there is **no latest run to report and no run status to record** — the latest-run question comes back empty for every repository.
- **Discussions: none of my 4 public repositories have discussions enabled or contain any discussions.** All four report `has_discussions: false`, and listing discussions returns a total count of 0 for each. There are therefore **no discussion comments to read through and nothing worth keeping from them** — the discussion question also comes back empty.
