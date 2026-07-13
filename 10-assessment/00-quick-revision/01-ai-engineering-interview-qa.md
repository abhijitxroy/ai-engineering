# AI Engineering Interview Q&A

> Simple, interview-focused questions and answers.

---

# 1. What is an AI Agent?

An AI Agent is a software application that understands a goal, makes decisions, uses tools, and completes tasks with little or no human intervention.

Unlike a chatbot, an AI agent can perform actions such as calling APIs, reading files, querying databases, creating Jira tickets, or interacting with GitHub.

---

# 2. What is the difference between an AI Chatbot and an AI Agent?

| AI Chatbot | AI Agent |
|------------|----------|
| Answers questions | Achieves a goal |
| Conversation focused | Action focused |
| Waits for user input | Can plan multiple steps |
| Usually returns text | Can perform actions |
| Limited tool usage | Uses multiple tools and APIs |

**Example**

Chatbot:
> Explain Kubernetes.

AI Agent:
> Find all GitHub bugs assigned to me and create Jira tickets.

---

# 3. Give a real-world example of an AI Agent.

In our organization, an AI agent monitors GitHub issues.

When a new issue is created:

- Reads the issue
- Reviews the source code
- Validates whether it is a genuine issue
- Creates a Jira ticket
- Sets priority
- Adds title
- Adds description
- Fills affected version
- Returns the ticket information

This reduces manual work and improves consistency.

---

# 4. What are the main components of an AI Agent?

1. User Goal
2. LLM (Reasoning Engine)
3. Planning / Decision Making
4. Memory (Optional)
5. Tools
6. MCP (Optional)
7. Output

Flow

```
User Goal
      │
      ▼
     LLM
      │
      ▼
    Tools
      │
      ▼
   Final Result
```

---

# 5. Why does an AI Agent need tools?

An LLM can understand language and reason, but it cannot access external systems by itself.

To perform real-world tasks it needs tools.

Examples:

- GitHub
- Jira
- Database
- File System
- REST API
- Web Search

Remember:

> **LLM thinks. Tools act.**

---

# 6. What is MCP?

MCP stands for **Model Context Protocol**.

It is a standard protocol that allows AI applications to communicate with external tools in a consistent way.

Instead of writing custom integrations for every application, AI applications or AI agents can use MCP to communicate with external tools through a common interface.

Examples:

- GitHub
- Jira
- PostgreSQL
- File System
- Slack

Think of MCP as:

> **USB-C for AI applications.**

---

# 7. API vs MCP

| API | MCP |
|------|-----|
| Application ↔ Application | AI ↔ Tool |
| Custom integration | Standard protocol |
| Used by all software | Designed for AI |
| One API per service | One common interface |

Important:

MCP does **not** replace APIs.

Most MCP servers internally call APIs.

---

# 8. What is RAG?

RAG stands for

**Retrieval-Augmented Generation**

It allows an AI model to retrieve additional information before generating a response.

The retrieved information may come from

- PDFs
- Company Wiki
- SharePoint
- Documentation
- Database
- Internal Knowledge Base

The retrieved information is provided to the LLM as additional context before it generates the response.

Remember

> **RAG retrieves information first, then the LLM generates the answer.**

---

# 9. RAG vs MCP

| RAG | MCP |
|------|-----|
| Retrieves information | Uses tools |
| Searches documents | Performs actions |
| Knowledge retrieval | Tool communication |

Example

Question:
> What is our leave policy?

Uses:

RAG

Question:
> Create a Jira ticket.

Uses:

MCP + Jira Tool

---

# 10. What is Tool Calling?

Tool Calling is the ability of an AI model or AI agent to use external tools to complete a task.

Examples:

- GitHub
- Jira
- PostgreSQL
- REST APIs
- File System
- Calculator

Tool Calling may use MCP, APIs, or SDKs depending on how the tool is integrated.

Flow

```
User

↓

AI Agent

↓

LLM decides

↓

Tool Calling

↓

Tool executes

↓

LLM

↓

User
```

---

# 11. What is a Prompt?

A prompt is the input given to an AI model.

It can be:

- Question
- Instruction
- Goal
- Task

Example

Question

> Explain Kubernetes.

Instruction

> Write a Python program.

Task

> Create a Jira ticket.

---

# 12. What is Prompt Engineering?

Prompt Engineering is the process of writing better prompts to obtain accurate, relevant, and useful responses from AI.

A good prompt includes

- Context
- Goal
- Constraints
- Expected Output

---

# 13. What is an LLM?

LLM stands for

**Large Language Model**

It is an AI model trained on massive amounts of text and code data.

It can

- Understand language
- Reason
- Generate text
- Write code
- Summarize
- Translate

Remember

An LLM does **not** access the internet or databases by itself.

---

# 14. Can an LLM access the Internet?

No.

It only knows what it learned during training.

To access:

- Internet
- GitHub
- Database
- Jira
- File System

It needs external tools.

---

# 15. LLM vs AI Agent

| LLM | AI Agent |
|------|----------|
| Understands language | Solves a goal |
| Generates text | Performs actions |
| Uses learned knowledge from training | Uses tools |
| Cannot act | Can act |

Remember

> **LLM is the brain. AI Agent is the brain plus planner plus tools.**

---

# 16. RAG vs Fine-tuning

| RAG | Fine-tuning |
|------|-------------|
| Retrieves knowledge | Retrains the model |
| Easy to update | Expensive |
| Uses external documents | Changes model behavior |
| No retraining | Requires training |

Remember

> **RAG adds knowledge. Fine-tuning changes behavior.**

---

# 17. What is an Embedding?

An embedding is a numerical representation (vector) of text, images, or other data that captures its meaning.

Similar meanings have similar embeddings.

Similar embeddings are stored close together in vector space.

Example

Forgot Password

≈

Reset Password

---

# 18. What is a Vector Database?

A Vector Database stores embeddings and efficiently searches for semantically similar data.

Instead of matching exact words, it matches meaning.

It is optimized for similarity search rather than exact keyword matching.

Popular Vector Databases

- Pinecone
- Milvus
- Weaviate
- ChromaDB
- FAISS (library)

---

# 19. Complete RAG Flow

```
User Question
        │
        ▼
Generate Query Embedding
        │
        ▼
Vector Database
        │
Retrieve Documents
        │
        ▼
LLM
        │
Generate Answer
        │
        ▼
User
```

---

# 20. Complete AI Agent Flow

```
User
  │
  ▼
AI Agent
  │
  ▼
LLM (Reasoning)
  │
  ▼
Tool Selection
  │
  ├────────────┐
  ▼            ▼
GitHub      Database
Tool         Tool
  │            │
  └──────┬─────┘
         ▼
      Retrieved Data
         │
         ▼
        LLM
         │
         ▼
     Final Response
         │
         ▼
        User
```

---

# 21. AI Agent vs Workflow

| Workflow | AI Agent |
|----------|----------|
| Fixed sequence | Goal driven |
| Predefined steps | Makes decisions |
| No reasoning | Reasons before acting |
| Same execution path | Dynamic execution path |
| Limited flexibility | Adapts based on the goal |

---

# Interview One-Liners

### AI Agent

> An AI Agent understands a goal, makes decisions, uses tools, and completes tasks.

### LLM

> The LLM is the brain of an AI application.

### Tools

> Tools allow the AI to perform real-world actions.

### MCP

> MCP is like USB-C for AI. It provides a standard way for AI to connect to tools.

### RAG

> RAG retrieves information first, then the LLM generates the answer.

### RAG vs MCP

> RAG retrieves knowledge. MCP connects tools.

### Embedding

> An embedding converts text into numbers while preserving meaning.

### Vector Database

> A vector database stores embeddings and finds semantically similar information.

### Prompt

> A prompt is the instruction or input given to an AI model.

### Prompt Engineering

> Prompt engineering is the process of designing prompts to get better AI responses.

### Tool Calling

> Tool Calling allows an AI model or AI agent to use external tools to complete tasks.

### LLM vs AI Agent

> The LLM thinks. The AI Agent thinks and acts.

### LLM vs Tool

> The LLM decides. The tool performs the action.

### RAG vs Fine-tuning

> RAG adds knowledge. Fine-tuning changes model behavior.


### LangChain

> LangChain is a framework that helps developers build LLM applications faster.

### Spring AI

> Spring AI brings AI capabilities to the Spring ecosystem.

### Spring AI vs LangChain

> Spring AI is for Spring Boot applications. LangChain is a general AI framework.

### LangGraph

> LangGraph is designed for complex, stateful AI workflows with branching and retries.

### LangChain vs LangGraph

> LangChain builds AI applications. LangGraph orchestrates complex AI agent workflows.

### AI Hallucination

> AI hallucination is when an LLM confidently generates incorrect or fabricated information.

### RAG and Hallucination

> RAG reduces hallucinations by providing trusted context before the LLM generates a response.

### RAG vs Tool Calling

> RAG retrieves knowledge. Tool Calling performs actions.

### Tool Failure

> A production AI agent should retry, recover, and fail gracefully instead of failing immediately.


---

# 22. What is LangChain?

LangChain is an open-source framework used to build AI applications powered by LLMs.

It provides reusable components for:

- Prompt management
- Tool Calling
- Memory
- RAG
- Agents
- Output parsing

Instead of writing everything from scratch, developers can use LangChain to build AI applications faster.

Remember

> **LangChain helps developers build LLM applications faster.**

---

# 23. What is Spring AI?

Spring AI is a Spring Framework module that helps developers build AI-powered applications using Spring Boot.

It provides support for:

- Chat Models
- Embeddings
- Vector Databases
- Prompt Templates
- Tool Calling
- RAG

It follows the familiar Spring programming model.

Remember

> **Spring AI brings AI capabilities to the Spring ecosystem.**

---

# 24. Spring AI vs LangChain

| Spring AI | LangChain |
|------------|-----------|
| Spring Framework module | General AI framework |
| Java + Spring Boot | Multiple languages |
| Integrates with Spring | AI application framework |
| Best for Spring developers | Best for general AI development |

---

# 25. What is LangGraph?

LangGraph is a framework for building complex AI agents.

It supports:

- Multi-step workflows
- Decision making
- Loops
- Retries
- Human-in-the-loop
- Stateful execution

Unlike a simple chain, LangGraph models the workflow as a graph.

Remember

> **LangChain builds AI applications. LangGraph orchestrates complex AI agent workflows.**

---

# 26. When should you use LangGraph instead of LangChain?

Use LangGraph when the AI application needs:

- Retries
- Branching
- Multiple decisions
- Human approval
- Long-running workflows
- Multiple tool calls

Example

Read GitHub issue → Analyze → Create Jira → Notify Slack → Retry if Jira fails.

---

# 27. Design an AI Assistant for Developers

High-level architecture:

- User
- AI Agent
- LLM
- GitHub Tool
- RAG for internal documentation
- Jira Tool
- Build Log Analysis Tool
- Final Response

If supported, tools can communicate through MCP. Otherwise, APIs or SDKs can be used.

Remember

> **Use RAG for knowledge retrieval and Tool Calling for actions.**

---

# 28. What is AI Hallucination?

An AI hallucination occurs when an LLM generates information that sounds correct but is actually incorrect or fabricated.

The model is not intentionally lying. It is predicting the most likely response.

How to reduce hallucinations:

- Use RAG
- Use trusted tools
- Provide better prompts
- Use reliable data sources
- Human review for critical tasks

Remember

> **Hallucination means confidently generating incorrect information.**

---

# 29. How does RAG reduce Hallucinations?

RAG retrieves trusted information before the LLM generates a response.

Instead of relying only on training data, the LLM receives relevant documents as context.

This improves answer accuracy.

Remember

> **RAG reduces hallucinations by providing trusted context.**

---

# 30. How does the AI decide between RAG and Tool Calling?

The decision depends on the user's goal.

- If the user needs information, use RAG.
- If the user wants an action performed, use Tool Calling.
- Some requests require both.

Example:

- "What is our leave policy?" → RAG
- "Create a Jira ticket." → Tool Calling
- "Read the bug guide and create a Jira ticket." → RAG + Tool Calling

Remember

> **RAG retrieves knowledge. Tool Calling performs actions.**

---

# 31. What should an AI Agent do if a Tool fails?

If a tool fails, the AI agent should:

- Retry the operation
- Handle timeouts
- Log the error
- Use fallback logic if available
- Continue other tasks when possible
- Inform the user if the task cannot be completed

Frameworks like LangGraph are useful for implementing retries and recovery workflows.

Remember

> **Production AI agents should fail gracefully, not fail immediately.**