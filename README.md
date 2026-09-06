### Devdatta Talele - Database internals and AI infrastructure. Mumbai.

#### Building: [plnt](https://github.com/devdattatalele/plnt) · [plnt.work](https://plnt.work)

A local-first micro-agents runtime. One resident planner LLM receives intents and spawns short-lived,
sandboxed micro-agents to do the work. Each agent gets exactly two
tools, search and execute; everything else it needs lives on the
filesystem and is reached through them. Sandboxing is a ladder
(process, docker, microVM) so you pay isolation cost only when the
threat model demands it. Every observable event is one line in a
per-run JSONL audit log: if cat and grep cannot see it, it does not
exist as state. Memory is plain files, no database, no vendor SDK,
no cloud lock-in. Ollama by default, any OpenAI-compatible backend
as fallback.

#### Also built

- [GIS](https://github.com/devdattatalele/GIS): CLI agent that resolves GitHub issues
  end to end, RAG knowledge base over the repo, patch generation, PR creation
- [browserstack-agent-edge-cases](https://github.com/devdattatalele/browserstack-agent-edge-cases):
  three reproducible production failure modes for browser agents

taleledevdatta@gmail.com · [linkedin.com/in/devdattatalele](https://www.linkedin.com/in/devdattatalele)
