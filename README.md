# 12-Week AI Agents Course: From Scratch to Robust, Ethical Autonomous Systems

This 12-week self-paced course addresses key structural gaps through a first-principles lens: building mathematical intuition early, embedding debugging and failure-mode handling, integrating security/ethics, expanding real-world deployment, and adding structured checkpoints for cumulative review. It remains beginner-friendly (no prior AI/ML knowledge required) and fits within 12 weeks by interleaving fixes without overload. The upgraded flow ensures progressive depth: foundations with math grounding, core building with debugging, advanced techniques, evaluation/ethics, multi-agent ops, and polished projects.

## Key Guidelines

- **Time Commitment**: 6-8 hours/week (videos/guides 2-3 hrs, courses/hands-on 3-4 hrs, review 1 hr). Week 0 is optional (2-3 hrs total).
- **Tools Needed**: Free accounts on YouTube, Hugging Face, DeepLearning.AI (free audits available), GitHub, Khan Academy. Use AI (e.g., Grok) for clarifications, code fixes, or ethical scenario simulations.
- **Prerequisites**: Basic computer skills; if new to Python, add [freeCodeCamp's Python for Everybody](https://www.youtube.com/watch?v=8DvywoWv6fI) (first 2 hrs) before starting.
- **Hands-On Focus**: Weekly mini-projects build a GitHub portfolio. Checkpoints in Weeks 4 and 10 refactor prior work.
- **All Resources**: From the original list (links verified as of September 14, 2025) plus targeted additions for gaps. Total keeps ~90% original coverage.

## Week 0: Optional Math for AI Agents Crash Kit (2-3 hrs)

Build intuition for probability (e.g., LLM predictions), embeddings (vector representations), and metrics (e.g., cosine similarity for similarity). Essential for reasoning about "why" agents work/fail.

| Focus            | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Math Intuition** | - Videos: [3Blue1Brown Essence of Linear Algebra (Chapters 1-3: Vectors, Linear Combinations, Matrices)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) (1 hr)<br>- Videos: [Khan Academy Probability Basics (Intro to Probability, Random Variables)](https://www.khanacademy.org/math/statistics-probability/probability-library) (45 min)<br>- Guide: [3Blue1Brown Neural Networks Playlist (Chapter on Embeddings/Cosine Similarity)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) (45 min)<br>- Repo: [Machine Learning for Beginners (Microsoft)](https://github.com/microsoft/ML-For-Beginners) — 12-week structured curriculum with labs covering classical ML models; skim Week 1 intro for ML context (30 min) | Grasp vectors as "AI's language," probability for uncertainty, embeddings for meaning. Mini-project: Calculate cosine similarity by hand for two sentences using AI-generated vectors. | 2-3 hrs |

## Week 1: AI & LLM Basics + Math Integration

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **AI & LLM Basics + Math Integration** | - Video: [LLM Introduction](https://www.youtube.com/watch?v=zjkBMFhNj_g) (30 min)<br>- Guide: [OpenAI's Practical Guide to Building Agents](https://github.com/HeyNina101/ai-agent-starter-kit/tree/main/expert-guides) (intro, 1 hr)<br>- Paper: [Chain-of-Thought Prompting](https://arxiv.org/pdf/2201.11903) (skim with Week 0 math, 30 min)<br>- Repo: [LLM Course](https://github.com/mlabonne/llm-course) — practical LLM learning path covering local LLMs and RAG pipelines (browse overview, 30 min)<br>- Integration: Review Week 0 probability for prompt "uncertainty." | Understand LLMs as probabilistic predictors. Mini-project: 5 chain-of-thought prompts; evaluate with basic metrics (e.g., accuracy via cosine sim). | 5-6 hrs |

## Week 2: LLM Fundamentals + Embeddings Intuition

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **LLM Fundamentals + Embeddings Intuition** | - Video: [LLMs from Scratch - Stanford CS229](https://www.youtube.com/watch?v=9vM4p9NN0Ts) (1 hr)<br>- Course: [Improving LLM Accuracy](https://www.deeplearning.ai/short-courses/improving-accuracy-of-llm-applications/) (Module 1, 2 hrs)<br>- Repo: [Hands-On Large Language Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models) — Jupyter notebooks covering embeddings, fine-tuning, and LLM apps (run 1 notebook, 1 hr)<br>- Integration: Apply Week 0 embeddings to visualize token vectors. | Learn training/inference with math grounding. Mini-project: Fine-tune a prompt for a riddle; measure improvement with similarity metrics. | 6-7 hrs |

## Week 3: Agentic AI Intro & Basics

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Agentic AI Intro & Basics** | - Video: [Agentic AI Overview](https://www.youtube.com/watch?v=kJLiOGle3Lw) (45 min)<br>- Video: [Building an Agent from Scratch](https://youtu.be/xzXdLRUyjUg?si=hIbRX2zjaAyN9s_J) (1 hr)<br>- Course: [HuggingFace's Agent Course](https://huggingface.co/learn/agents-course/en/unit0/introduction) (Units 0-1, 2 hrs)<br>- Repo: [AI Agents for Beginners (Microsoft)](https://github.com/microsoft/ai-agents-for-beginners) — step-by-step lessons using Semantic Kernel, AutoGen, and Azure AI (Lesson 1, 1 hr) | Define agents/tools with probabilistic lens. Mini-project: Sketch/code a simple tool-calling agent (e.g., weather checker). | 7 hrs |

## Week 4: Building Basic Agents + Debugging Checkpoint

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Building Basic Agents + Debugging Checkpoint** | - Video: [Building and Evaluating Agents](https://youtu.be/d5EltXhbcfA?si=Y7BK6MgG6dbtC5aX) (45 min)<br>- Video: [Building Effective Agents](https://youtu.be/D7_ipDqhtwk?si=x70I0lKjSxJFPGhF) (45 min)<br>- Guide: [Building Effective Agents by Anthropic](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/03-anthropic-building-effective-ai-agents.pdf) (1 hr)<br>- Repo: [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) (run example, 1 hr)<br>- New: Debugging Guide [Debugging LLM Failures](https://medium.com/@kuldeep.paul08/debugging-llm-failures-a-comprehensive-guide-to-robust-ai-applications-4d3e07c59df5) (hallucinations/loops, 1 hr) | Code first agent; checkpoint: Refactor Weeks 1-3 projects. Mini-project: Build calculator agent; deliberately induce failure (e.g., infinite loop), log traces, and fix. | 7-8 hrs |

## Week 5: Advanced Agent Tools

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Advanced Agent Tools**   | - Video: [Building Agents with MCP](https://youtu.be/kQmXtrmQ5Zg?si=bwduUYKZpAbXKLEa) (45 min)<br>- Course: [MCP with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/) (full, 3 hrs)<br>- Course: [Computer Use with Anthropic](https://www.deeplearning.ai/short-courses/building-towards-computer-use-with-anthropic/) (Modules 1-2, 2 hrs)<br>- Repo: [Hands-On AI Engineering](https://github.com/Sumanth077/Hands-On-AI-Engineering) — end-to-end AI project examples covering LLM apps, pipelines, and system design (1 project, 1 hr) | Integrate protocols with debugging in mind. Mini-project: Enhance Week 4 agent with MCP; test for tool mis-binding. | 8 hrs |

## Week 6: Retrieval & Memory

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Retrieval & Memory**     | - Course: [Building Vector DB with Pinecone](https://www.deeplearning.ai/short-courses/building-applications-vector-databases/) (Modules 1-2, 2 hrs)<br>- Course: [Agent Memory](https://www.deeplearning.ai/short-courses/llms-as-operating-systems-agent-memory/) (full, 2 hrs)<br>- Course: [Building and Evaluating RAG Apps](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) (Module 1, 1 hr)<br>- Paper: [Retrieval-Augmented Generation Survey](https://arxiv.org/pdf/2312.10997) (skim, 1 hr; tie to Week 0 embeddings) | Add RAG/memory; debug retrieval failures. Mini-project: RAG Q&A agent for a doc; fix hallucination via traces. | 8 hrs |

## Week 7: Agent Evaluation + Ethics/Safety

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Agent Evaluation + Ethics/Safety** | - Course: [Evaluating AI Agents](https://www.deeplearning.ai/short-courses/evaluating-ai-agents/) (full, 2 hrs)<br>- Course: [Agent Design Patterns](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/) (Modules 1-2, 2 hrs)<br>- Papers: [ReAct](https://react-lm.github.io/); [Reflexion](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf) (overviews, 1 hr)<br>- New: Ethics Guide [LLM Red Teaming Guide](https://www.confident-ai.com/blog/red-teaming-llms-a-step-by-step-guide) (prompt injection/jailbreaking, 1 hr) | Evaluate patterns; cover ethics (e.g., data leakage). Mini-project: Harden Week 6 agent against malicious prompts; test adversarial cases. | 7 hrs |

## Week 8: Browser & Specialized Agents

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Browser & Specialized Agents** | - Guide: [Google's Agent](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/09-agents.pdf) (1 hr)<br>- Guide: [Claude Code Best Practices](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/10-coding_best_practices_Anthropic.pdf) (1 hr)<br>- New: Tutorial [Building AI Browser Agents with n8n](https://www.youtube.com/watch?v=O3HP4uC7XlA) (full, 2 hrs) | Handle web tasks ethically. Mini-project: Browser agent for scraping headlines; add safety checks (e.g., no sensitive data). | 7 hrs |

## Week 9: Multi-Agent Systems

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Multi-Agent Systems**    | - Course: [Multi-Agent Use](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/) (full, 2 hrs)<br>- Course: [Multi Agent Systems](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) (Modules 1-2, 2 hrs)<br>- Papers: [Generative Agents](https://arxiv.org/pdf/2304.03442); [Tree of Thoughts](https://arxiv.org/pdf/2305.10601) (skim, 1 hr) | Coordinate agents; debug inter-agent loops. Mini-project: Multi-agent debate; evaluate ethical tradeoffs. | 8 hrs |

## Week 10: Ops & Optimization + Checkpoint

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Ops & Optimization + Checkpoint** | - Course: [LLMOps](https://www.deeplearning.ai/short-courses/llmops/) (full, 2 hrs)<br>- Guide: [Google's Agent Companion](https://github.com/HeyNina101/ai-agent-starter-kit/blob/main/expert-guides/08-agents-companion.pdf) (1 hr)<br>- Paper: [Toolformer](https://proceedings.neurips.cc/paper_files/paper/2023/file/d842425e4bf79ba039352da0f658a906-Paper-Conference.pdf) (overview, 1 hr)<br>- New: Expansion [How to Debug Agentic AI](https://katalon.com/resources-center/blog/how-to-debug-agentic-ai-from-failed-output-to-root-cause) (cost/latency/monitoring, 1 hr)<br>- Repo: [Made With ML](https://github.com/GokuMohandas/Made-With-ML) — production ML systems covering data pipelines, testing, and monitoring (skim ML systems section, 1 hr)<br>- Repo: [Designing ML Systems (Chip Huyen)](https://github.com/chiphuyen/dmls-book) — notes and references from the ML systems book; learn how real production ML pipelines work (browse, 30 min)<br>- Checkpoint: Refactor Weeks 1-9 with ops (e.g., add rate limits). | Deploy with monitoring/human loops. Mini-project: Optimize Week 9 agent for cost; log production-like traces. | 7 hrs |

## Week 11: Projects & Repos

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Projects & Repos**       | - Repo: [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) (extend, 2 hrs)<br>- Repo: [Microsoft's AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) (1 lab, 2 hrs)<br>- Repo: [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — most complete prompt engineering resource covering RAG, agents, and LLM workflows (apply, 1 hr)<br>- Repo: [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai) — curated list of GenAI tools, frameworks, research papers, and tutorials for LLM apps and agents (browse, 30 min)<br>- Course: [HuggingFace's Agent Course](https://huggingface.co/learn/agents-course/en/unit0/introduction) (finish Units 2+, 1 hr) | Build robust projects. Mini-project: Integrate RAG/multi-agent with ethics/debugging. | 8 hrs |

## Week 12: Synthesis, Deep Dive & Portfolio Polish

| Focus                      | Key Resources                                                                 | Goals/Activities                                                                 | Estimated Time |
|----------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------|
| **Synthesis, Deep Dive & Portfolio Polish** | - Repo: [AI Agent Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers) (review 2-3, 2 hrs)<br>- Papers: Remaining (summarize with AI, 1 hr)<br>- Full Playlist: [All Videos](https://youtube.com/playlist?list=PLFTL4e_1THqDgaDuFjzvdF58auTjQg21q&si=UM49A-XX25MZgu-x) (rewatch 1, 30 min)<br>- New: Polish [AI Red Teaming Courses](https://learnprompting.org/blog/ai-red-teaming-courses) (ethics recap, 30 min) | Synthesize; capstone: Full ethical agent app. Mini-project: Portfolio—README, demo video, lessons (e.g., failure modes learned). Share on GitHub/LinkedIn. | 6-7 hrs |

This upgraded plan transforms shallow demos into production-ready skills, with math/debugging/ethics woven in for depth. By end, you'll have a hardened portfolio for jobs/startups in 2025's agent economy. For tweaks, query AI on "agent failure simulations." Dive in!

---

## Supplemental Reference Repositories

These repos are integrated throughout the weekly curriculum above but listed here for quick reference. All links verified as of April 2026.

| # | Repo | Description | Best Week |
|---|------|-------------|-----------|
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