# Governance

## Maintainers

The repositories of this organization are maintained by NexiFlow. The current maintainers are the members of the
organization's *maintainers* team; `CODEOWNERS` in each repository names who answers a pull request.

## How a decision is taken

- **Content of an export** (a page, a component, a pack, a row of the dataset): a maintainer decides, in the source
  repository, and the change comes out with the next export. A contributor's pull request is the proposal; the
  maintainer's answer on it is the decision and its reason.
- **What is published, under which licence, how the pipeline works:** the organization's owners decide, and the
  decision is recorded in the source repository's architecture decision records. A change of licence is announced in
  the repository's `README.md` and takes effect at the next export; nothing published is re-licensed retroactively.
- **Retraction:** when something that should not have left the source is found in an export, a maintainer removes it
  from the source, a new export is published, and the affected tags are marked in the repository's releases. History
  is rewritten only when the law or a person's safety requires it, and then with notice.

## How a maintainer joins

A contributor whose pull requests and reviews have been accurate and kind over time is invited by the existing
maintainers; the invitation says which repositories. A maintainer who has been away for a year is asked whether to
stay. There is no vote count; there is a conversation and a written answer.

## What this is not

This is not a foundation project and does not claim to be one. The source is not public; the exports are. We say so
plainly so that nobody mistakes a publication for a community-owned codebase.
