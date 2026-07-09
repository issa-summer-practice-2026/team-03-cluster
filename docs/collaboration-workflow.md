# Collaboration workflow setup

## Work tracking
- Create one GitHub Issue per backlog item from [docs/backlog](backlog/README.md).
- Keep each issue focused on one change and assign it to the teammate who will implement it.
- Use the GitHub Projects board to track status as: Backlog → In Progress → Review → Done.

## Pull requests
- Branch names should follow the pattern `type/kebab-case`.
- Every PR must use the repository template and include a `Closes #<issue>` line.
- The teammate who did not author the change should review and approve the PR.

## Protection rules
- Protect `main` with required pull requests, required status checks, at least one review, and conversation resolution.
- Require branches to be up to date before merging and keep a linear history for the repository.
- Disable bypassing of the above rules for admins.

## Stretch goals
- Add signed commits once the core workflow is stable.
- Expand the labeler and add more automation if the team grows.
