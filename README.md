# Clear to Ship

**IBM Bob 2.0 Hackathon · Jason Parser Research · Sep 25–27, 2026**

> The release bouncer. Four specialist agents tear the diff apart in IBM Bob IDE. You get one page: **GO / NO-GO**, ranked risks, and the fixes.

## Why
Pre-release reviews burn 2–4 hours, get skipped under pressure, and still miss authz holes and broken deps. Engineers either ship scared or stall for days.

## How (Bob IDE is the engine)
1. Point Clear to Ship at a release candidate (diff, deps, tests, policies)
2. **Parallel Bob subagents**: security · dependencies · tests · rollback
3. **Agent-mode synthesizer** → clearance memo + patches
4. `bob_sessions/` evidence of real Bob usage

## Demo metrics
- Review time **~2h → 15 min**
- Seeded critical findings **caught**
- Manual checklist steps **12 → 2**

## Links
- Event: https://lablab.ai/ai-hackathons/ibm-bob-2-hackathon
- Team: https://lablab.ai/ai-hackathons/ibm-bob-2-hackathon/jason-parser-research
- Bob IDE: https://bob.ibm.com/download
