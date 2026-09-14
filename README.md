# Thomas Labarriere

**AI Engineer.** I build LLM agents, and the instruments that prove they hold up.

An agent that writes the code and its own test is judge and jury, so its green tick proves nothing. My work moves the proof outside the agent: ground-truth eval sets, objective guardrails, an LLM-as-a-judge validated against gold labels, and mutation testing. One rule holds the rest together: a passing test proves nothing until it has failed for the right reason.

### What I've built (open, and meant to be opened)

* **[access-agent-eval](https://github.com/thomaslabarriere/access-agent-eval)** reliability harness for autonomous access-management agents. The verdict comes from the real state diff, not the agent's prose (a "done" that changed nothing is caught), and a mutation proof shows the harness itself catches broken agents.
* **[contract-gap-eval](https://github.com/thomaslabarriere/contract-gap-eval)** a contract-vs-policy gap agent with gap-recall by severity. It measures the missed non-compliant clauses a legal team can't afford (the false negative), plus an objective citation-hallucination guard.
* **[kb-reliability](https://github.com/thomaslabarriere/kb-reliability)** customer-support RAG diagnosed by layer (retrieval, groundedness, freshness) with a calibrated LLM-as-judge. It flags a wrong answer even when retrieval and groundedness both look perfect.
* **[legal-cite-eval](https://github.com/thomaslabarriere/legal-cite-eval)** citation reliability for legal agents, with an LLM-as-a-judge validated against a gold set (who judges the judge?).
* **[med-code-eval](https://github.com/thomaslabarriere/med-code-eval)** a medical-coding harness that catches upcoding (severity inflated for reimbursement) and PHI leaks, not just wrong codes.
* **[ops-agent](https://github.com/thomaslabarriere/ops-agent)** an autonomous ops agent scored on task success and guardrail safety (an agent can be safe but useless, or helpful but dangerous), with prompt-injection and self-healing tests.
* **[unwired](https://github.com/thomaslabarriere/unwired)** finds code that is written, tested, and never actually reached. On my own repo it surfaced a comparison dead for months under 10,858 green tests.

*Each harness ships with a synthetic gold set and mutation-proof tests. The numbers are on those sets; plug in real data for real numbers.*

### Shipped (under NDA)

AI-native builder: I orchestrate coding agents while owning the architecture, security and quality. Two production apps: a RAG coaching assistant going live, and a deterministic decision engine backed by a cohort-based evaluation setup.

### Tech Stack

`Python` · `TypeScript` · `LLM Agents` · `RAG` · `AI Evaluation` · `Testing`

📍 Paris / Bordeaux (open to remote). Open to AI Engineering roles where reliability isn't optional.
