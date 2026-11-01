# Contributing

Suggest resources that help developers use AI in a concrete software engineering workflow.

## What belongs here

* Tools, documentation, articles, example workflows, research, talks, case studies and collections that help an engineer plan, build, review, test, ship, operate or maintain software with AI.
* **Real configs:** instruction files (`AGENTS.md`, `CLAUDE.md`, `copilot-instructions.md`) and agent workflows committed to public repositories. Link the file itself, pinned to the default branch, and say what is worth studying in it.
* General AI news, model catalogs, prompt collections without a development task, and automation unrelated to software development are out of scope.

## Resource selection

* Prefer original sources: project repositories, official documentation, author articles, papers and engineering team posts. Use other lists for discovery, not as the link.
* Explain what the resource helps a developer do.
* Check existing entries before adding a resource. Use one primary section per resource.
* Keep descriptions factual. Do not copy marketing claims, performance numbers or assurances of production readiness without supporting evidence.
* Mark resources tied to a paid plan or a single commercial service with `$`.
* Do not add archived or clearly abandoned projects unless they are still a useful reference, and say so.
* Distinguish examples that have been read from workflows that have actually been executed. A passing link check does not validate an agent's behavior.

## Entry format

```markdown
* 🛠️ [Resource name](https://example.com/resource): A short description of the task it helps perform.
```

| Icon | Type |
| :-: | --- |
| 🛠️ | Tool |
| 📘 | Documentation |
| 📝 | Article or talk |
| 🧪 | Research |
| 🏢 | Case study |
| 🧩 | Example workflow |
| 📦 | Collection |
| ⚙️ | Real config (added to the tables in [Real-world setups](README.md#real-world-setups)) |

Use English descriptions and descriptive link labels. Keep each description to one sentence. A new section is welcome once there are enough relevant resources to make it useful.

## Pull requests

* One topic per pull request.
* Links are checked automatically by the `links` workflow.
