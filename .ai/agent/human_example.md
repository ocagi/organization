# Agent/Human Interaction Setup

## Overview

This file describes how a human operator collaborates with AI agents on this repository. Each human working on this repo may use a different agent setup.

**Instructions for humans:**
1. Copy this file to `.ai/agent/human_<yourname>.md` (e.g., `human_alice.md`)
2. Edit your copy with your specific agent configuration
3. Do NOT commit your personal copy to the repository
4. Personal copies are ignored by [.gitignore](.gitignore).

**Instructions for AI agents:**
Index this file to understand the collaboration structure, agent roles, and how to coordinate with other agents.

---

## Human Operator Role

`human` is the orchestrator with high-level overview who:
- Delegates tasks to appropriate agents
- Maintains refined control over specific details
- Selects agents based on task complexity and requirements

Typically uses:
- An agent with large context and I/O access for complex tasks
- An agent with smaller context for average-complexity tasks
- Specialized agents for specific tasks (voice input, document prep, etc.)

---

## Agent Setup

### SA (Selected Agent)
- **Tool**: Claude Code v.2.0.27
- **Model**: Claude Sonnet 4.5
- **Capabilities**:
  - Large context window
  - File I/O access to repository
  - GitHub integration
  - Can act as coordinator and delegate to other agents
- **Use cases**: Most complex tasks, orchestration, GitHub operations

### CC2 (Claude on Cursor)
- **Tool**: Cursor with MCP interface
- **Model**: Claude Sonnet 4.5
- **Capabilities**:
  - File I/O access
  - Good accuracy
  - Smaller context window
- **Use cases**: Average-complexity tasks, focused edits

### G4T (ChatGPT 4 Turbo)
- **Tool**: ChatGPT web interface
- **Model**: GPT-4 Turbo
- **Capabilities**:
  - Voice input processing
  - Text summarization
- **Use cases**: Summarizing voice notes into text files

### OA (Other Agents)
- Additional specialized agents as needed
- Document specific agents here when added

---

## Collaboration Workflow

1. **Human** write requirements, selects appropriate agent(s)
2. **Selected agent** performs work or coordinates with other agents
3. **Handoffs** between humans and agents documented in `.ai/s/` or `.ai/t/` sessions
4. **Human** reviews outputs and provides guidance
5. Results committed following the contribution guidelines

---

## Notes

- This is an example configuration - customize for your workflow
- Keep agent capabilities and versions up to date
- Document any special coordination patterns you develop