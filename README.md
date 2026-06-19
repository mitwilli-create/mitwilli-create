# Mitchell Williams

**AI Agent Builder & Comms Lead.** Production LLM pipelines, built where reliability isn't optional.

> *A producer's discipline, applied to systems. Same job, different substrate.*

For a decade I ran toward the hard live moments in network newsrooms: breaking-news control rooms at Al Jazeera English (*The Stream*), Fusion, AJ+, and HuffPost Live. The system has to hold under deadline. Judgment happens at speed. Zero tolerance for drift. I build AI the same way: agents that work on the first take, for an audience that would know the instant they didn't.

## Inspectable architecture

Real, running systems. Clone them, read the prompt chains, see the design decisions:

- **[comms-triage-agent](https://github.com/mitwilli-create/comms-triage-agent):** autonomous triage → revision → escalation for internal-comms intake across a large engineering organization (Principal/Distinguished/Fellow IC tier, ~1,000 engineers). Three-prompt architecture with conditional knowledge-base loading; ~160 operational hours/year recaptured. Apps Script + Gemini.
- **[voice-os](https://github.com/mitwilli-create/voice-os):** six-axis voice scoring, dual-persona routing, and QA gates calibrated on a multi-million-word corpus. The "Voice DNA" approach: a curated corpus plus a banned-phrase checklist of rejected drafts teaches an agent risk tolerance and rhetorical pace. Built on Claude.
- **[tax-verification-agent](https://github.com/mitwilli-create/tax-verification-agent):** citation-gated verification over a four-layer knowledge base. Caught a real multi-state income-tax error that filing software defended as correct.

At the Office of Engineering Strategy (OES), inside a large engineering organization, I shipped **two** production LLM agents into that senior-IC org: the comms-triage agent above and an executive "Voice DNA" RAG pipeline. I also run a private, forked-and-extended agentic pipeline (career-ops) that drives my own job search end to end.

## Why the newsroom matters

A live broadcast control room is a high-availability system staffed by humans: redundant feeds, real-time failover, an editor making irreversible publish decisions in seconds. The instincts port straight over: observability, graceful degradation, judgment under load, and a refusal to ship anything that drifts. That decade at Al Jazeera, Fusion, and *The Stream* is the origin of how I think about agent reliability, not a detour from it.

## Background

Journalist → communications & content strategist → builder. Network newsrooms (AJ+, HuffPost Live, Fusion, Al Jazeera English) → comms + applied AI at the Office of Engineering Strategy (OES), inside a large engineering organization.
