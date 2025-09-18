# AI Enhanced SOC Automation Lab

## Objective
This SOC Automation Project Updated lab empowers learners to set up and automate core SOC workflows—now enhanced with AI agents. The initiative merges classic SOC practices like event ingestion and alert triage with next-generation machine and reasoning agents, transforming how analysts detect, investigate, and respond to security threats. Labs provide hands-on experience in orchestrating automated workflows and integrating AI triage, reducing manual workload while increasing precision and speed.

## Skills Learned
- Architecting SOAR workflows with AI, leveraging large language models for automated triage recommendations.
- Advanced integration of SIEM, SOAR, and case management tools with AI prompt engineering, Assistant APIs, and autonomous alert dispositioning.
- Building and tuning event-driven playbooks using reasoning agents (ReAct, Chain-of-Thought) to dynamically adapt to SOC data and context.
- Extracting context and enrichment from disparate sources (EDR, SIEM, threat intelligence) using agentic retrieval-augmented generation (RAG).
- Creating closed-loop feedback systems—AI curates recommendations, analysts verify, detection engineers fine-tune.
- Hands-on experience in orchestrating fully automated investigation, reporting, and remediation actions using open-source and AI-driven tools.

## Tools Used
- OpenAI GPT-4o (or similar LLM): SOC analyst-like assistant for alert triage, evidence evaluation, and automated recommendations.
- Wazuh: SIEM platform for real-time log ingestion and alerting.
- Shuffle (SOAR): Orchestrating response workflows with AI agent integration.
- TheHive: Case management, enhanced with AI agent enrichment.
- VirusTotal / OSINT APIs: Automated enrichment of file hashes, IPs, and domains.
- Agentic Reasoning Platforms (ReAct, Chain-of-Thought, RAG): Allow AI agents to combine logic with knowledge retrieval, tool use, and historical memory.

## Lab Structure
Project exercises and guided labs are based on the updated MyDFIR SOC Automation series, including:
- Initial SOC setup and infrastructure (Windows client, SIEM, SOAR, case management).
- AI agent configuration: training LLMs with SOC-specific prompts to handle alert triage, recommend actions, and summarize context.
- Automated event ingestion from endpoints and enrichment (Sysmon, security logs, Mimikatz telemetry).
- Building SOAR workflows that route alerts through automated logic, escalate legitimate incidents, and manage noise.
- Implementing AI-powered feedback loops: agent triages alert, analyst verifies, detection rules adjusted.
- End-to-end use cases in autonomous incident detection, analysis, and response.
