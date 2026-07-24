# TechGyaan

TechGyaan is the central resource hub for the TechGyaan YouTube channel. It collects source code, commands, notes, references, examples, and practice material for videos across software development, AI, cloud, DevOps, interview preparation, and productivity topics.

## Repository Layout

```text
TechGyaan/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
├── docs/
├── assets/
├── series/
└── templates/
```

## Series

| Series | Folder | Focus |
| --- | --- | --- |
| Git & GitHub Shorts | [series/git-github](series/git-github) | Git basics, GitHub workflows, branching, pull requests, and collaboration. |
| 100 Days AI API Development | [series/ai-api-development](series/ai-api-development) | API projects, AI integrations, prompts, agents, and backend patterns. |
| AI Tools | [series/ai-tools](series/ai-tools) | Practical workflows with developer AI tools. |
| Prompt Engineering | [series/prompt-engineering](series/prompt-engineering) | Prompt design, evaluation, and reusable patterns. |
| ASP.NET Core | [series/dotnet](series/dotnet) | .NET, C#, ASP.NET Core, APIs, and application architecture. |
| React | [series/react](series/react) | React apps, components, state, routing, and UI patterns. |
| JavaScript | [series/javascript](series/javascript) | Core JavaScript, browser APIs, and practical examples. |
| SQL | [series/sql](series/sql) | Queries, schema design, joins, indexing, and database practice. |
| MongoDB | [series/mongodb](series/mongodb) | NoSQL modeling, queries, aggregation, and application usage. |
| System Design | [series/system-design](series/system-design) | Architecture, scalability, tradeoffs, and design interviews. |
| DevOps | [series/devops](series/devops) | CI/CD, automation, containers, releases, and deployment basics. |
| Cloud | [series/cloud](series/cloud) | Cloud concepts, services, deployment, and architecture. |
| Interview Questions | [series/interview](series/interview) | Technical interview preparation and topic-wise question sets. |
| Aptitude | [series/aptitude](series/aptitude) | Reasoning, quantitative aptitude, and placement preparation. |
| VS Code Tips | [series/vscode](series/vscode) | Editor productivity, extensions, shortcuts, and workflows. |
| Miscellaneous | [series/misc](series/misc) | Resources that do not fit a primary series yet. |

## Standard Video Folder

Video resources should be added under the relevant series folder using lowercase, hyphen-separated names:

```text
series/<series-name>/day-001-topic-name/
├── README.md
├── summary.md
├── commands.txt
├── source-code/
├── examples/
├── practice/
├── screenshots/
├── references.md
└── resources/
```

Use [templates/video-readme-template.md](templates/video-readme-template.md), [templates/summary-template.md](templates/summary-template.md), [templates/references-template.md](templates/references-template.md), and [templates/commands-template.txt](templates/commands-template.txt) when creating new video folders.

## Contribution Workflow

1. Choose the correct folder under [series](series).
2. Create a new video folder using the `day-001-topic-name` naming format.
3. Add the standard video files and folders from [templates/video-folder-structure.md](templates/video-folder-structure.md).
4. Update the related series README.
5. Update this root README if the new content should be highlighted.
6. Prefer relative links for all internal references.

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution details.

## License

License details are tracked in [LICENSE](LICENSE).