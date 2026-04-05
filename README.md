# Agentic AI Labs 🤖

A collection of hands-on experiments and mini-projects for learning Agentic AI concepts, frameworks, and implementation patterns.

## 📚 What's Inside

This repository documents my journey into the world of AI agents:
- **Agent Fundamentals** - Core concepts of autonomous AI agents
- **Tool Integration** - Function calling and external tool usage
- **RAG Agents** - Retrieval-Augmented Generation systems
- **Multi-Agent Systems** - Coordination and collaboration between agents
- **Agent Design Patterns** - Common patterns for building robust agents

Each folder represents a focused learning exercise with working code and detailed explanations.

## 🗂️ Repository Structure
```
agentic-ai-labs/
├── README.md
├── 01_agent_basics/
│   └── ...
├── 02_tool_calling/
│   └── ...
├── 03_rag_agent/
│   └── ...
├── 04_multi_agent/
│   └── ...
├── 05_Agent_Design_Pattern/
│   └── ...
└── notes.md
```

## 🎯 Learning Goals

- [ ] Understand core agent architecture and reasoning loops
- [ ] Master tool calling and function execution
- [ ] Build RAG-powered agents with knowledge retrieval
- [ ] Implement multi-agent coordination and communication
- [ ] Apply agent design patterns (routing, chaining, parallelization, etc)
- [ ] Explore agentic frameworks (LangChain, LlamaIndex, AutoGPT, etc)
- [ ] Practice prompt engineering for agent behaviors
- [ ] Handle agent memory and state management

## 🚀 Getting Started

Each project folder contains:
- `README.md` - Concept overview and implementation details
- Source code with detailed comments
- `poetry` - Project dependencies
- Example outputs and test cases

### Prerequisites
- Python 3.9 or higher
- OpenAI API key (or other LLM provider)
- Basic understanding of LLMs and prompt engineering

### Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/agentic-ai-labs.git
cd agentic-ai-labs

# Navigate to a specific project
cd 01_agent_basics


# Set up environment variables
export OPENAI_API_KEY='your-api-key-here'
# or create a .env file

# Run the agent
python main.py
```

## 📖 Projects

| # | Project | Concepts Covered | Status |
|---|---------|------------------|--------|
|	| ....... |  .............   | ...... |

**Legend:** ✅ Completed | 🚧 In Progress | 📋 Planned

## 🛠️ Tech Stack

- **LLM Providers:** OpenAI GPT-4, Anthropic Claude, Ollama (local)
- **Frameworks:** LangChain, LlamaIndex, CrewAI
- **Vector Stores:** ChromaDB, Pinecone, FAISS
- **Tools:** Python 3.x, Pydantic, asyncio
- **APIs:** OpenAI, Tavily (search), custom tools

## 🧠 Key Concepts Explored

### Agent Architectures
- TODO

### Design Patterns
- **Routing** - Dynamic path selection based on input
- **Prompt Chaining** - Sequential task breakdown
- **Parallelization** - Concurrent agent execution
- **Orchestration** - Coordinating multiple specialized agents


## 🔒 Environment Variables

Create a `.env` file in each project directory:
```env
OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key
TAVILY_API_KEY=your_tavily_key
```

## 🤝 Contributing

This is a personal learning repository, but suggestions and feedback are welcome! Feel free to:
- Open an issue for suggestions or questions
- Share interesting agent patterns or papers
- Point out improvements or best practices
- Contribute example use cases

## ⚠️ Important Notes

- **API Costs:** Some experiments use paid LLM APIs. Monitor your usage!
- **Rate Limits:** Be mindful of API rate limits during experimentation
- **Local Options:** Consider using Ollama for local LLM experimentation

## 📄 License

MIT License - feel free to use these examples for your own learning.

---

⭐ **Note:** This is a living laboratory. Experiments may be incomplete, and implementations evolve as I learn. Focus is on understanding concepts rather than production-ready code.

💡 **Tip:** Check `notes.md` for my personal learnings, challenges faced, and insights gained throughout this journey.
