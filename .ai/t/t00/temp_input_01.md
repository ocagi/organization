# Requirement 1
I need you to create a new issue for this repo. The issue should state that we need to do the initial setup of the founding documents. Founding documents are the Open Collect AGI manifesto and the AI privacy document. 
After you created that initial issue, we should create a new branch to solve that issue. In the branch, we need to commit ai_privacy.md ,  open_collective_agi_manifesto.md, and README.md, and then wait for review and merge by human.

# Requirement 2
I need to quickly state the main rules for this git repository. Please, summarize these rules, and add them to a file explaining how to contribute. The file should be clear, conscise, and with a vewry high SNR.
For this requirement: 1. open a new issue #2 and write an informal and concise requirement. 2. create a new local branch to fix the issue #2 3. fix the issue locally, interactively with the human operator, which whill need to provide a pre-commit review. 4. when the human-op agrees, push the branch remotely and open a PR.


# Requirement 3
I need you to create a new issue for this repo. This should state that we need a basic framework for interacting with the AI, and to make this persistent we need to use a folder called `.ai` containing sessions and temporary sessions with the AI. 
After creating the issue, you shall create a new branch to fix that issue. Then, you need to add a file.gitkeep under the folders `.ai/s`, `.ai/t`. Then you should commit the `.ai/README.md`
Perhaps you want to integrate the .ai/README to make it clearer and concise. If so, ask the human operator review before committing and pushing. Review and merge will be done by humans.

# Requirement 4
Scope of this requirement is to structure the interaction between agents and humans. We need to provide an example `.ai/agent/human_example.md`. The idea is the human operator renames the example file and then edits it with their own preferences, without committing the file. 
- Examples should be simple to read and to modify for the human. The human should be able to create a copy with its own parameter and not commit his own copy in the repository. 
- AI agents should be able to index the file and understand which are the agents and how they collaborate together - what is their role. 


Here is an example of human agents interaction that we use as example case, and which we'll structure in the example file: 

```md
You will help a human user, let's call it `human` working on this repository. I assume several humans will work on this repo, and each one will use a different way of interacting with agents. The description below affects the local human only.

`human` uses the following setup: 
- `human` is the orchestrator: has an high-level overview, delegate tasks, and might want refined control over some details. Very often will select one of the agents to work with. Typically uses (a) an agent that can handle large contexts and has i/o access, (b) an agent with i/o access with smaller context that can handle average-complexity tasks, (c) one or more other agents for smaller tasks, such as collecting voice input, preparing documents to be used in the codebase, etc. 

The specific setup is something like this:
- `SA` (Selected Agent) - Claude Code v.2.0.27, using Sonnet 4.5 - Model with larger context and file i/o access to repository and gitub. Handles the most complex tasks, and can act as a coordinator and delegate to other agents, typically when requested by human. 
- `CC2`: (Claude on Cursor 2) - Claude 4.5 sonnet used through Cursor and its MCP interface - Has file i/o access and good accuracy, but typically has a smaller context. Can handle tasks of average complexity.
- `G4T`: ChatGPT (GPT-4 Turbo) - ChatGPT 4-Turbo Accessed via web interface, used to summarize voice notes into text files.
- `OA`: Other Agents

```

For this requirement, please add a github issue with a good description of this problem, and an outline of the solution. 
Then, create a new branch to fix that issue. When done, interactively ask the human operator for pre-commit review. 
When done, commit and push. Review and merge to main will be done by humans.


# Requirement 5

We need to add an initial readme, and the first works about license, and code of conduct. For this we need to create a new issue, and a new branch for that. The issue will be completed by a different agent: CC2 (Claude Code on Cursor)
SA will perform a pre-commit review, and if changes are suggested/ needed, then an interactive session with the human operator should be done. 
When all is set, after human pre-commit check, we can commit and push. 

# Requirement 6
We need to setup spaces for discussion. I would like to setup github discussions and a discord server. 
Please, open a new issue in the repository. Scope of the issue is to write an output documents in .at/t/t00 : [setup_community_discussions.md](setup_community_discussions.md)
The document should explain how to create github discussions and how to create a discord server to host community interaction.
Once the document is created, an human will complete the setup by enabling the [GitHub Discussion](https://github.com/ocagi/organization/discussions)
