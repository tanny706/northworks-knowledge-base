# Northworks Knowledge Base

## AI-First Organization Principles

This knowledge base is optimized for AI consumption and retrieval, not traditional human folder browsing. The structure prioritizes semantic clarity, rich metadata, and interconnected knowledge over deep hierarchies.

---

## Core Principles

### 1. **Semantic Clarity Over Hierarchy**
- AI retrieves via semantic search, not folder navigation
- Folder structure is minimal (5-7 broad domains)
- Context lives in the note content and metadata, not folder location

### 2. **Metadata is Critical**
Every note MUST have frontmatter with:
```yaml
---
type: strategy | meeting | decision | engagement | client | proposal | person | resource
status: active | completed | archived | draft
date: YYYY-MM-DD
tags:
  - relevant
  - topic
  - tags
related:
  - "[[linked-note]]"
  - "[[another-note]]"
summary: One-line description for AI context
---
```

### 3. **Self-Contained Context**
Each note should be independently understandable. Include:
- **What**: What is this about?
- **Why**: Why does it matter?
- **When**: When was it created/relevant?
- **Who**: Who is involved or affected?

### 4. **Linking Over Nesting**
- Use `[[wiki-links]]` extensively between related notes
- Create bidirectional connections
- Let knowledge graphs emerge organically
- Relationships are more valuable than folder organization

### 5. **Maps of Content (MOCs)**
- Use MOCs instead of deep folder hierarchies
- MOCs cluster related topics and provide entry points
- See `_Index/` folder for hub pages

---

## Folder Structure

```
📁 Business/                  # Core business domains (flat)
  ├── Strategy/               # Positioning, service offerings, competitive differentiation
  ├── Operations/             # Delivery methodology, processes, tools
  ├── Finance/                # Billing rates, utilization, revenue
  └── Business Development/   # Pipeline strategy, BD activities, outreach

📁 Clients/                   # Client profiles and relationship management
  └── _Index.md              # Master client list with status

📁 Engagements/               # Active and past client projects
  └── [client-project-name]/ # One folder per engagement

📁 Proposals/                 # Proposals and SOWs in pipeline

📁 People/                    # Contacts, prospects, partners, advisors

📁 Meetings/                  # All meeting notes (chronological capture)

📁 Inbox/                     # Rapid capture zone (process regularly)

📁 _Index/                    # Maps of Content (MOCs) and hub pages
```

---

## Note Types & Templates

### Strategy Notes
- Positioning, service lines, competitive analysis
- Template: `_Index/Templates/Strategy.md`

### Meeting Notes
- Chronological capture with action items
- Template: `_Index/Templates/Meeting.md`

### Decision Records
- Key decisions with context and rationale
- Template: `_Index/Templates/Decision.md`

### Engagement Briefs
- Active client projects with scope, timeline, owners
- Template: `_Index/Templates/Engagement.md`

### Client Profiles
- Client relationship history, contacts, context
- Template: `_Index/Templates/Client.md`

### Proposals
- Scoping docs, SOWs, pitches in pipeline
- Template: `_Index/Templates/Proposal.md`

### People Notes
- Stakeholder profiles, relationships, context
- Template: `_Index/Templates/Person.md`

---

## Workflow

### 1. **Capture**
- Quick notes go to `Inbox/`
- Use templates for structured content
- Add basic frontmatter immediately

### 2. **Process**
- Review Inbox regularly
- Add rich metadata and links
- Move to appropriate domain folder
- Link to related notes

### 3. **Connect**
- Create links between related concepts
- Update relevant MOCs
- Build knowledge graphs

### 4. **Archive**
- Mark completed items: `status: completed`
- Keep in place (don't move to Archive folder)
- AI can filter by status

---

## Best Practices

### ✅ Do
- Use consistent frontmatter on every note
- Write self-contained notes with full context
- Link generously to related concepts
- Tag with 3-5 relevant keywords
- Include one-line summaries

### ❌ Don't
- Create deep folder hierarchies (max 2 levels)
- Rely on folder location for context
- Create orphan notes (always link from somewhere)
- Use vague titles ("Notes", "Misc")
- Skip metadata "because I'll remember"

---

## AI Retrieval Optimization

### For Best AI Results
1. **Descriptive Titles**: "ACME Corp - Q2 Strategy Engagement" > "Project Notes"
2. **Clear Summaries**: One-line context in frontmatter
3. **Structured Content**: Use consistent headings
4. **Dense Linking**: Connect clients ↔ engagements ↔ meetings ↔ people
5. **Rich Tags**: Use semantic, not organizational tags

### Example Query Patterns
- "Show me all active client engagements"
- "What proposals are pending approval?"
- "Who are our contacts at [Client]?"
- "What decisions were made in the ACME engagement?"

---

## Maintenance

- **Weekly**: Process Inbox, update engagement status
- **Monthly**: Review pipeline, update client profiles
- **Quarterly**: Audit metadata consistency, review BD strategy
- **As Needed**: Create new templates for emerging patterns

---

## Getting Started

1. Start with the Dashboard: `_Index/Dashboard.md`
2. Use templates in `_Index/Templates/`
3. Capture quickly in `Inbox/`, process later
4. Build connections through linking
5. Let the structure evolve with your needs

---

**Remember**: This system prioritizes AI discoverability and semantic relationships over traditional organization. Trust the metadata, linking, and search—not the folders.
