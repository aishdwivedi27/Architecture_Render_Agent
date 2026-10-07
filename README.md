# Architecture Render Agent

Automated architectural drawing analysis and visualisation agent.

## Development environment

- Windows
- Docker Desktop
- WSL 2
- n8n
- OpenAI API
- VS Code
- GitHub
- Claude Code

## Project structure

- input/ - incoming architectural drawings
- output/ - completed renders
- jobs/ - job-specific working data
- 
- references/ - project reference material
- knowledge/ - agent knowledge base (proprietary, not included in this repository)
  - approved/ - approved agent knowledge
  - proposed/ - proposed knowledge changes for human review
- workflows/ - automation workflows
- schemas/ - structured data schemas
- scripts/ - supporting scripts
- logs/ - execution logs
# docker composer up -d
# docker compose ps      to check 
# docker composer down 