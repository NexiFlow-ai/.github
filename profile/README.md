# NexiFlow

**Nexi** is a governed runtime for building, running, packaging and deploying agentic systems — a suite of
applications over one conversation backbone, one design system, one policy model.

What is public here is a set of **exports** from the Nexi source repository, published from tagged commits by a
pipeline that guards every file before it leaves:

| Repository | What it is | Where it is served |
|---|---|---|
| [`nexi-devportal`](https://github.com/NexiFlow-ai/nexi-devportal) | the documentation site — guides, concepts, API reference | [docs.nexiflow.ai/docs](https://docs.nexiflow.ai/docs/) |
| [`nexi-design-system`](https://github.com/NexiFlow-ai/nexi-design-system) | the design system — the register, the tokens, the component workshop | [docs.nexiflow.ai/design-system](https://docs.nexiflow.ai/design-system/) |
| [`nexi-skills`](https://github.com/NexiFlow-ai/nexi-skills) | the pack commons — skills, agents, flows as installable packs | — |
| [`nexi-home`](https://github.com/NexiFlow-ai/nexi-home) | the landing page | [nexiflow.ai](https://nexiflow.ai/) |

Every exported repository carries a `PROVENANCE.json` naming the source tag, the source commit and a digest of every
file — the same tag always yields the same digest.

- **Contributing:** see [CONTRIBUTING](https://github.com/NexiFlow-ai/.github/blob/main/CONTRIBUTING.md) — changes land
  in the source first and come out with the next export; every commit is signed off (DCO).
- **Security:** see [SECURITY](https://github.com/NexiFlow-ai/.github/blob/main/SECURITY.md) — private vulnerability
  reporting on every repository, never a public issue.
- **Questions:** Discussions on the repository the question is about — see [SUPPORT](https://github.com/NexiFlow-ai/.github/blob/main/SUPPORT.md).

Licence: Apache-2.0 on every export (the decision dataset: CDLA-Permissive-2.0). *Nexi* and *NexiFlow* are names of
the publisher — see `TRADEMARKS.md` in any export.
