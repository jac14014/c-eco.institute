# Continuity across Claude, Codex and Kimi

Keep the current approved documents and a dated decision log as the authority. At the start of a session, read the current dossier, roster, last accepted decision and outstanding evidence gaps. At the end, write a short handoff containing:

| Field | Required content |
|---|---|
| Document/version | Exact document and revision used |
| Completed | Section IDs and outputs actually changed |
| Evidence | New sources and claim-status updates |
| Decisions | User-approved changes with date |
| Conflicts | Competing sources, including legacy roster differences |
| Next step | Specific prompt or review gate |

An agent should verify the document version before acting on a remembered decision. Do not put confidential HTML dossiers, source data, unpublished manuscripts, personal records or credentials in a public repository.

[ai-memory](https://github.com/akitaonrails/ai-memory) is a separate optional service for cross-agent session recall and handoffs. Its documented integrations include Claude Code, Codex and Kimi Code; check the current [support matrix](https://github.com/akitaonrails/ai-memory/blob/main/docs/support-matrix.md) and [installation guide](https://github.com/akitaonrails/ai-memory/blob/main/docs/install.md) for the specific CLI tools in use. Installing this prompt repository alone does not install ai-memory or connect it to ChatGPT Work, Claude's web interface or Kimi's web interface. Review [data handling](https://github.com/akitaonrails/ai-memory/blob/main/DATA_HANDLING.md) before enabling capture for controlled documents.
