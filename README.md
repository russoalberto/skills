# skills

Agent-agnostic skills for AI coding assistants (OpenCode, Claude Code, Copilot CLI, Gemini CLI, and others). Each skill provides specialized instructions and workflows for a specific domain.

## Skills

| Skill | Description |
|-------|-------------|
| **backend-architect** | Design APIs, review backend architecture, establish service boundaries, choose between architectural patterns |
| **cicd-automation** | Design CI/CD pipelines, containerize applications, automate deployments, set up build/test/release workflows |
| **cloud-infrastructure** | Provision cloud resources, design network topology, write Terraform/OpenTofu modules, plan multi-cloud architecture |
| **database-expert** | Optimize queries, design schemas, plan migrations, choose between SQL/NoSQL storage solutions |
| **devops-safety** | Execute infrastructure changes safely, run destructive commands, manage production environments, deploy to critical systems |
| **frontend-expert** | Build UI components, optimize frontend performance, implement responsive design, set up frontend architecture |
| **security-auditor** | Audit code for vulnerabilities, implement authentication/authorization, review security posture, handle sensitive data |
| **sre-observability** | Set up monitoring and alerting, define SLOs/SLIs, investigate production incidents, design observability strategy |

## Install

```bash
npx skills add russoalberto/skills
```

## Usage

Skills auto-load when a task matches their description. Load one explicitly with your agent's skill command (e.g., `/skill` in OpenCode, `Skill` tool in Claude Code).

## Making agent-agnostic skills work with any agent

The tools referenced in SKILL.md files use Claude Code naming conventions. If your agent uses different tool names (e.g., Copilot CLI, Gemini CLI), check the [superpowers references](https://github.com/obra/superpowers) for tool mappings.
