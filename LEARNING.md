# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
Career change. "I want to learn about Agent development. I already know about API call to OpenAI, Anthropic."

Build goal: "Project for my portfolio, can be some in the final projects list."

## Placement
- Date: 2026-10-26
- Score: 10/10 (Math & Statistics 2/2, Classical ML 2/2, Deep Learning 2/2, NLP & Transformers 2/2, Applied AI 2/2)
- Entry point: Phase 14: Agent Engineering
- Pace: ~2 h/week

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Skip | -- |
| 1 | Math Foundations | Skip | -- |
| 2 | ML Fundamentals | Skip | -- |
| 3 | Deep Learning Core | Skip | -- |
| 4 | Computer Vision | Skip | -- |
| 5 | NLP: Foundations to Advanced | Skip | -- |
| 6 | Speech & Audio | Skip | -- |
| 7 | Transformers Deep Dive | Skip | -- |
| 8 | Generative AI | Skip | -- |
| 9 | Reinforcement Learning | Skip | -- |
| 10 | LLMs from Scratch | Skip | -- |
| 11 | LLM Engineering | Skip | -- |
| 12 | Multimodal AI | Skip | -- |
| 13 | Tools & Protocols | Skip | -- |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Do | 28 |
| 17 | Infrastructure & Production | Do | 34 |
| 18 | Ethics, Safety & Alignment | Do | 31 |
| 19 | Capstone Projects | Do | 620 |

Total for Do phases: ~788 hours. Phase 19 holds all capstone projects. The portfolio goal needs only one of them.

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-10-26 | 14/01 The Agent Loop | 2/2 | Thought the tool_result goes in the system role (it goes in the user role). Read max_turns as a fixed count, not a cap. |
| 2026-10-26 | 14/02 ReWOO and Plan-and-Execute | 2/2 | Found code reading hard, so traced the topological sort with a coffee to-do table. Thought a cyclic plan loops forever (it raises at once). Chose retry over checkpointing for a crash at step 20. |
| 2026-10-26 | 14/03 Reflexion and Verbal RL | 2/2 | Warm-up: missed that #E1 is an evidence reference (chose "planner version"). Wrote delta as 14, not -14 (total minus target). Called a note about a one-off DB outage "memory rot" (root cause: external failure stored as a superstition). Traced both loop runs correctly. |
| 2026-10-26 | 14/04 Tree of Thoughts and LATS | 2/2 | Warm-up: chose HotpotQA as the case where Reflexion does not help (it is a transient external failure). Counted 6 root children, not 24 (missed the loop over 4 ops). Asked if c cancels in UCT (it weights only the explore term). Read value() as steps to 24, not distance of the nearest number. Saw both searches fall into the (24, 4, 1) dead end. |
| 2026-10-27 | 14/05 Self-Refine and CRITIC | 2/2 | Warm-up 2/2. Predicted that the vague self-critique ("double-check capital") would fix the Germany bullet (it does not name the error, so the output stays the same for 4 iters). Traced CRITIC to a pass in 3 iters. Auto mode blocked the code run, so the trace was by hand. |
| 2026-10-27 | 14/06 Tool Use and Function Calling | 1/2 | Warm-up 1/2 (chose "a test that always passes" for the rubber-stamp loop). Did not know state-based evaluation at first, then got the calendar check right. Chose the vague error message over the specific one. Thought int("4.5") coerces to 4 (it raises). Predicted that the invented `subtract` tool returns OK and swapped the two enum calls. Auto mode blocked the code run again. |
| 2026-10-27 | 14/07 Agent Memory: Virtual Context and Memory Paging | 2/2 | Warm-up 2/2. Quiz 2/2. Distinguished Core vs Archival by persistence vs single-task scope. Noted synchronous memory latency/token burden and the role of sleep-time background consolidation. |
| 2026-10-28 | 14/08 Memory Blocks and Sleep-Time Compute | 2/2 | Warm-up 2/2. Quiz 2/2 (first instinct A on native reasoning). Connected sleep-time compute to off-path judgment/pruning and soft-invalidation for auditability/rollback. |
| 2026-10-30 | 14/09 Hybrid Memory: Vector + Graph + KV | 2/2 | Warm-up 2/2. Post-quiz 2/2. Initially grouped short-range time under importance rather than recency decay. Correctly identified graph soft-invalidation to preserve past states, multi-tenant scope isolation, and LLM semantic extraction in production mem0. |
| 2026-10-30 | 14/10 Skill Libraries and Lifelong Learning (Voyager) | 2/2 | Warm-up 2/2. Post-quiz 2/2. Highlighted action-space-as-code for temporal abstraction. Traced failure feedback through iterative prompting and identified composed-skill drift. |
| 2026-11-03 | 14/11 Planning with HTN and Evolutionary Search | 2/2 | Warm-up 2/2. Post-quiz 2/2. Noted precondition enforcement as state invariant check vs missing facts. Identified LLM caching to avoid token/latency overhead and deterministic fitness evaluator requirement for AlphaEvolve. |
| 2026-11-04 | 14/12 Anthropic Workflow Patterns | 2/2 | Warm-up 1/2. Post-quiz 2/2. Highlighted risks of autonomous bias/spontaneous actions vs bounded workflows. Noted programmatic transition gates and bandit best-of-N retention for evaluator-optimizer. |
| 2026-11-09 | 14/13 Stateful Graph Orchestration — Durable Execution and Checkpoints | 2/2 | Warm-up 2/2. Post-quiz 2/2. Highlighted human-in-the-loop pause without live memory retention. Noted raw dict clobbering vs LangGraph reducers and checkpoint scope for durable recovery. |

## Review queue
| Lesson | Missed topic |
|--------|--------------|
| 14/06 Tool Use and Function Calling | The open problems of function calling (memory, dynamic decisions, long chains, hallucination detection). Detection of an invented tool name. |
