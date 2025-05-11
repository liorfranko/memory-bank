# Memory Bank

The Memory Bank is a structured documentation system that allows Cursor to maintain context across sessions. It transforms Cursor from a stateless assistant into a persistent development partner that can effectively "remember" your project details over time.

## Key Benefits

- Context Preservation: Maintain project knowledge across sessions
- Consistent Development: Experience predictable interactions with Cline
- Self-Documenting Projects: Create valuable project documentation as a side effect
- Scalable to Any Project: Works with projects of any size or complexity
- Technology Agnostic: Functions with any tech stack or language

## How Memory Bank Works

The Memory Bank isn't a Cursor-specific feature - it's a methodology for managing AI context through structured documentation. When you instruct Cursor to "follow custom instructions," it reads the Memory Bank files to rebuild its understanding of your project.

## Getting Started

### Prerequisites

- Cursor IDE installed on your system
- A project to work on

## Installation

1. Copy the `memory-bank.mdc` file to your `.cursor/rules` directory
2. In Cursor, ask the agent to "please initialize memory bank"

That's it! Memory Bank is now ready to use.

## Note

AI agents can sometimes ignore the Memory Bank. If you find that the agent is not following your instructions, try the following:

1. Make sure the Memory Bank file is in the `.cursor/rules` directory
2. Make sure the Memory Bank file is set to "Always apply"
3. You can also try to ask the agent to "Use the Memory Bank"
