# 🤝 Collaborator

## Purpose

This file defines how information about people should be remembered inside my Obsidian vault.

The goal is to build a living engineering collaboration graph instead of a simple contacts list. Every person should become a connected node that links to projects, technologies, events, and other collaborators.

---

# General Behavior

Whenever I naturally mention meeting, working with, or learning about a person, assume I want to remember them unless I explicitly say otherwise.

Examples:

- "I met someone named Rahul today..."
- "There's a senior named Akash..."
- "My teammate Priya..."
- "I spoke with a backend developer..."
- "My friend John knows Kubernetes."

Treat these as opportunities to create or update collaborator notes.

---

# What to Extract

From natural language, automatically identify and remember any useful information such as:

## Identity

- Full name
- Nickname (if mentioned)
- College or company
- Department
- Year of study
- Role

## Technical Profile

- Programming languages
- Frameworks
- Tools
- Platforms
- Databases
- Cloud technologies
- Areas of expertise

## Interests

- AI
- Backend
- Frontend
- DevOps
- Cybersecurity
- Open Source
- Competitive Programming
- Startups
- Research

## Collaboration

- Projects worked on
- Events attended together
- Hackathons
- Workshops
- Clubs
- Communities

## Relationship

- How we met
- Why they're useful to remember
- Any notable technical observations
- Future collaboration opportunities

---

# What NOT to Store

Do NOT remember:

- Casual greetings
- Random conversations
- Personal gossip
- Sensitive personal information
- Information unrelated to collaboration
- Temporary details with no future value

Only remember information that could help me collaborate, network, build projects, or learn.

---

# Obsidian Rules

Create one note per collaborator.

Use the person's full name as the filename.

Always create wiki links whenever possible.

Examples:

- [[Java]]
- [[Docker]]
- [[React]]
- [[SIH 2027]]
- [[AI Internship Recommendation Engine]]
- [[John Doe]]

Never duplicate collaborators.

If a collaborator already exists, update their note instead.

---

# Relationships

Whenever possible, connect collaborators to:

- Skills
- Technologies
- Projects
- Events
- Other collaborators

The graph should naturally grow over time.

---

# Information Priority

Prioritize remembering:

1. Skills
2. Expertise
3. Projects
4. Shared events
5. Technical interests
6. Collaboration history

---

# Example Inputs

Input:

> I met Rahul at the NEC workshop. He's a second-year CSE student at CIT. He's good at Java and Spring Boot and wants to participate in SIH.

Remember:

- Rahul
- CIT
- Second Year CSE
- [[Java]]
- [[Spring Boot]]
- [[NEC Workshop]]
- [[SIH]]
- Interested in hackathons

---

Input:

> My teammate Sarah handled the backend using Node.js and PostgreSQL.

Remember:

- Sarah
- [[Node.js]]
- [[PostgreSQL]]
- Backend Development

---

Input:

> Arjun recently started learning Kubernetes and Docker.

Remember:

- Arjun
- [[Docker]]
- [[Kubernetes]]

---

# Expected Note Structure

Every collaborator note should contain, when available:

- Name
- Role
- Organization / College
- Skills
- Interests
- Expertise
- Projects
- Events
- Collaborators
- Contact Information
- Last Meaningful Interaction
- Notes
- Tags

Missing fields may be omitted.

---

# Query Goals

This knowledge graph should be able to answer questions like:

- Who knows Java?
- Who knows Docker?
- Who has worked with React?
- Who attended NEC?
- Who is interested in AI?
- Who should I ask about cybersecurity?
- Who would make a good hackathon teammate?
- Which technologies are common among my collaborators?
- Which people have I collaborated with the most?
- Show everyone connected to [[Spring Boot]].
- Show everyone connected to [[SIH]].

---

# Writing Style

Keep notes:

- Short
- Accurate
- Technical
- Searchable
- Well linked

Avoid unnecessary text.

---

# Long-Term Objective

Build a searchable engineering relationship graph that grows naturally from everyday conversations.

I should be able to mention someone once in normal conversation, and the graph should automatically remember the important technical details, connect them to relevant technologies, projects, events, and collaborators, and update existing knowledge without creating duplicates.
