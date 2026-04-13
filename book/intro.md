# Build Intelligent AI Systems with LangChain 🦜⛓️‍💥

**Your hands-on guide to Retrieval-Augmented Generation, Agentic AI, and Agentic Security.**

As AI moves from answering questions to taking actions — approving payments, deploying code, managing records, executing contracts — the way we build and secure these systems has to evolve with it. This guide takes you from the foundations of RAG through the architecture of agentic workflows and into the emerging discipline of securing AI agents in production.

## Part I — Retrieval-Augmented Generation (Basics)

We start with the fundamentals. Retrieval-Augmented Generation (RAG) is the technique of grounding a language model's outputs in external knowledge — combining the reasoning power of generative AI with the reliability of structured, retrievable data. The result is responses that are not only coherent but factually anchored.

We cover the full RAG pipeline step by step: query transformation, hypothetical document embeddings, routing mechanisms, indexing strategies, and advanced retrieval techniques including Self-RAG, Adaptive RAG, and CRAG (Corrective Retrieval-Augmented Generation). Each chapter builds on the last, giving you both the theory and working implementations using LangChain.

## Part II — Agentic AI and Security

RAG is a pipeline. Agents are something more: autonomous systems that plan, delegate, loop, and act. We explore how LangGraph extends LangChain into stateful multi-agent workflows, where specialized agents handle distinct tasks, pass state to one another, and make routing decisions dynamically. Autonomous agents operating on sensitive data introduce a category of risk that traditional software security wasn't designed for. When a human delegates to an agent — and that agent delegates to another — the original authorization context disappears. There is no built-in record of what was approved, which agents ran, or whether any action was within scope.

This section introduces **HDP (Human Delegation Provenance)**, an open protocol from [Helixar](https://helixar.ai) that creates a cryptographic chain-of-custody from the human's authorization event through every downstream agent action. We demonstrate the integration of HDP with LangGraph, simulate real-world attack scenarios — rogue agent injection, chain blending, and evidence erasure — and show exactly which detection layer catches each threat.

---

The organization and content of the RAG sections is primarily based on the [**LangChain Tutorial Series**](https://www.youtube.com/watch?v=wd7TZ4w1mSw&list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x) with significant extensions and improvements.

```{tableofcontents}
```
