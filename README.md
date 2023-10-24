# This is a space of Data Platform team's issues

Near.org Data Platform Initiatives and Epics: Recommendations, Search, Analaytics

## How to use GitHub

- Roadmap: https://github.com/orgs/near/projects/80/views/3?sliceBy%5Bvalue%5D=Data+Platform
- QueryAPI tickets in queryapi repo
- General Data platform epics and tickets are data-platform repo

## Data Platform Initiatives
- Should have clear title that could be understood by anyone in the ecosystem
- Should have Data Platform team assigned
- Should have a description with high-level functionality, without technical details
- Should have at least one epic in the relevant team’s repository that implements it
- Should have defined Priority and Impact

## Data Platform Epics
- Should be used to group issues into user-facing functionality that is publicly announced.
- Should take at most one quarter to complete.
- Should have the title that describes the end-user value. If this is not possible (i.e. the epic is about refactoring),consider moving sub-issues to other epics that have appropriate title.
- Should be connected to a Pagoda Initiative in the [Pagoda Public Roadmap](https://github.com/orgs/near/projects/80/views/3?sliceBy%5Bvalue%5D=Data+Platform)
- Ideally have a milestone assigned. The milestone is some public announcement, conference, a sunset of a functionality or some other important external event.

## Creating GitHub issues
- Should be included in the Data Platform project (now automated)
- Should be connected to a relevant Epic
- Should be linked to an issue that blocks it, or if it is blocking another issue.
- Should not have an assigned person if it is unclear who will work on this issue.
- Ideally have an appropriate label: `bug`, `indexer`

## Issues lifecycle
- Todo
- Selected
- In Progress
- In Review
- Released to Staging (through GitHub Actions)
- Issue is 'Done' when it is released to production (through GitHub Actions)

## Working on GitHub issues
- Ensure the state is 'In Progress'
- If issue involves writing code, start a draft PR as soon as possible, so that the team can see the progress
- Connect it to a relevant Pull Request. If PR-linking functionality doesn’t work, drop PR link to a comment

## Communication
- All ticket-related communication should be in issues: questions about functionality
- If the communication happens in slack, the decision should be pasted in the description of the issue or in a comment
