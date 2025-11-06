# 🤖 RAG Knowledge Assistant

**Goal:** Create an assistant that answers questions using your own data (like PDFs or company docs).

**Concept (in simple terms):**
- Step 1: Store your documents in a searchable format (called "embeddings").
- Step 2: When a user asks a question, find relevant text first.
- Step 3: Send both the question + found text to an AI model like GPT.
- Step 4: Model gives a precise answer based on your data.

**Tools used (conceptually):**
- LangChain (to connect parts)
- OpenAI API (the brain)
- ChromaDB or FAISS (for storing document embeddings)

**Why this matters for product managers:**
- RAG makes AI answers accurate and business-specific.
- Cheaper and faster than training a new model.
- Used in Chatbots, Knowledge Search, and Enterprise Tools.

**Key Learnings:**
- AI models without data grounding can “hallucinate.”
- Retrieval improves factual accuracy.
- You can measure performance by answer relevance or latency.
