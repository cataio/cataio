# Cata Sarafoleanu

I threat model AI agents. I also build them, which is how I know where they break.

My first internet was two Unix boxes exchanging email over a phone line with UUCP, before browsers existed. Since then I have caught infrastructure waves early: routing to CCIE #21712, telco through 5G, then cloud before cloud security had a name. The pattern is consistent: technology reaches production before security catches up.

Today that wave is AI agents. I run autonomous systems with real permissions and document what breaks: trust boundaries, token custody, harness design, MCP servers, memory, and blast radius. When your agent calls a third-party tool server, your trust boundary extends to someone else's infrastructure.

I have led security architecture, SOC, and incident response programs at enterprise scale across cloud and multi-cloud environments. The principle I keep applying: keep detections deterministic, use automation for enrichment and orchestration, and use AI where reasoning over context actually helps analysts move faster.

I work at the point where production AI systems meet real security architecture.

## What I work on

- Agent harness security and MCP server trust boundaries
- Token custody and permission models for autonomous systems
- Detection engineering: deterministic detections, automated enrichment, AI as the reasoning layer
- Cloud and Kubernetes security architecture
- Monitoring agent workloads in production

## Featured work

- [AI Security Monitoring Playbook](https://github.com/cataio/ai-security-monitoring-playbook) - practical guidance for agent harness security and monitoring
- [Agent Harnesses Are the New Attack Surface](https://sarafoleanu.com/blog/ai-agents/agent-harnesses-attack-surface)
- [Your AI Coding Agent Is an Attack Surface](https://sarafoleanu.com/blog/ai-agents/coding-agent-attack-surface)
- [Monitoring AI Agents in EKS](https://sarafoleanu.com/blog/sec-monitoring/monitoring-ai-agents-eks)

## Current focus

The questions most teams skip on the first pass:

- What permissions does this agent actually have?
- Where do the tokens live?
- What is the blast radius when the wrong content steers it?
- When your agent calls a third-party MCP server, whose infrastructure are you trusting?
- How do you monitor and audit what an autonomous workload actually did?

## Credentials

CCIE #21712
CISSP
CISM
AWS Solutions Architect

## Writing

I write at [sarafoleanu.com](https://sarafoleanu.com) about AI agent security, cloud-native monitoring, and the architecture decisions that determine whether systems are usable and defensible.
