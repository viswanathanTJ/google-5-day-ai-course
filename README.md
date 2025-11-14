# Google 5-Day AI Agent Course 🤖

A comprehensive 5-day learning journey into building AI agents using Google's Agent Development Kit (ADK). This repository contains Jupyter notebooks covering fundamental to advanced concepts in AI agent development.

## 📚 Course Overview

This course takes you from basic prompts to deploying production-ready AI agents. Each day builds upon the previous, covering essential concepts and practical implementations.

### Day 1: Foundations
- **Day 1a: From Prompt to Action** - Build your first AI agent with tool capabilities
- **Day 1b: Agent Architectures** - Understanding different agent design patterns

### Day 2: Tools & Integration
- **Day 2a: Agent Tools** - Equipping agents with external capabilities
- **Day 2b: Agent Tools Best Practices** - Optimizing tool usage and performance

### Day 3: State & Context
- **Day 3a: Agent Sessions** - Managing conversation context and state
- **Day 3b: Agent Memory** - Implementing persistent memory systems

### Day 4: Quality & Monitoring
- **Day 4a: Agent Observability** - Monitoring and debugging agent behavior
- **Day 4b: Agent Evaluation** - Testing and validating agent performance

### Day 5: Advanced Topics
- **Day 5a: Agent-to-Agent Communication** - Building multi-agent systems
- **Day 5b: Agent Deployment** - Deploying agents to production

## 🚀 Getting Started

### Prerequisites

- Python 3.13 or higher
- [uv](https://docs.astral.sh/uv/) package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/viswanathanTJ/google-5-day-ai-course.git
   cd google-5-day-ai-course
   ```

2. **Install dependencies using uv**
   ```bash
   uv sync
   ```

3. **Set up your API key**
   
   Create a `.env` file in the project root:
   ```bash
   GOOGLE_API_KEY=your_api_key_here
   ```
   
   Get your API key from [Google AI Studio](https://aistudio.google.com/apikey)

4. **Launch Jupyter**
   ```bash
   uv run jupyter lab
   ```

## 📦 Dependencies

This project uses the following main dependencies:

- `google-adk[eval]>=1.18.0` - Google's Agent Development Kit
- `ipykernel>=7.1.0` - Jupyter kernel support
- `ipython>=9.7.0` - Interactive Python
- `jupyter-server>=2.17.0` - Jupyter notebook server
- `python-dotenv>=1.2.1` - Environment variable management

## 🎯 Learning Path

Follow the notebooks in order for the best learning experience:

1. Start with Day 1a to understand basic agent concepts
2. Progress through each day sequentially
3. Complete the exercises in each notebook
4. Experiment with the code examples
5. Build your own agents as you learn

## 📝 Key Concepts Covered

- **Agent Basics**: Prompts, actions, and tool usage
- **Architecture Patterns**: Different agent design approaches
- **Tool Integration**: Connecting agents to external services
- **State Management**: Sessions and persistent memory
- **Observability**: Monitoring and debugging techniques
- **Evaluation**: Testing and validating agent behavior
- **Multi-Agent Systems**: Agent-to-agent communication
- **Production Deployment**: Best practices for deploying agents

## 🔧 Project Structure

```
.
├── Day_1a_From_Prompt_to_Action.ipynb
├── day-1b-agent-architectures.ipynb
├── day-2a-agent-tools.ipynb
├── day-2b-agent-tools-best-practices.ipynb
├── day-3a-agent-sessions.ipynb
├── day-3b-agent-memory.ipynb
├── day-4a-agent-observability.ipynb
├── day-4b-agent-evaluation.ipynb
├── day-5a-agent2agent-communication.ipynb
├── day-5b-agent-deployment.ipynb
├── blog.md                           # Sample multi-agent output
├── pyproject.toml                    # Project dependencies
└── README.md                         # This file
```

## 🤝 Contributing

This is a learning repository. Feel free to:
- Open issues for questions or clarifications
- Submit PRs for improvements or corrections
- Share your agent implementations

## 📄 License

Licensed under the Apache License, Version 2.0. See notebook headers for full license text.

## 🔗 Resources

- [Google ADK Documentation](https://google.github.io/adk-docs/)
- [Google AI Studio](https://aistudio.google.com/)
- [Kaggle 5-Day Agents Course](https://www.kaggle.com/learn-guide/5-day-genai)

## 💡 Tips

- Use the notebooks interactively - run and modify the code
- Experiment with different prompts and tools
- Check the blog.md file for example multi-agent system output
- Join the community discussions for help and sharing

---

**Happy Agent Building! 🚀**