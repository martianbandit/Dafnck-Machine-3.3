---
phase: P05
step: S17
task: T05
task_id: P05-S17-T05
title: Real-Time Alerting and Incident Management
agent:
  - "@health-monitor-agent"
  - "@devops-agent"
  - "@performance-load-tester-agent"
  - "@data-analyst-agent"
previous_task: P05-S17-T04
next_task: P05-S17-T06
version: 3.1.0
source: Step.json
---

# Super Prompt
You are @health-monitor-agent, collaborating with @devops-agent, @performance-load-tester-agent, and @data-analyst-agent. Your mission is to implement a real-time alerting system and incident management for DafnckMachine v3.1, ensuring proactive detection, rapid response, and robust escalation. Document all alerting and incident management procedures with clear guidelines and best practices. Save all outputs to the specified documentation directory and update workflow progress upon completion.

1. **Documentation Reference**
   - All outputs must be saved in: `01_Machine/04_Documentation/vision/Phase_5/17_Monitoring_Analytics/`

2. **Collect Data/Input**
   - Reference alerting and incident management requirements
   - Review previous alerting, incident, and escalation documentation if available
   - Gather standards for alert rules, notification channels, and escalation workflows

3. **Save Output**
   - Save alerting system implementation: `Alerting_System_Implementation.md`
   - Save incident management framework: `Incident_Management_Framework.json`
   - Save incident response procedures: `Incident_Response_Procedures.md`
   - Save escalation workflows: `Escalation_Workflows.json`
   - Minimal JSON schema example for incident management framework:
     ```json
     {
       "alertRules": ["cpuHigh", "memoryLeak", "downtime"],
       "notificationChannels": ["email", "slack"],
       "escalationProcedures": true,
       "incidentResponseIntegration": true
     }
     ```

4. **Update Progress**
   - Upon completion, update `Step.json` and `DNA.json` to mark this task as SUCCEEDED
   - Proceed to the next task: P05-S17-T06

5. **Self-Check**
   - [ ] All required files are present in the documentation directory
   - [ ] Alerting and incident management systems are implemented and operational
   - [ ] Documentation and configs are clear and complete
   - [ ] Task status updated in workflow tracking files 