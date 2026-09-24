# c-ECO Agent Workflows

Reusable prompts for drafting and reviewing c-ECO Institute documents and the SIL 19×19 program. These files are written for the c-ECO workflow and can be used with Claude, Codex, or Kimi by pasting the relevant prompt or attaching this repository to an agent session.

## Use

| Workflow | File | When to run |
|---|---|---|
| Verify claims | [`prompts/dossier-fact-check.md`](prompts/dossier-fact-check.md) | Before circulating an Institute, GIH or Living Lab dossier, manuscript, or funding proposal |
| Improve repeated work | [`prompts/workflow-reflection.md`](prompts/workflow-reflection.md) | After several dossier sections or multiple similar applications |
| Edit English prose | [`prompts/institutional-prose-review.md`](prompts/institutional-prose-review.md) | After factual review, before final layout |
| Assess SIL security | [`prompts/sil-security-review.md`](prompts/sil-security-review.md) | When SIL architecture, code or a deployment exists |
| Pass work between agents | [`docs/cross-agent-handoff.md`](docs/cross-agent-handoff.md) | At the start and end of each Claude/Codex/Kimi session |

Work on a copy of the current controlled document. An agent's memory and this repository do not supersede an approved dossier, Board action, signed agreement or evidence record. Keep restricted documents out of a public repository.

## Provenance

These are original c-ECO instructions informed by Fabio Akita's public [my-skills](https://github.com/akitaonrails/my-skills) examples: [fact-check](https://github.com/akitaonrails/my-skills/tree/master/fact-check), [reflect](https://github.com/akitaonrails/my-skills/tree/master/reflect), [humanizer](https://github.com/akitaonrails/my-skills/tree/master/humanizer) and [security-audit](https://github.com/akitaonrails/my-skills/tree/master/security-audit). They do not reproduce his files. His README recommends adapting the examples to one's own workflow. The [ai-memory](https://github.com/akitaonrails/ai-memory) software is a separate project; it is linked here, not copied or installed by this repository.
