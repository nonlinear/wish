# Wish ROADMAP

*Hyperlocal skill exchange & mutual aid platform*

---

## 🎯 Vision

**Enable neighbors to help neighbors** through monthly recurring skill exchanges and mutual aid meetups. Privacy-first, hyperlocal, human-curated.

**Core loop:**
1. People volunteer skills they offer + help they need
2. Matchmakers pair people, build monthly agenda
3. Helper & seeker align ("help me to help you" checklist)
4. Monthly meetup happens (same time, same place)
5. Repeat next month

**Anti-goals:**
- ❌ No money/currency/time-banking (just mutual aid)
- ❌ No algorithmic matching (human matchmakers)
- ❌ No surveillance capitalism (Signal, not apps that track)
- ❌ No scaling beyond hyperlocal (walk/bike distance)

---

## 🚧 Current Status

**Phase:** Concept definition  
**Next step:** Design matchmaker workflow (how do organizers build agendas?)

---

## 📋 Epics / Milestones

### Phase 1: Concept & Research
- [x] Define core concept (mutual aid skill exchange)
- [ ] Research existing models (time banks, skill shares, mutual aid networks)
- [ ] Identify what makes this different (hyperlocal + recurring + privacy-first)
- [ ] Talk to potential matchmakers (what do they need?)
- [ ] Talk to potential participants (what barriers exist?)

### Phase 2: Matchmaker Tooling (MVP)
- [ ] Design matchmaker workflow
  - How do people submit wants/offers?
  - How do matchmakers pair people?
  - How is agenda published?
  - How do helper & seeker align before meetup?
- [ ] Choose tech stack (spreadsheet? Airtable? Custom?)
- [ ] Build MVP (simplest thing that works)
- [ ] Test with 1 matchmaker + 10 participants

### Phase 3: First Meetup
- [ ] Find venue (community center, library, park)
- [ ] Recruit 1 matchmaker
- [ ] Recruit 10-15 participants
- [ ] Build first agenda (3-5 sessions)
- [ ] Run first meetup
- [ ] Gather feedback, iterate

### Phase 4: Sustainability
- [ ] Document matchmaker playbook
- [ ] Recruit 2nd matchmaker (backup/rotation)
- [ ] Establish recurring schedule (2nd Saturday every month?)
- [ ] Build community norms (code of conduct, conflict resolution)
- [ ] Evaluate: Is this working? Should it continue?

---

## 🔍 Research Questions

**What exists already?**
- Time banks (too currency-like?)
- Skill shares (too one-off?)
- Meetup.com chapters (too corporate, not mutual aid focused)
- Community fridges / tool libraries (physical goods, not skills)
- Mutual aid networks (crisis-focused, not ongoing skill exchange)
- **[Praxis Wish](https://praxis.nyc/wish/)** - Micro-volunteering for one-off transactions (compost pickup, tool lending)

**What's unique here?**
- **Recurring communal gatherings** (not one-off errands like Praxis Wish)
- Everyone meets same time/place (not distributed transactions)
- **Recurring:** Monthly, same time/place (low overhead)
- **Hyperlocal:** Walk/bike distance only
- **Privacy-first:** Signal, no central surveillance
- **Human-curated:** Matchmakers, not algorithms
- **Mutual aid frame:** Not transactional, just neighbors helping

**Comparison: This Wish vs Praxis Wish**

| Feature | This Wish | Praxis Wish |
|---------|-----------|-------------|
| **Model** | Communal gathering | Distributed errands |
| **Cadence** | Monthly recurring | One-off transactions |
| **Format** | Everyone meets same time/place | Private 1-on-1 pickups |
| **Use case** | Learn knitting, fix computer | Pick up compost, borrow drill |
| **Community** | Builds over time (same faces) | Ephemeral (forget after) |
| **Scale** | 10-50 people per meetup | P2P matching (unlimited) |

**Could we merge them?**
- **Probably unnecessary** - errands will naturally converge to the meetup
- "I'll bring that jacket since we're both going anyway"
- "Oh you need compost? I'll bring some on Saturday"
- Monthly meetup = natural coordination point for P2P transactions
- No need for separate errand-matching system
- **Communal gathering absorbs distributed errands organically**

**What Praxis Wish teaches us:** The platform GENERATES a Map of Needs
  - **Unfulfilled wishes = community gaps**
  - "5 want knitting, 0 offer" → visible gap, recruit someone
  - "8 need debt help, 1 offer" → demand exceeds supply, prioritize
  - "0 want gardening, 3 offer" → unused capacity, educate demand
  - Matchmakers use unfulfilled wishes to prioritize sessions & recruit helpers
  - Community becomes self-aware of its own needs through aggregation

**Emergent behavior:**
- People will naturally bring things to exchange at meetups
- "I heard you need X, I'll bring it Saturday"
- Errands piggyback on existing gathering (no extra coordination needed)
- Community becomes hybrid: planned sessions + organic exchanges

**Who are the matchmakers?**
- Community organizers
- People who like facilitating (not just participating)
- Need lightweight tooling (can't be a full-time job)

**What tools do matchmakers need?**
- Collect wants/offers (Google Form? Signal poll?)
- Pair people (spreadsheet? Notion? Custom tool?)
- Publish agenda (shared calendar? PDF? Signal post?)
- Facilitate "help me to help you" alignment (template?)

---

## 🛠️ Design Decisions

### Communication Platform: Signal
**Why:**
- ✅ Privacy-first (E2E encrypted)
- ✅ Everyone already has it (or can get it)
- ✅ Group chat = natural fit for coordination
- ✅ No corporate tracking

**Trade-offs:**
- ❌ Not great for scheduling/agenda (need separate tool)
- ❌ Discovery harder (can't browse, need invite link)

### Matchmaker Role: Human-Curated
**Why:**
- ✅ Context matters (know the community, spot good matches)
- ✅ Algorithms optimize for engagement, not mutual aid
- ✅ Builds trust (people know who's organizing)

**Trade-offs:**
- ❌ Doesn't scale beyond ~50 people per matchmaker
- ❌ Requires community organizers (not everyone wants to do this)

### Meetup Cadence: Monthly Recurring
**Why:**
- ✅ Predictable (low planning overhead)
- ✅ Not too frequent (burnout)
- ✅ Not too rare (momentum)

**Trade-offs:**
- ❌ Some urgent needs can't wait a month
- ❌ Some people can't commit monthly

---

## 💡 Ideas / Backlog

- **"Help me to help you" template:** Pre-meetup alignment form
- **Session types:** Open (anyone can join) vs Closed (1-on-1)
- **Skill tags:** Standardized categories for easier matching
- **No-show policy:** How to handle flakes without being punitive?
- **Safety:** Code of conduct, conflict resolution, reporting
- **Growth:** When does a chapter split into two (size limit)?
- **Async help:** Not everything needs in-person (some can be Signal/Zoom)
- **Library integration:** Partner with local libraries for venue/promotion

---

## 🌍 Example Use Cases

**A wants to learn knitting, B offers knitting help:**
- Matchmaker pairs them
- B asks A: "Do you have yarn/needles, or should I bring extras?"
- Session marked "open" → anyone can join
- Monthly meetup: 10-11am, B teaches A (and anyone else) basic stitches

**C needs debt refinancing help, D offers financial literacy:**
- Matchmaker pairs them
- D asks C: "What debts do you have? Bring statements if comfortable"
- Session marked "closed" (privacy)
- Monthly meetup: 11am-12pm, D walks C through refinancing options

**E has broken computer, F offers basic repair:**
- Matchmaker pairs them
- F asks E: "What's broken? Bring the computer"
- Session marked "open" → maybe G also has computer issues
- Monthly meetup: 12-1pm, F diagnoses + fixes with E (and G)

---

---

## v0.19.0

### Community Organizing (Resilience Networks) 🏴

**Status:** 💡 CONCEPT (from life project)

**Goal:** Build resilient community infrastructure (mesh networks, mutual aid, off-grid communication)

**Philosophy:** "O jogo é criar maneiras de sermos mais resilientes"

**Tasks:**
- [x] Examine Meshtastic (https://themultiverse.school/x/cyberpony#about)
- [ ] Home Meshtastic node (ESP32 + LoRa, base station)
- [ ] Test with 2-3 neighbors (pilot network)
- [ ] Skill inventory (what I offer, what I need)
- [ ] Tool/resource sharing system
- [ ] Self-hosted community services (Matrix, maps, directory)
- [ ] Off-grid power backup (solar + battery)

**Success Criteria:**
- Meshtastic node running 24/7 (no internet/cell needed)
- 2-3 neighbor nodes tested (messaging works)
- Emergency coordination plan documented
- Community services self-hosted

**Details:** [v0.19.0-community-organizing.md](../life/backstage/epic-notes/v0.19.0-community-organizing.md)

---

## 📝 Notes

- **Created:** 2026-02-03
- **Status:** Ideation
- **Inspiration:** Mutual aid, time banks, skill shares, community fridges
- **Anti-inspiration:** Algorithmic matching, surveillance apps, hustle culture
