# TechGyaan GitHub Repository Structure Plan

## Purpose

This repository is the central resource hub for the **TechGyaan**
YouTube channel. Every video should have a corresponding folder
containing source code, notes, commands, cheat sheets, and references.

------------------------------------------------------------------------

# Root Structure

``` text
TechGyaan/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/
│
├── docs/
├── assets/
│   ├── images/
│   ├── thumbnails/
│   ├── logos/
│   └── banners/
│
├── series/
│   ├── git-github/
│   ├── ai-api-development/
│   ├── ai-tools/
│   ├── prompt-engineering/
│   ├── dotnet/
│   ├── react/
│   ├── javascript/
│   ├── sql/
│   ├── mongodb/
│   ├── system-design/
│   ├── interview/
│   ├── aptitude/
│   ├── devops/
│   ├── cloud/
│   ├── vscode/
│   └── misc/
│
└── templates/
```

------------------------------------------------------------------------

# Standard Video Folder

``` text
day-001-topic-name/
│
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

------------------------------------------------------------------------

# README Template

Each README should include:

1.  Video Title
2.  YouTube Link
3.  Learning Objectives
4.  Prerequisites
5.  Commands
6.  Step-by-Step Explanation
7.  Example
8.  Common Mistakes
9.  Practice Exercise
10. Downloadable Resources
11. Related Videos
12. License

------------------------------------------------------------------------

# Naming Standards

-   Use lowercase folder names.
-   Separate words with hyphens.
-   Prefix sequential content with `day-001`, `day-002`, etc.
-   Avoid spaces in file/folder names.

------------------------------------------------------------------------

# Repository Rules for LLM

1.  Never delete existing content unless explicitly instructed.
2.  Preserve folder naming conventions.
3.  Add new videos only under the appropriate series.
4.  Every new video folder must include the standard template.
5.  Update the series README and root README when new content is added.
6.  Keep Markdown formatting consistent.
7.  Prefer relative links.
8.  Store images in `assets/` unless specific to one video.
9.  Store reusable files in `templates/`.
10. Keep commits atomic and descriptive.

------------------------------------------------------------------------

# Recommended Series

| Series | Folder |
| --- | --- |
| Git & GitHub Shorts | `series/git-github/` |
| 100 Days AI API Development | `series/ai-api-development/` |
| AI Tools | `series/ai-tools/` |
| Prompt Engineering | `series/prompt-engineering/` |
| ASP.NET Core | `series/dotnet/` |
| React | `series/react/` |
| JavaScript | `series/javascript/` |
| SQL | `series/sql/` |
| MongoDB | `series/mongodb/` |
| System Design | `series/system-design/` |
| DevOps | `series/devops/` |
| Cloud | `series/cloud/` |
| Interview Questions | `series/interview/` |
| Aptitude | `series/aptitude/` |
| VS Code Tips | `series/vscode/` |
| Miscellaneous | `series/misc/` |

------------------------------------------------------------------------

# Future Expansion

-   Projects
-   Roadmaps
-   Certifications
-   E-books
-   Coding Challenges
-   Open Source Contributions
-   Community Resources

This structure is designed to scale from tens to thousands of
educational resources while remaining easy to navigate for both humans
and LLMs.
