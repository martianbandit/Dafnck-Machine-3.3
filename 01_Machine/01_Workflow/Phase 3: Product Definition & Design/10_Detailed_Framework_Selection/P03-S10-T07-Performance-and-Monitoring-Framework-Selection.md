---
phase: P03
step: S10
task: T07
task_id: P03-S10-T07
title: Performance and Monitoring Framework Selection
agent: ["@performance-optimization-agent", "@system-architect-agent", "@development-orchestrator-agent", "@technology-advisor-agent", "@security-auditor-agent"]
previous_task: P03-S10-T06
next_task: P03-S10-T08
version: 3.1.0
source: Step.json
orchestrator: "@uber-orchestrator-agent"
---

# Super Prompt
@performance-optimization-agent (lead), with support from @system-architect-agent, @development-orchestrator-agent, @technology-advisor-agent, and @security-auditor-agent: Select and document performance monitoring, optimization, and caching frameworks for DafnckMachine v3.1. Document all findings, configurations, and selection decisions with clear rationale and evidence. Output all specifications, configuration guides, and analysis to the required files. Communicate blockers or gaps in requirements immediately.

1. **Documentation Reference**
   - Documentation in  `01_Machine/04_Documentation/Doc/Phase_3/10_Detailed_Framework_Selection/`

2. **Collect Data/Input**
   - Gather system health, performance, and scalability requirements from previous steps and team input.
   - Collect preferences and constraints regarding monitoring, optimization, and caching tools.

3. **Save Output**
   - 01_Machine/04_Documentation/vision/Phase_3/10_Detailed_Framework_Selection/Performance_Monitoring_Tools.md (Markdown)
   - 01_Machine/04_Documentation/vision/Phase_3/10_Detailed_Framework_Selection/Monitoring_Framework_Specs.json (JSON, schema: {"tools": [string], "metrics": [string], "config": object, "alerting": [string]})
   - 01_Machine/04_Documentation/vision/Phase_3/10_Detailed_Framework_Selection/Optimization_Framework_Selection.md (Markdown)
   - 01_Machine/04_Documentation/vision/Phase_3/10_Detailed_Framework_Selection/Caching_Solutions_Analysis.json (JSON, schema: {"solution": string, "strategy": string, "config": object})

4. **Update Progress**
   - Mark this task as done in Step.json and DNA.json when all outputs are complete and reviewed.

5. **Self-Check**
   - [ ] Are all required output files present and complete?
   - [ ] Is the monitoring and optimization rationale clearly documented?
   - [ ] Are configuration guides and analysis justified and reproducible?
   - [ ] Have all blockers and requirements been communicated and addressed? 