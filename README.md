# AutoCarry

## Purpose

Implement AutoCarry by running the prompt.txt file in the workspace. 

This solution automates the migration of unfinished work items between sprints/iterations (especially suitable for a POD model), integrates AI-assisted scripts with the GitHub Copilot Agent and Azure DevOps MCP, and provides intelligent detection and migration, automatic updates, and real-time notifications. Running prompt.txt causes the Copilot Agent to read the workspace and execute the steps described there, eliminating the manual overhead of handoffs and logging, and improving planning efficiency, team satisfaction, and delivery continuity. Ensure the Copilot Agent has permission to access the repository and read prompt.txt, and that ADO MCP is authenticated to perform queries and updates on behalf of the current user.

## Prerequisites

- Set up GitHub Copilot Agent: <https://code.visualstudio.com/docs/copilot/setup>
- Install ADO MCP: <https://github.com/microsoft/azure-devops-mcp>

## Run steps

Send the following to the GitHub Copilot Agent:

`Please read the prompt.txt in your workspace and follow the steps described there`
