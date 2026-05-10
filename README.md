# 12-Week AI Agents Course: From Scratch to Robust, Ethical Autonomous Systems

This 12-week self-paced course addresses key structural gaps through a first-principles lens: building mathematical intuition early, embedding debugging and failure-mode handling, integrating security/ethics, expanding real-world deployment, and adding structured checkpoints for cumulative review. It remains beginner-friendly (no prior AI/ML knowledge required) and fits within 12 weeks by interleaving fixes without overload. The upgraded flow ensures progressive depth: foundations with math grounding, core building with debugging, advanced techniques, evaluation/ethics, multi-agent ops, and polished projects. Throughout, the curriculum traces the full arc of modern AI development — from vibe coding (LLM-assisted, intuition-driven) to vibe engineering (structured AI-assisted workflows) to agentic engineering (humans as orchestrators of AI agent teams) — so you understand not just how to build agents, but why the field evolved to demand it.

→ **[Start with Week 0 (optional math)](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs)** · **[Jump to Week 1](#week-1-ai--llm-basics--math-integration)** · **[Key Guidelines](#key-guidelines)** · **[Background: Vibe Coding → Agentic Engineering](#background-from-vibe-coding-to-agentic-engineering-optional-recommended)**

---

## Who Is This For?

| Track | Background | Entry Point |
|-------|-----------|-------------|
| **Complete Beginner** | No ML/AI experience; new to Python | Start at [Week 0](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs) for math grounding, then proceed linearly |
| **Intermediate Coder** | Comfortable with Python; built basic apps but new to AI | Skip Week 0; start at [Week 1](#week-1-ai--llm-basics--math-integration) and use [supplemental repos](#supplemental-reference-repositories) for depth |
| **Agent-Curious Builder** | Already using LLMs/ChatGPT; want to build autonomous agents | Read [Background](#background-from-vibe-coding-to-agentic-engineering-optional-recommended) first, then jump to [Week 3](#week-3-agentic-ai-intro--basics) |

---

## Quick 12-Week Overview

| Week | Focus | Ship |
|------|-------|------|
| [0](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs) | Math Foundations *(optional)* | Cosine similarity by hand |
| [1](#week-1-ai--llm-basics--math-integration) | AI & LLM Basics | Chain-of-thought prompt evaluations |
| [2](#week-2-llm-fundamentals--embeddings-intuition) | LLM Fundamentals + Embeddings | Prompt fine-tuning with similarity metrics |
| [3](#week-3-agentic-ai-intro--basics) | Agentic AI Intro | Tool-calling agent (weather checker) |
| [4](#week-4-building-basic-agents--debugging-checkpoint) | Basic Agents + Debugging | Calculator agent with injected failures |
| [5](#week-5-advanced-agent-tools) | Advanced Tools (MCP) | Week 4 agent + MCP integration |
| [6](#week-6-retrieval--memory) | Retrieval & Memory (RAG) | RAG Q&A agent with hallucination fix |
| [7](#week-7-agent-evaluation--ethicssafety) | Evaluation + Ethics/Safety | Adversarially hardened agent |
| [8](#week-8-browser--specialized-agents) | Browser & Specialized Agents | Browser agent with safety checks |
| [9](#week-9-multi-agent-systems) | Multi-Agent Systems | Multi-agent debate system |
| [10](#week-10-ops--optimization--checkpoint) | Ops & Optimization | Production agent with cost monitoring |
| [11](#week-11-projects--repos) | Projects & Repos | Full RAG + multi-agent integration |
| [12](#week-12-synthesis-deep-dive--portfolio-polish) | Synthesis & Portfolio | Capstone ethical agent app + portfolio |

---

## 🎓 Primary Reference: AI Engineering from Scratch

This curriculum has been updated to align with **[AI Engineering from Scratch](https://aiengineeringfromscratch.com/)** — a comprehensive 20-phase, 416-lesson open-source course. The source course provides deep, first-principles coverage of every topic in this 12-week program.

> **Source Course**: [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) · 416 lessons · 20 phases · ~320 hours · MIT License

### How to Use Both

- This 12-week course provides a focused, accelerated path for agent engineering
- The source course offers deeper exploration with runnable code in Python, TypeScript, Rust, and Julia
- For each week below, relevant lessons from the source course are referenced
- Clone the source repo for hands-on code: `git clone https://github.com/rohitg00/ai-engineering-from-scratch.git`

### Week-to-Phase Mapping

| Week | Focus | Source Course Phases |
|------|-------|---------------------|
| 0 | Math Foundations *(optional)* | [Phase 1: Math Foundations](phases/01-math-foundations/) - 22 lessons covering linear algebra, probability, and statistics
| 1 | AI & LLM Basics | [Phase 2: ML Fundamentals](phases/02-ml-fundamentals/), [Phase 10: LLMs from Scratch](phases/10-llms-from-scratch/) - intro to ML + building LLMs from scratch
| 2 | LLM Fundamentals + Embeddings | [Phase 5: NLP Foundations to Advanced](phases/05-nlp-foundations-to-advanced/), [Phase 11: LLM Engineering](phases/11-llm-engineering/) - embeddings, prompt engineering, RAG basics
| 3 | Agentic AI Intro & Basics | [Phase 14: Agent Engineering](phases/14-agent-engineering/) - the agent loop, tool use, function calling
| 4 | Basic Agents + Debugging | [Phase 14: Agent Engineering](phases/14-agent-engineering/) - debugging, reflexion, self-critique
| 5 | Advanced Agent Tools | [Phase 13: Tools & Protocols](phases/13-tools-and-protocols/) - MCP fundamentals, building MCP servers/clients
| 6 | Retrieval & Memory | [Phase 11: LLM Engineering](phases/11-llm-engineering/) - RAG (06, 07), context engineering, embeddings
| 7 | Evaluation + Ethics/Safety | [Phase 18: Ethics, Safety, Alignment](phases/18-ethics-safety-alignment/) - safety evaluation, alignment, red teaming
| 8 | Browser & Specialized Agents | [Phase 14: Agent Engineering](phases/14-agent-engineering/), [Phase 15: Autonomous Systems](phases/15-autonomous-systems/) - computer use, browser agents
| 9 | Multi-Agent Systems | [Phase 16: Multi-Agent & Swarms](phases/16-multi-agent-and-swarms/) - supervisor patterns, hierarchical architecture, debate
| 10 | Ops & Optimization | [Phase 17: Infrastructure & Production](phases/17-infrastructure-and-production/) - observability, caching, quantization, latency
| 11 | Projects & Repos | [Phase 19: Capstone Projects](phases/19-capstone-projects/) - full-stack agent projects
| 12 | Synthesis & Portfolio | All phases - synthesize everything learned

---

## YouTube Channel Resources

Curated YouTube channels to supplement your learning throughout the 12 weeks. Links verified as of April 2026.

| Channel | Description | Best Week(s) |
|---------|-------------|--------------|
| **3Blue1Brown** | Visual math & ML | [Week 0](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs) |
| **StatQuest (Josh Starmer)** | Statistics & ML basics | [Week 0](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs) |
| **MIT OpenCourseWare** | Academic AI courses | [Week 0](#week-0-optional-math-for-ai-agents-crash-kit-2-3-hrs) |
| **Andrej Karpathy** | Neural networks & LLMs | [Week 1](#week-1-ai--llm-basics--math-integration), [Week 2](#week-2-llm-fundamentals--embeddings-intuition) |
| **DeepLearning.AI** | Deep learning courses (Andrew Ng) | [Week 1](#week-1-ai--llm-basics--math-integration), [Week 2](#week-2-llm-fundamentals--embeddings-intuition) |
| **sentdex** | Practical ML projects | [Week 1](#week-1-ai--llm-basics--math-integration), [Week 2](#week-2-llm-fundamentals--embeddings-intuition) |
| **Siraj Raval** | AI overviews | [Week 1](#week-1-ai--llm-basics--math-integration) |
| **Yannic Kilcher** | Research paper breakdowns | [Week 2](#week-2-llm-fundamentals--embeddings-intuition), [Week 7](#week-7-agent-evaluation--ethicssafety) |
| **Umar Jamil** | Transformer implementations | [Week 2](#week-2-llm-fundamentals--embeddings-intuition), [Week 3](#week-3-agentic-ai-intro--basics) |
| **Two Minute Papers** | AI research updates | [Week 2](#week-2-llm-fundamentals--embeddings-intuition), [Week 7](#week-7-agent-evaluation--ethicssafety) |
| **Stanford Online** | University AI lectures | Throughout ( Weeks 1-12) |
| **Hugging Face** | NLP & LLM tools | [Week 3](#week-3-agentic-ai-intro--basics), [Week 5](#week-5-advanced-agent-tools), [Week 11](#week-11-projects--repos) |
| **Lex Fridman** | AI interviews | Throughout ( Weeks 1-12) |
| **Steve Brunton** | Scientific ML | [Week 6](#week-6-retrieval--memory) |
| **Michael Bronstein** | Graph deep learning | [Week 9](#week-9-multi-agent-systems) |
| **GDLCaltech** | Advanced ML lectures (CS 156) | [Week 10](#week-10-ops--optimization--checkpoint) |

---

## Key Guidelines

- **Time Commitment**: 6-8 hours/week (videos/guides 2-3 hrs, courses/hands-on 3-4 hrs, review 1 hr). Week 0 is optional (2-3 hrs total).
- **Tools Needed**: Free accounts on YouTube, Hugging Face, DeepLearning.AI (free audits available), GitHub, Khan Academy. Use AI (e.g., Grok) for clarifications, code fixes, or ethical scenario simulations.
- **Prerequisites**: Basic computer skills; if new to Python, add [freeCodeCamp's Python for Everybody](https://www.youtube.com/watch?v=8DvywoWv6fI) (first 2 hrs) before starting.
- **Hands-On Focus**: Weekly mini-projects build a GitHub portfolio. Checkpoints in Weeks 4 and 10 refactor prior work.
- **All Resources**: From the original list (links verified as of September 14, 2025) plus targeted additions for gaps. Total keeps ~90% original coverage.

---

## Background: From Vibe Coding to Agentic Engineering *(Optional, Recommended)*

Understanding how AI-assisted development evolved — from free-form LLM prompting to disciplined agent orchestration — gives you the "why" behind this curriculum's structure. The arc took roughly two years.

### The Evolution

| Era | Coined | What it means | What drove the next step |
|-----|--------|---------------|--------------------------|
| **Vibe Coding** | Feb 2025 · Andrej Karpathy | Describe intent to an LLM; accept generated code with minimal review; *"fully give in to the vibes."* Karpathy: *"the hottest new programming language is English."* | Works for toy projects; unsafe for production. No structure, no oversight, code quality unknowable. |
| **Vibe Engineering** | Mid 2025 | Keep the intuitive, high-level flow of vibe coding but embed it in a structured engineering process — architecture, code review, testing. | Still human-centric: one AI assistant + one developer. Doesn't scale to complex, multi-step, or multi-agent tasks. |
| **Agentic Engineering** | Feb 2026 · Andrej Karpathy | Humans as **orchestrators** of AI agent teams — not coders. Agents plan, write, test, and deploy under human oversight. Emphasizes architecture, security, and auditability. | *(Current frontier)* |

### Suggested Reading Order *(~3–4 hrs total, fully optional)*

**1. Baseline — what vibe coding actually felt like**
- [Wikipedia: Vibe Coding](https://en.wikipedia.org/wiki/Vibe_coding) *(15 min)* — Concise definition; ties directly to Karpathy's Feb 2, 2025 X post and the phrase "forget that the code even exists."

**2. The intermediate step — adding discipline**
- [Simon Willison: Vibe Engineering](https://simonwillison.net/2025/Oct/7/vibe-engineering/) *(15 min)* — How "fast and loose" AI-assisted building evolved to need structure and rigor.
- [SmarterArticles: Vibe Engineering — Intuition Meets Discipline](https://smarterarticles.co.uk/vibe-engineering-when-intuition-meets-discipline-in-software-development) *(20 min)* — Why it's a distinct practice, not just "vibe coding + code review."
- [Wopee: Vibe Coding, Vibe Testing, and Vibe Engineering](https://wopee.io/blog/vibe-testing-coding-engineering/) *(20 min)* — The full "vibe movement" across coding, testing, and deployment as a team-level practice.

**3. The full arc — into agentic engineering**
- [Taskade: What Is Agentic Engineering? Complete History](https://www.taskade.com/blog/what-is-agentic-engineering) *(30 min)* — Cleanest timeline: Turing (1950) → deep learning (2012) → Transformers (2017) → AutoGPT (2023) → MCP (2024) → vibe coding (2025) → agentic engineering (2026). Also covers the standards war (AAIF, MCP).
- [IBM Think: What is Agentic Engineering?](https://www.ibm.com/think/topics/agentic-engineering) *(15 min)* — Enterprise framing; contrasts vibe coding with agentic engineering and explains why industry needed a more disciplined term.

**4. The mindset shift — humans as orchestrators**
- [Addy Osmani: Agentic Engineering](https://addyosmani.com/blog/agentic-engineering/) *(30 min)* — Opens with Karpathy's "gleefully reckless" vibe coding (prompt, accept everything, paste errors), then contrasts it with a disciplined agentic approach. **Best single read.**
- [iS2 Digital: From Vibe Coding to Agentic Engineering](https://www.is2digital.com/insights/vibe-coding-agentic-engineering) *(20 min)* — Traces the Feb 2025 → Feb 2026 rebranding; covers security implications as you move from single assistant to orchestrated agent teams.
- [Towards AI: Agentic Engineering — Humans as Orchestrators, not Coders](https://pub.towardsai.net/agentic-engineering-humans-as-orchestrators-not-coders-601d015d9c9e) *(20 min)* — Reflects critically on whether to take Karpathy's terminology seriously and what orchestrating agents means in practice.

**5. Applied and academic perspectives**
- [Algorand: From Vibe Coding to Agentic Engineering (Security)](https://algorand.co/blog/from-vibe-coding-to-agentic-engineering-security-for-ai-assisted-blockchain-development) *(20 min)* — Same vibe → agentic contrast applied to a security-critical blockchain context; useful companion to Week 7.
- [arXiv 2505.19443: Vibe Coding vs. Agentic Coding — Fundamentals](https://arxiv.org/abs/2505.19443) *(30 min)* — Structured academic comparison of autonomy levels, architecture roles, and developer posture. Cite-worthy for essays or talks.

> **Why this matters for the curriculum:** Weeks 1–2 are LLM fundamentals (the foundation of vibe coding). Weeks 3–5 introduce agent tools (the vibe engineering layer). Weeks 6–12 build toward full agentic engineering — RAG, evaluation, multi-agent orchestration, ops, and ethics.

---

## Week 0: Optional Math for AI Agents Crash Kit (2-3 hrs)

Build intuition for probability (e.g., LLM predictions), embeddings (vector representations), and metrics (e.g., cosine similarity for similarity). Essential for reasoning about "why" agents work/fail.

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [01-linear-algebra-intuition](phases/01-math-foundations/01-linear-algebra-intuition/) - vectors, linear combinations
> - [02-linear-algebra-operations](phases/01-math-foundations/02-linear-algebra-operations/) - matrix ops, determinants
> - [03-eigen-decomposition](phases/01-math-foundations/03-eigen-decomposition/) - eigenvalues, eigenvectors

| Focus            | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Math Intuition** | - Videos: [3Blue1Brown Essence of Linear Algebra (Chapters 1-3: Vectors, Linear Combinations, Matrices)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) (1 hr)<br>- Videos: [Khan Academy Probability Basics (Intro to Probability, Random Variables)](https://www.khanacademy.org/math/statistics-probability/probability-library) (45 min)<br>- Guide: [3Blue1Brown Neural Networks Playlist (Chapter on Embeddings/Cosine Similarity)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) (45 min)<br>- Repo: [Machine Learning for Beginners (Microsoft)](https://github.com/microsoft/ML-For-Beginners) — 12-week structured curriculum with labs covering classical ML models; skim Week 1 intro for ML context (30 min) | Grasp vectors as "AI's language," probability for uncertainty, embeddings for meaning. Mini-project: Calculate cosine similarity by hand for two sentences using AI-generated vectors. | 2-3 hrs |

## Week 1: AI & LLM Basics + Math Integration

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [Phase 2: ML Fundamentals](phases/02-ml-fundamentals/) - supervised/unsupervised learning, training dynamics
> - [01-intro-to-llms](phases/10-llms-from-scratch/01-intro-to-llms/) - what is an LLM, tokenizer, embeddings
> - [02-tokenization](phases/10-llms-from-scratch/02-tokenization/) - byte-pair encoding, wordpiece, sentencepiece

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **AI & LLM Basics + Math Integration** | - Video: [LLM Introduction](https://www.youtube.com/watch?v=zjkBMFhNj_g) (30 min)<br>- Guide: [OpenAI's Practical Guide to Building Agents](https://github.com/HeyNina101/ai-agent-starter-kit/tree/main/expert-guides) (intro, 1 hr)<br>- Paper: [Chain-of-Thought Prompting](https://arxiv.org/pdf/2201.11903) (skim with Week 0 math, 30 min)<br>- Repo: [LLM Course](https://github.com/mlabonne/llm-course) — practical LLM learning path covering local LLMs and RAG pipelines (browse overview, 30 min)<br>- Integration: Review Week 0 probability for prompt "uncertainty." | Understand LLMs as probabilistic predictors. Mini-project: 5 chain-of-thought prompts; evaluate with basic metrics (e.g., accuracy via cosine sim). | 5-6 hrs |

## Week 2: LLM Fundamentals + Embeddings Intuition

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [04-embeddings](phases/11-llm-engineering/04-embeddings/) - word2vec, BERT, cosine similarity
> - [01-prompt-engineering](phases/11-llm-engineering/01-prompt-engineering/) - zero-shot, few-shot, chain-of-thought
> - [02-few-shot-cot](phases/11-llm-engineering/02-few-shot-cot/) - structured outputs, JSON mode

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **LLM Fundamentals + Embeddings Intuition** | - Video: [LLMs from Scratch - Stanford CS229](https://www.youtube.com/watch?v=9vM4p9NN0Ts) (1 hr)<br>- Course: [Improving LLM Accuracy](https://www.deeplearning.ai/short-courses/improving-accuracy-of-llm-applications/) (Module 1, 2 hrs)<br>- Repo: [Hands-On Large Language Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models) — Jupyter notebooks covering embeddings, fine-tuning, and LLM apps (run 1 notebook, 1 hr)<br>- Integration: Apply Week 0 embeddings to visualize token vectors. | Learn training/inference with math grounding. Mini-project: Fine-tune a prompt for a riddle; measure improvement with similarity metrics. | 6-7 hrs |

## Week 3: Agentic AI Intro & Basics

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [01-the-agent-loop](phases/14-agent-engineering/01-the-agent-loop/) - agent loop, observation, action, feedback
> - [06-tool-use-and-function-calling](phases/14-agent-engineering/06-tool-use-and-function-calling/) - function calling, tool schema design

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Agentic AI Intro & Basics** | - Video: [Agentic AI Overview](https://www.youtube.com/watch?v=kJLiOGle3Lw) (45 min)<br>- Video: [Building an Agent from Scratch](https://youtu.be/xzXdLRUyjUg?si=hIbRX2zjaAyN9s_J) (1 hr)<br>- Course: [HuggingFace's Agent Course](https://huggingface.co/learn/agents-course/en/unit0/introduction) (Units 0-1, 2 hrs)<br>- Repo: [AI Agents for Beginners (Microsoft)](https://github.com/microsoft/ai-agents-for-beginners) — step-by-step lessons using Semantic Kernel, AutoGen, and Azure AI (Lesson 1, 1 hr) | Define agents/tools with probabilistic lens. Mini-project: Sketch/code a simple tool-calling agent (e.g., weather checker). | 7 hrs |

## Week 4: Building Basic Agents + Debugging Checkpoint

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [03-reflexion-verbal-rl](phases/14-agent-engineering/03-reflexion-verbal-rl/) - verbal reflection, self-critique
> - [05-self-refine-and-critic](phases/14-agent-engineering/05-self-refine-and-critic/) - self-refine patterns, error handling
> - [01-debugging-and-profiling](phases/00-setup-and-tooling/12-debugging-and-profiling/) - debugging tools for AI

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Building Basic Agents + Debugging Checkpoint** | - Video: [Building and Evaluating Agents](https://youtu.be/d5EltXhbcfA?si=Y7BK6MgG6dbtC5aX) (45 min)<br>- Video: [Building Effective Agents](https://youtu.be/D7_ipDqhtwk?si=x70I0lKjSxJFPGhF) (45 min)<br>- Guide: [Building Effective Agents by Anthropic](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/03-anthropic-building-effective-ai-agents.pdf) (1 hr)<br>- Repo: [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) (run example, 1 hr)<br>- New: Debugging Guide [Debugging LLM Failures](https://medium.com/@kuldeep.paul08/debugging-llm-failures-a-comprehensive-guide-to-robust-ai-applications-4d3e07c59df5) (hallucinations/loops, 1 hr) | Code first agent; checkpoint: Refactor Weeks 1-3 projects. Mini-project: Build calculator agent; deliberately induce failure (e.g., infinite loop), log traces, and fix. | 7-8 hrs |

## Week 5: Advanced Agent Tools

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [06-mcp-fundamentals](phases/13-tools-and-protocols/06-mcp-fundamentals/) - MCP protocol overview
> - [07-building-an-mcp-server](phases/13-tools-and-protocols/07-building-an-mcp-server/) - build your own MCP server
> - [08-building-an-mcp-client](phases/13-tools-and-protocols/08-building-an-mcp-client/) - connect to MCP servers

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Advanced Agent Tools**   | - Video: [Building Agents with MCP](https://youtu.be/kQmXtrmQ5Zg?si=bwduUYKZpAbXKLEa) (45 min)<br>- Course: [MCP with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/) (full, 3 hrs)<br>- Course: [Computer Use with Anthropic](https://www.deeplearning.ai/short-courses/building-towards-computer-use-with-anthropic/) (Modules 1-2, 2 hrs)<br>- Repo: [Hands-On AI Engineering](https://github.com/Sumanth077/Hands-On-AI-Engineering) — end-to-end AI project examples covering LLM apps, pipelines, and system design (1 project, 1 hr) | Integrate protocols with debugging in mind. Mini-project: Enhance Week 4 agent with MCP; test for tool mis-binding. | 8 hrs |

## Week 6: Retrieval & Memory

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [06-rag](phases/11-llm-engineering/06-rag/) - retrieval-augmented generation basics
> - [07-advanced-rag](phases/11-llm-engineering/07-advanced-rag/) - hybrid search, reranking, agentic RAG
> - [05-context-engineering](phases/11-llm-engineering/05-context-engineering/) - context window management
> - [07-memory-virtual-context-memgpt](phases/14-agent-engineering/07-memory-virtual-context-memgpt/) - virtual context memory

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Retrieval & Memory**     | - Course: [Building Vector DB with Pinecone](https://www.deeplearning.ai/short-courses/building-applications-vector-databases/) (Modules 1-2, 2 hrs)<br>- Course: [Agent Memory](https://www.deeplearning.ai/short-courses/llms-as-operating-systems-agent-memory/) (full, 2 hrs)<br>- Course: [Building and Evaluating RAG Apps](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) (Module 1, 1 hr)<br>- Paper: [Retrieval-Augmented Generation Survey](https://arxiv.org/pdf/2312.10997) (skim, 1 hr; tie to Week 0 embeddings) | Add RAG/memory; debug retrieval failures. Mini-project: RAG Q&A agent for a doc; fix hallucination via traces. | 8 hrs |

## Week 7: Agent Evaluation + Ethics/Safety

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [Phase 18: Ethics, Safety, Alignment](phases/18-ethics-safety-alignment/) - safety evaluation, red teaming, alignment
> - [10-evaluation](phases/11-llm-engineering/10-evaluation/) - LLM evaluation metrics, benchmarks
> - [12-guardrails](phases/11-llm-engineering/12-guardrails/) - guardrails, input/output filtering

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Agent Evaluation + Ethics/Safety** | - Course: [Evaluating AI Agents](https://www.deeplearning.ai/short-courses/evaluating-ai-agents/) (full, 2 hrs)<br>- Course: [Agent Design Patterns](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/) (Modules 1-2, 2 hrs)<br>- Papers: [ReAct](https://react-lm.github.io/); [Reflexion](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf) (overviews, 1 hr)<br>- New: Ethics Guide [LLM Red Teaming Guide](https://www.confident-ai.com/blog/red-teaming-llms-a-step-by-step-guide) (prompt injection/jailbreaking, 1 hr) | Evaluate patterns; cover ethics (e.g., data leakage). Mini-project: Harden Week 6 agent against malicious prompts; test adversarial cases. | 7 hrs |

## Week 8: Browser & Specialized Agents

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [Phase 15: Autonomous Systems](phases/15-autonomous-systems/) - computer use, browser automation
> - [Phase 13: MCP Apps](phases/13-tools-and-protocols/14-mcp-apps/) - MCP-powered applications

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Browser & Specialized Agents** | - Guide: [Google's Agent](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/09-agents.pdf) (1 hr)<br>- Guide: [Claude Code Best Practices](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/10-coding_best_practices_Anthropic.pdf) (1 hr)<br>- New: Tutorial [Building AI Browser Agents with n8n](https://www.youtube.com/watch?v=O3HP4uC7XlA) (full, 2 hrs) | Handle web tasks ethically. Mini-project: Browser agent for scraping headlines; add safety checks (e.g., no sensitive data). | 7 hrs |

## Week 9: Multi-Agent Systems

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [01-why-multi-agent](phases/16-multi-agent-and-swarms/01-why-multi-agent/) - why multi-agent systems
> - [05-supervisor-orchestrator-pattern](phases/16-multi-agent-and-swarms/05-supervisor-orchestrator-pattern/) - supervisor architecture
> - [06-hierarchical-architecture](phases/16-multi-agent-and-swarms/06-hierarchical-architecture/) - hierarchical agent teams
> - [07-society-of-mind-debate](phases/16-multi-agent-and-swarms/07-society-of-mind-debate/) - debate patterns

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Multi-Agent Systems**    | - Course: [Multi-Agent Use](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/) (full, 2 hrs)<br>- Course: [Multi Agent Systems](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) (Modules 1-2, 2 hrs)<br>- Papers: [Generative Agents](https://arxiv.org/pdf/2304.03442); [Tree of Thoughts](https://arxiv.org/pdf/2305.10601) (skim, 1 hr) | Coordinate agents; debug inter-agent loops. Mini-project: Multi-agent debate; evaluate ethical tradeoffs. | 8 hrs |

## Week 10: Ops & Optimization + Checkpoint

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [01-managed-llm-platforms](phases/17-infrastructure-and-production/01-managed-llm-platforms/) - OpenAI, Anthropic, Azure AI
> - [08-inference-metrics-goodput](phases/17-infrastructure-and-production/08-inference-metrics-goodput/) - latency, throughput, goodput
> - [13-llm-observability](phases/17-infrastructure-and-production/13-llm-observability/) - tracing, monitoring, debugging
> - [14-prompt-semantic-caching](phases/17-infrastructure-and-production/14-prompt-semantic-caching/) - semantic caching strategies

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Ops & Optimization + Checkpoint** | - Course: [LLMOps](https://www.deeplearning.ai/short-courses/llmops/) (full, 2 hrs)<br>- Guide: [Google's Agent Companion](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/08-agents-companion.pdf) (1 hr)<br>- Paper: [Toolformer](https://proceedings.neurips.cc/paper_files/paper/2023/file/d842425e4bf79ba039352da0f658a906-Paper-Conference.pdf) (overview, 1 hr)<br>- New: Expansion [How to Debug Agentic AI](https://katalon.com/resources-center/blog/how-to-debug-agentic-ai-from-failed-output-to-root-cause) (cost/latency/monitoring, 1 hr)<br>- Repo: [Made With ML](https://github.com/GokuMohandas/Made-With-ML) — production ML systems covering data pipelines, testing, and monitoring (skim ML systems section, 1 hr)<br>- Repo: [Designing ML Systems (Chip Huyen)](https://github.com/chiphuyen/dmls-book) — notes and references from the ML systems book; learn how real production ML pipelines work (browse, 30 min)<br>- Checkpoint: Refactor Weeks 1-9 with ops (e.g., add rate limits). | Deploy with monitoring/human loops. Mini-project: Optimize Week 9 agent for cost; log production-like traces. | 7 hrs |

## Week 11: Projects & Repos

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - [Phase 19: Capstone Projects](phases/19-capstone-projects/) - full-stack agent projects
> - [13-production-app](phases/11-llm-engineering/13-production-app/) - building production LLM apps
> - [17-agent-framework-tradeoffs](phases/11-llm-engineering/17-agent-framework-tradeoffs/) - LangChain, LlamaIndex, Hayraphase trade-offs

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Projects & Repos**       | - Repo: [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) (extend, 2 hrs)<br>- Repo: [Microsoft's AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) (1 lab, 2 hrs)<br>- Repo: [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — most complete prompt engineering resource covering RAG, agents, and LLM workflows (apply, 1 hr)<br>- Repo: [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai) — curated list of GenAI tools, frameworks, research papers, and tutorials for LLM apps and agents (browse, 30 min)<br>- Course: [HuggingFace's Agent Course](https://huggingface.co/learn/agents-course/en/unit0/introduction) (finish Units 2+, 1 hr) | Build robust projects. Mini-project: Integrate RAG/multi-agent with ethics/debugging. | 8 hrs |

## Week 12: Synthesis, Deep Dive & Portfolio Polish

> 📚 **Source Course Lessons** (AI Engineering from Scratch):
> - Synthesize all phases - bring together everything learned
> - Use [Phase 19: Capstone Projects](phases/19-capstone-projects/) for portfolio ideas
> - Review [Phase 18: Ethics, Safety, Alignment](phases/18-ethics-safety-alignment/) for ethics recap

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Synthesis, Deep Dive & Portfolio Polish** | - Repo: [AI Agent Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers) (review 2-3, 2 hrs)<br>- Papers: Remaining (summarize with AI, 1 hr)<br>- Full Playlist: [All Videos](https://youtube.com/playlist?list=PLFTL4e_1THqDgaDuFjzvdF58auTjQg21q&si=UM49A-XX25MZgu-x) (rewatch 1, 30 min)<br>- New: Polish [AI Red Teaming Courses](https://learnprompting.org/blog/ai-red-teaming-courses) (ethics recap, 30 min) | Synthesize; capstone: Full ethical agent app. Mini-project: Portfolio—README, demo video, lessons (e.g., failure modes learned). Share on GitHub/LinkedIn. | 6-7 hrs |

This upgraded plan transforms shallow demos into production-ready skills, with math/debugging/ethics woven in for depth. By end, you'll have a hardened portfolio for jobs/startups in 2025's agent economy. For tweaks, query AI on "agent failure simulations." Dive in!

---

## Supplemental Reference Repositories

These repos are integrated throughout the weekly curriculum above but listed here for quick reference. All links verified as of April 2026.

| # | Repo | Description | Best Week |
|---|------|-------------|-----------|
| 0 | **[AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch)** | ⭐ Primary reference - 20-phase, 416-lesson comprehensive curriculum with runnable code | All weeks |
| 1 | [AI Agents for Beginners (Microsoft)](https://github.com/microsoft/ai-agents-for-beginners) | Step-by-step lessons using Semantic Kernel, AutoGen, and Azure AI with real notebooks | Weeks 3, 11 |
| 2 | [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai) | Massive curated list of GenAI resources — tools, frameworks, papers, and tutorials for LLM apps, agents, and RAG | Week 11 |
| 3 | [Designing ML Systems (Chip Huyen)](https://github.com/chiphuyen/dmls-book) | Notes and references from the ML systems book; learn how real production ML pipelines work | Week 10 |
| 4 | [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) | Practical tutorials for building GenAI agents covering LangChain, tools, memory, and workflows | Weeks 4, 11 |
| 5 | [Hands-On AI Engineering](https://github.com/Sumanth077/Hands-On-AI-Engineering) | End-to-end AI project examples covering LLM apps, pipelines, and system design | Week 5 |
| 6 | [Hands-On Large Language Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models) | Jupyter notebooks explaining LLM concepts — embeddings, fine-tuning, and LLM apps | Week 2 |
| 7 | [LLM Course](https://github.com/mlabonne/llm-course) | Practical LLM learning path — how LLMs work, local LLM apps, and RAG pipelines | Week 1 |
| 8 | [Machine Learning for Beginners (Microsoft)](https://github.com/microsoft/ML-For-Beginners) | 12-week curriculum with labs covering classical ML models and workflows; pairs with Week 0 math foundations | Week 0 |
| 9 | [Made With ML](https://github.com/GokuMohandas/Made-With-ML) | Build ML systems used in real products — data pipelines, testing, and monitoring | Week 10 |
| 10 | [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | Most complete prompt engineering resource — techniques with examples, RAG, agents, and LLM workflows | Week 11 |