# Make Me! Recruiter Outreach Engine

**Make Me! Recruiter Outreach Engine** is a planned AI-assisted messaging tool that will help users communicate with recruiters, hiring managers, referrals, and networking contacts.

Part of the **Make Me!** career tools suite - built by a Senior Technical Program Manager to solve real job search problems with practical AI-assisted workflows.

Good outreach is specific, concise, and human. This engine will help users get there faster.

![Make Me! Recruiter Outreach Engine](Screenshot.png)

---

## What This Will Demonstrate

- A planned workflow for proactive job-search communication
- AI-assisted outreach drafting based on role, company, contact, and user positioning
- Message variants for recruiters, hiring managers, referrals, and networking contacts
- Follow-up sequencing support without automatic sending
- Clear separation between general outreach and application-specific follow-ups
- A communication engine connected to the broader Make Me positioning system

---

## The Problem

Many job seekers know they should reach out, but the first message is often the hardest part. They worry about sounding generic, too pushy, too formal, or unclear about what they want.

Recruiter and networking outreach also changes by context. A cold recruiter message is different from a referral ask. A hiring manager note is different from a follow-up. Users need language that fits the relationship, role, and moment.

---

## The Planned Solution

The Recruiter Outreach Engine is planned to support proactive job-search communication:

1. Capture target role, target company, contact context, user profile, resume summary, and desired tone
2. Identify the outreach scenario and relationship type
3. Generate concise message options for the channel and audience
4. Create warm and cold variants where useful
5. Support follow-up sequencing and re-engagement drafts
6. Keep messages user-reviewed and manually sent

General proactive outreach belongs here. Application-specific follow-ups tied to a tracked job application belong in the Application Engine.

---

## Design Constraints (Intentional)

- Planned engine; not active in the current prototype suite
- Designed for message drafting, not automated sending
- Intended to preserve user control over outreach
- Planned to support context-specific messaging instead of generic templates
- Built around the user's positioning from the broader Make Me suite

---

## Planned Capabilities

### Outreach Context

- Target role
- Target company
- Recruiter or hiring manager name when available
- User profile
- Resume summary
- Desired tone
- Outreach context and relationship type

### Message Generation

- Cold recruiter outreach
- Recruiter replies
- Referral asks
- Networking messages
- LinkedIn connection messages
- Hiring manager outreach
- Re-engagement messages

### Follow-Up Support

- Follow-up sequences
- Short and long message versions
- Warm and cold outreach variants
- Channel-specific phrasing
- Professional tone options

### Suite Alignment

- Messaging tied to user positioning
- Resume summary reuse
- LinkedIn profile alignment
- Clear distinction from application-specific follow-ups

---

## Planned Architecture

```text
User Browser
  |
  v
Recruiter Outreach Workflow (planned)
  |
  +--> Role, company, contact, and tone intake
  |
  +--> User profile and resume-summary context
  |
  +--> Outreach message-generation workflow
  |       |
  |       v
  |   Runtime-selected AI provider/model
  |
  v
Recruiter messages, referral asks, follow-ups, and outreach variants
```

The planned engine is expected to reuse resume positioning and LinkedIn context so outreach messages feel specific to the user instead of generic.

---

## Setup

This engine is planned and is not yet active as a standalone workflow. Setup instructions will be added when the engine is implemented.

---

## Known Limitations

- The engine is planned and not currently implemented.
- Current documentation describes intended product scope, not active functionality.
- The engine will not send messages automatically.
- Generated outreach should be reviewed and personalized before sending.
- Contact quality and context will strongly affect message quality.

---

## Tech Stack

Planned to align with the existing Make Me prototype stack:

- Vanilla HTML / CSS / JavaScript
- Browser `localStorage`
- Runtime AI provider/API key input
- No backend in the initial prototype unless the suite architecture changes

---

## Roadmap

- Define the recruiter outreach specification
- Build outreach context intake
- Add message variants by relationship and channel
- Support follow-up sequencing
- Connect outreach to resume and LinkedIn positioning
- Add saved message history and reusable templates

---

## Part of the Make Me! Suite

| Engine | Tool | Purpose |
|--------|------|---------|
| Engine 1 | **Make Me! Resume Positioning Engine** | Build a strategically positioned resume from raw career history |
| Engine 2 | **Make Me! Application Engine** | Analyze job postings, tailor application materials, generate cover letters, and track applications |
| Engine 3 | **Make Me! LinkedIn Optimization Engine** | Optimize LinkedIn profiles for recruiter searchability and credibility |
| Engine 4 | **Make Me! Interview Prep Engine** | Planned engine for interview questions, STAR stories, and role-specific prep |
| Engine 5 | **Make Me! Salary Negotiation Engine** | Planned engine for compensation strategy, counteroffers, and negotiation messaging |
| Engine 6 | **Make Me! Recruiter Outreach Engine** | Planned engine for recruiter, referral, and networking outreach |

---

## Why This Exists

Opportunities often start with a short message. The difference between a generic note and a useful one is context: who the user is, what they are targeting, why the contact is relevant, and what the user is asking for.

This engine exists to make proactive outreach less awkward and more intentional. It will help users communicate their value clearly while keeping the message human, brief, and appropriate to the relationship.

- **Outreach design** - shapes messages around audience, context, and relationship
- **AI as interpreter** - planned model output will adapt positioning into concise communication
- **Workflow thinking** - cold outreach, replies, referrals, follow-ups, and variants in one flow
- **Constraint-driven architecture** - planned to follow the suite's browser-first, local-first pattern

---

## License

MIT — use it, fork it, adapt it.

---

*Built by Jonathan Madden*
*[LinkedIn](https://linkedin.com/in/jonathan-p-madden) - [github.com/Jon-P-Madden](https://github.com/Jon-P-Madden)*
