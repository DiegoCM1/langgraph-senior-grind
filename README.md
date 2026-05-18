<!-- List of concepts to explain -->

Focus on Graph API:
    The thing is that Graph API is more explicit. Resembles FastAPI work. If you want to learn, this is the way.

 Tier 1 — Foundations
  1. What LangGraph is & why it exists ✅
  1.1 Mental model for state, nodes and edges, reducers, how they interact.
  2. State schema & reducers ← new, non-negotiable
  3. Nodes, edges, START/END, .compile()
  4. Graph API vs Functional API ← new, short

  Tier 2 — Control flow
  5. Conditional edges & routing
  6. Tool calling & ToolNode — the agent loop ← new
  7. ReAct vs plan-execute

  Tier 3 — Persistence (the spine)
  8. Checkpointing & threads
  9. Time travel / replay ← new
  10. Human-in-the-loop via interrupt()
  11. Long-term memory & the Store

  Tier 4 — Scale & robustness
  12. Streaming modes — values/updates/messages/custom
  13. Parallelism & Send / map-reduce 
  14. Error handling, retries, durability 
  15. Subgraphs ← new
  16. Multi-agent supervisor pattern 

  Tier 5 — Judgment
  17. When NOT to use LangGraph (your #15)