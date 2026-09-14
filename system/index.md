# System Index

- [[system/architecture]]

## Action Routing

Load only the row that matches the current action. Read the protocol first, then the referenced template and prompt when creating or changing a file. Read the relevant Area or Project `README.md` when ownership or local context is needed.

| Action | Protocol | Template | Prompt |
| --- | --- | --- | --- |
| Create or organize a personal note | `system/protocols/working-notes.md`, `system/protocols/metadata-and-links.md` | `system/templates/working-note.md` | `system/prompts/organize-note.md` |
| Process a Web Clipper or manual resource | `system/protocols/resource-processing.md`, `system/protocols/metadata-and-links.md` | `system/templates/resource.md` | `system/prompts/process-resource.md` |
| Design or advance a learning session | `system/protocols/learning-behavior.md` | `system/templates/working-note.md` | `system/prompts/organize-note.md` |
| Decide whether a recurring question becomes a standalone note | `system/protocols/questions.md` | `system/templates/question.md` | Use the current task prompt; no dedicated execution prompt |
| Generate a central daily or monthly review | `system/protocols/reviews.md`, `system/protocols/metadata-and-links.md` | Matching file in `system/templates/` | Use the current task prompt; no dedicated execution prompt |

## Control-Plane Map

- Architecture and ownership: `system/architecture.md`
- Personal note processing: `system/protocols/working-notes.md`
- Resource processing: `system/protocols/resource-processing.md`
- Questions: `system/protocols/questions.md`
- Reviews: `system/protocols/reviews.md`
- Shared metadata and links: `system/protocols/metadata-and-links.md`
- Templates: `system/templates/`
- Execution prompts: `system/prompts/`
