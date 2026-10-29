# NetWorkOS — AI-Powered Collaborator Memory

NetWorkOS is an AI-powered collaborator memory system built with **Antigravity CLI** and **Obsidian**. It transforms natural-language descriptions into a structured, searchable engineering knowledge graph, helping you remember people, their skills, projects, technologies, interests, and the events where you met them.

Instead of losing valuable connections in scattered notes, NetWorkOS helps build a connected knowledge base that makes it easier to discover the right people for a project, find specific skills, and recall past interactions.

## Key Features

- **Natural-Language Capture:** Describe a person or interaction in plain English instead of manually filling out structured forms.
- **Automatic Note Creation and Updates:** Create or update collaborator notes based on extracted information.
- **Structured Collaborator Profiles:** Organize details such as education, skills, technologies, interests, projects, and events.
- **Obsidian Wiki Links:** Connect related people and entities through internal links.
- **Knowledge Graph:** Build relationships between collaborators, skills, projects, technologies, and events.
- **Natural-Language Queries:** Find collaborators based on skills, interests, previous meetings, or project requirements.
- **Reusable Knowledge Base:** Keep collaboration-related information organized in Markdown files within an Obsidian vault.

## How It Works

1. **Capture:** Describe a person, meeting, or professional interaction in natural language.
2. **Extract:** Use the AI-assisted workflow to identify relevant details.
3. **Organize:** Create or update the appropriate collaborator notes.
4. **Connect:** Link related people, skills, projects, technologies, and events using Obsidian wiki links.
5. **Discover:** Search the resulting knowledge base to find relevant people and connections.

## Example

### Input

```text
I met Arun today. He's a 2nd-year CSE student at CIT,
skilled in Java and Spring Boot, and interested in AI.
```

### Extracted Information

| Field | Example value |
|---|---|
| Name | Arun |
| College | CIT |
| Year | 2nd Year |
| Skills | Java, Spring Boot |
| Interest | AI |

NetWorkOS organizes these details into a collaborator note and can connect related entities through Obsidian wiki links.

## Example Queries

Once the knowledge base contains relevant information, you can use queries such as:

- Who knows Docker?
- Who should I contact for AI?
- Who did I meet at the NEC workshop?
- Who has experience with Spring Boot?
- Who could be a suitable teammate for a hackathon?

The answers depend on the information captured in your collaborator notes.

## Technology Stack

- **Antigravity CLI** — AI-assisted workflow for capturing and organizing collaborator information.
- **Obsidian** — Knowledge management and graph visualization.
- **Markdown** — Human-readable storage for collaborator notes.
- **Obsidian Wiki Links** — Connections between related notes and entities.

## Prerequisites

Before using NetWorkOS, make sure you have:

- [Obsidian](https://obsidian.md/) installed.
- [Antigravity](https://antigravity.google/) and its CLI workflow configured, as required by your setup.
- A local Obsidian vault for storing collaborator notes.
- Access to the AI capabilities required by your configured workflow.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/minhuparthasarathy/NetworkOS.git
cd NetworkOS
```

### 2. Open the project

Open the repository in your preferred editor and review the project instructions and `collaborator.md` guidelines.

### 3. Configure your Obsidian vault

Open the relevant project directory or configured vault in Obsidian. Ensure the workflow writes collaborator notes to the intended location.

### 4. Configure the AI-assisted workflow

Set up Antigravity CLI according to your environment and review any project-specific instructions required to process natural-language input.

### 5. Capture and explore collaborators

Use the configured workflow to describe people and interactions, organize the resulting notes, and explore their relationships using Obsidian's search and graph features.

**Note:** NetWorkOS is organized around Markdown notes and an AI-assisted Obsidian workflow. The exact CLI commands and configuration steps depend on your local Antigravity setup; verify them against your installed version and project instructions.

## Project Structure

```text
NetworkOS/
├── collaborator.md   # Guidelines for structuring collaborator notes
├── README.md         # Project documentation
└── LICENSE            # MIT License
```

The collaborator notes and additional knowledge-base files may be created as you use the system, depending on your vault configuration.

## Potential Use Cases

- **Hackathon Networking:** Find people with complementary skills when forming teams.
- **Developer Communities:** Remember members, their interests, and technical expertise.
- **Event Follow-Ups:** Recall who you met at workshops, conferences, and meetups.
- **Project Collaboration:** Identify people with relevant experience for a new project.
- **Personal Knowledge Management:** Build a connected record of professional relationships over time.

## Future Improvements

Potential directions for extending NetWorkOS include:

- More advanced natural-language search across collaborator notes.
- Improved duplicate detection and collaborator profile merging.
- Timeline views for meetings, events, and interactions.
- Richer relationship visualizations for projects, people, and technologies.
- Structured validation to keep collaborator information consistent.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**NetWorkOS — Turn conversations into connections, and connections into knowledge.**
