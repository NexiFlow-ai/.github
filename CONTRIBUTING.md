# Contributing

Thank you for taking the time. Three things decide how a contribution travels here.

## 1. Every public repository is an export

The repositories under NexiFlow are **publications** of a source repository that is not public. A pipeline exports a
unit (the docs, the design system, a pack, a dataset) from a tagged commit, runs a guard over every file, writes the
licence and the provenance, and pushes the result as one commit. Nothing is read back from a public repository.

So a pull request here cannot be merged *here* — `main` is written only by the publisher. What happens instead:

1. A maintainer reads your pull request and answers on it.
2. An accepted change is made in the source repository, with you credited in the commit message
   (`Co-authored-by: Your Name <you@example.com>` when you wish, or your handle).
3. The change comes out with the next export; the pull request is closed with a comment naming the tag that carried it.

Small, specific pull requests travel fastest: a wrong sentence, a broken link, a missing state in a story, a pack whose
manifest is off by one field. For anything larger, open an issue or a discussion first and say what you intend.

## 2. Sign your commits off (DCO)

We use the [Developer Certificate of Origin](https://developercertificate.org/) — no contributor licence agreement.
Signing off says the four things the DCO says: the work is yours or you have the right to submit it under the
repository's licence. Add the line to every commit:

```
Signed-off-by: Your Name <you@example.com>
```

`git commit -s` adds it for you. A pull request with an unsigned commit fails the `dco` check and waits.

## 3. What a contribution is licensed under

Your contribution is licensed under the licence of the repository it lands in — Apache-2.0 for the docs, the design
system, the packs and the toolkit; CDLA-Permissive-2.0 for the decision dataset. Third-party content you bring must
carry a compatible licence and its notice; say where it comes from in the pull request.

## Where to go

| You want to… | Do this |
|---|---|
| report a mistake in the docs | an issue of type *docs issue* on `nexi-devportal` |
| report a bug in a pack or the toolkit | an issue of type *bug* on `nexi-skills` |
| propose a pack or a skill | an issue of type *pack proposal* or *skill proposal* on `nexi-skills` |
| report a problem with the dataset or the recipe | an issue of type *dataset / recipe issue* on `nexi-decision` |
| ask a question | Discussions — see `SUPPORT.md` |
| report a security problem | **not an issue** — see `SECURITY.md` |

## Conduct

Everyone here follows the [Code of Conduct](./CODE_OF_CONDUCT.md).
