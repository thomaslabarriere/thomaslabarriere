### Thomas Labarriere

**I turn what an expert knows into a system that decides.**

A four-time World's Strongest Man's coaching method, encoded as a 50,000-line
deterministic rules engine. A sleep practitioner's protocol, turned into a personalised
programme and a conversational coach. Same requirement both times: the system decides,
the AI explains, never the other way round.

I do not type the code. I design the systems, model the domain, orchestrate agents, and
take everything apart until I know why it holds. Three complete mobile products shipped
alone in six months.

What occupies me next is one step further. An agent that writes the implementation **and**
its test is judge and jury: its green tick proves nothing. I build the instruments that
move the proof outside the agent — invariants measured across a generated population
behind a monotonic ratchet, property-based testing with a fixed replayable seed, detection
of code that is written but never reached, mutation testing.

One rule holds the rest together: *a passing test proves nothing until it has failed for
the right reason.*

---

**[unwired](https://github.com/thomaslabarriere/unwired)** · finds code that is written,
tested, and never actually reached. On my own repository it surfaced a comparison that had
been dead for months, under 10,858 green tests.

**[access-agent-eval](https://github.com/thomaslabarriere/access-agent-eval)** · a
reliability & anomaly evaluation harness for autonomous access-management agents. Verdicts
come from the real state diff, not the agent's prose, and a mutation proof shows the harness
itself catches broken agents.

*Most of my work lives in private repositories, under client agreements, and its commits
are authored by the agents that wrote them. What is public here is what I built to keep
those agents honest.*
