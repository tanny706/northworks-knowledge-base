---
type: resource
status: active
date: 2026-04-20
tags:
  - example
  - guide
  - meta
related:
  - "[[README]]"
  - "[[_Index/Dashboard]]"
summary: Example note demonstrating AI-first principles for a consulting vault
---

# Example - How to Use This System

This note demonstrates the key principles in action, adapted for consulting work.

## Notice the Frontmatter
Every note starts with YAML metadata:
- `type` — helps AI categorize (engagement, client, proposal, meeting, decision, etc.)
- `status` — tracks state (active, completed, archived, draft)
- `date` — temporal context
- `tags` — semantic keywords for discovery
- `related` — explicit connections to other notes
- `summary` — one-line AI context

## Self-Contained Context
This note answers:
- **What**: A working example of the system principles
- **Why**: To show how metadata and linking work together for consulting workflows
- **When**: Created 2026-04-20 as part of initial setup
- **Who**: Template for Northworks consulting knowledge management

## Rich Linking — Consulting Style
Connect concepts with `[[wiki-links]]`:
- Client profile: `[[Clients/ACME Corp]]`
- Engagement: `[[Engagements/ACME Corp - Digital Strategy]]`
- Meeting: `[[Meetings/2026-04-20 - ACME Kickoff]]`
- Person: `[[People/Jane Smith]]`
- Proposal: `[[Business/Business Development/ACME Proposal Q2]]`

This creates a **client knowledge graph** — from first contact through delivery and beyond.

## Consulting Workflow Example

### 1. Capture (You are here!)
Drop a quick note in [[Inbox/]] — a call recap, an idea, a client insight.

### 2. Process
- Create a proper note using the right template
- Add frontmatter (type, status, date, tags, client link, summary)
- Move to the right folder (Clients/, Engagements/, Meetings/, etc.)

### 3. Connect
- Link the meeting note to the client profile
- Link the client profile to the engagement
- Link the engagement to the proposal it came from
- Add the person to the People/ note

### 4. Retrieve
AI can now answer:
- "What did we discuss with ACME last month?"
- "What proposals do we have outstanding?"
- "Who are our contacts at TechCorp?"
- "What's the status of the Strategy engagement?"

## Why This Works for Consulting

Traditional approach:
```
/Client Files/ACME/2026/Q2/Meeting Notes v3 FINAL.docx
```
Context is buried in folders and filenames. AI can't connect it to the proposal or the client relationship.

AI-first approach:
```yaml
---
type: meeting
tags: [acme, strategy, kickoff]
client: "[[Clients/ACME Corp]]"
related: ["[[Engagements/ACME - Digital Strategy]]", "[[People/Jane Smith]]"]
summary: Kickoff meeting for ACME digital strategy engagement
---
```
AI immediately understands this is a kickoff for a specific engagement with a specific client, and can retrieve it in context.

## Your Turn

Try it:
1. Create a quick note in [[Inbox/]]
2. Use a template from [[_Index/Templates/]]
3. Add metadata and links
4. See how easy it becomes to retrieve later

---

**Remember**: Optimize for future AI retrieval, not current folder browsing.
