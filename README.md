# Wish

A hyperlocal, privacy-first skill exchange and mutual aid platform.

## Overview

**Wish** connects people who want to learn with people who want to teach, and people who need help with people who can offer it. It's built around **monthly recurring meetups** where neighbors help neighbors—no money, no tracking, just community.

---

## Related: Wish (Micro-Volunteering)

**Note:** This project shares a name with [Wish by Praxis.nyc](https://praxis.nyc/wish/), a mutual aid micro-volunteering platform for one-off transactions (e.g., picking up compost, borrowing tools). That version facilitates individual errands with privacy-first matching.

**Key difference:**
- **Praxis Wish:** One-off P2P transactions (pickup compost Tuesday, borrow drill Friday)
- **This Wish:** Recurring communal gatherings (everyone meets 2nd Saturday 10am)

**Why not merge them?**
- **Errands naturally converge to the meetup anyway**
- "I'll bring that jacket since we're both going Saturday"
- "Oh you need compost? I'll bring some to the meetup"
- Monthly gathering = natural coordination point for exchanges
- No need for separate P2P matching system
- **Communal gathering absorbs distributed errands organically**

**What we learn from Praxis Wish:**
- Wish generates a **Map of Needs** (unfulfilled wishes = community gaps)
- Use this to prioritize sessions, recruit helpers, educate demand
- See full analysis below in "Inspiration" section

---

### How It Works

1. **People volunteer** their skills/needs
   - "I want to learn: knitting, debt refinancing, Python"
   - "I can help with: basic computer repair, Spanish tutoring, gardening"

2. **Matchmakers** (community organizers) pair people
   - Match wants with offers
   - Build monthly agenda (same time, same place)
   - Mark sessions as **open** (others can join) or **closed** (1-on-1)

3. **Helper & seeker align** before the meetup
   - "Help me to help you" checklist
   - What do you need prepared? What should I bring?
   - Clear expectations, low friction

4. **People meet, help each other, move on**
   - Monthly recurring (predictable schedule)
   - Hyperlocal (walk/bike distance)
   - Privacy-first (Signal groups, no surveillance)

### Example Agenda

**February Meetup - Saturday 10am @ Community Center**

- **10:00-11:00** - A & B: Knitting basics (open - anyone can join)
- **11:00-12:00** - C & D: Debt refinancing (closed - 1-on-1)
- **12:00-13:00** - E & F: Fix old computer (open)

---

## Principles

- **Privacy-first:** Signal groups, no central database, minimal data
- **Hyperlocal:** Walk/bike distance, same neighborhood
- **Recurring:** Monthly meetups, same time/place (low planning overhead)
- **Mutual aid:** No money, no hustle, just neighbors helping neighbors
- **Consent-based:** Open vs closed sessions, clear boundaries
- **Matchmaker-curated:** Human organizers, not algorithms

---

## Status

🌱 **Ideation** - Exploring concept, no implementation yet

---

## Open Questions

- **Matchmaker tooling:** What do organizers need to build agendas efficiently?
- **Signal vs other:** Is Signal the right platform, or custom chat needed?
- **Scaling:** How many people per meetup? Per matchmaker?
- **Safety:** How to handle bad actors, harassment, no-shows?
- **Onboarding:** How do new people find/join their local chapter?
- **Incentives:** What motivates matchmakers to organize (not just participate)?

---

## Tech Stack

- **Communication:** Signal (private groups)
- **Coordination:** [TBD - spreadsheet? Airtable? Custom tool?]
- **Scheduling:** [TBD - Google Calendar? iCal? Manual?]

---

## Inspiration

- **Mutual aid networks** (community fridges, tool libraries)
- **Skill shares** (time banking without currency)
- **Meetup.com** (but hyperlocal, privacy-first, no corporate tracking)
- **Little Free Libraries** (take a skill, leave a skill)
- **[Praxis Wish](https://praxis.nyc/wish/)** - Micro-volunteering platform for one-off transactions

### What We Learn from Praxis Wish

**Praxis Wish is transactional** (things, not crafts):
- P2P errands: pick up compost, borrow drill, get plant cutting
- Ephemeral: connection forgotten after transaction
- Privacy-first: geofenced, bottom-up taxonomy (#tags)

**Key insight: Wish GENERATES a Map of Needs**
- **Unfulfilled wishes = community gaps**
- "5 people want knitting help, 0 offers" → visible gap
- "8 people need debt refinancing, 1 offer" → demand exceeds supply
- "Nobody wants help with gardening, 3 offer it" → unused capacity

**How this helps matchmakers:**
- See what's missing: "We need someone who can teach X"
- Prioritize high-demand skills for open sessions
- Recruit helpers for unfulfilled needs
- Balance supply/demand over time
- Build community resilience by filling gaps

**In Praxis Wish:** Unfulfilled #needs show what the community lacks (things)  
**In our Wish:** Unfulfilled wants/offers show what skills/help are missing (crafts, care, knowledge)

**Example Map of Needs:**
```
High demand, low supply:
- Debt refinancing (8 want, 1 offer)
- Computer repair (6 want, 2 offer)

Balanced:
- Knitting (3 want, 3 offer)

Low demand, high supply:
- Gardening (0 want, 3 offer) → maybe people don't know they want this?
```

**Matchmakers use this to:**
- Recruit: "We desperately need someone who knows debt refinancing"
- Educate: "Hey, 3 people can help with gardening—anyone interested?"
- Prioritize: "Debt refinancing is open session this month (high demand)"

---

> 🤖
>
> - [README](README.md) - Our project
> - [ROADMAP](backstage/ROADMAP.md) - What we wanna do
>
> 🤖
