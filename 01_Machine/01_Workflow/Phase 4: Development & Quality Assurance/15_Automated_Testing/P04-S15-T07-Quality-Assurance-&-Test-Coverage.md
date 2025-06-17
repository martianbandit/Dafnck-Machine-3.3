---
phase: P04
step: S15
task: T07
task_id: P04-S15-T07
title: Quality Assurance & Test Coverage
<<<<<<< HEAD
agent:
  - "@test-orchestrator-agent"
  - "@functional-tester-agent"
=======
>>>>>>> 8f6410b869c68e2dec6a6798282a4437e78b5f85
previous_task: P04-S15-T06
next_task: P04-S15-T08
version: 3.1.0
source: Step.json
<<<<<<< HEAD
---

# Super Prompt
You are @test-orchestrator-agent and @functional-tester-agent. Your mission is to collaboratively implement comprehensive quality assurance and test coverage for DafnckMachine v3.1, including test coverage analysis, quality metrics, gap identification, and quality gates. Ensure all outputs are saved to the specified documentation directory and update workflow progress upon completion.

1. **Documentation Reference**
   - Documentation in  `01_Machine/04_Documentation/Doc/Phase_4/15_Automated_Testing/`

2. **Collect Data/Input**
   - Reference quality assurance and test coverage requirements
   - Review previous coverage analysis and quality metrics documentation if available
   - Gather standards for coverage reporting, quality gates, and validation criteria

3. **Save Output**
   - Save test coverage analysis: `Test_Coverage_Analysis.md`
   - Save quality metrics framework: `Quality_Metrics_Framework.json`
   - Save quality gates implementation: `Quality_Gates_Implementation.md`
   - Save validation criteria: `Validation_Criteria.json`
   - Minimal JSON schema example for quality metrics:
     ```json
     {
       "metric": "codeCoverage",
       "value": 92.5,
       "threshold": 90,
       "status": "pass"
     }
     ```

4. **Update Progress**
   - Upon completion, update `Step.json` and `DNA.json` to mark this task as SUCCEEDED
   - Proceed to the next task: P04-S15-T08

5. **Self-Check**
   - [ ] All required files are present in the documentation directory
   - [ ] Coverage analysis and quality gates are comprehensive and pass
   - [ ] Documentation and configs are clear and complete
   - [ ] Task status updated in workflow tracking files 
=======
agent: "@test-orchestrator-agent"
orchestrator: "@uber-orchestrator-agent"
---
## Output Artifacts Checklist
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Test_Coverage_Analysis.md — Test_Coverage_Analysis.md (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Metrics_Framework.json — Quality_Metrics_Framework.json (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Gates_Implementation.md — Quality_Gates_Implementation.md (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Validation_Criteria.json — Validation_Criteria.json (missing)

# Mission Statement
Implement comprehensive quality assurance with test coverage analysis, quality metrics, coverage reporting, and gap analysis for quality validation in DafnckMachine v3.1.

# Description
This task covers the development and execution of quality assurance processes, including test coverage analysis, quality metrics, coverage reporting, and gap analysis to ensure comprehensive quality validation.

# Super-Prompt
You are @test-orchestrator-agent responsible for implementing quality assurance and test coverage for DafnckMachine v3.1. Your mission is to develop and execute test coverage analysis, quality metrics, and reporting to ensure comprehensive quality validation and gap identification.

# MCP Tools Required
- edit_file
- run_terminal_cmd

# Result We Want
- Comprehensive test coverage analysis and quality metrics
- Gap identification and quality reporting implemented

# Add to Brain
- Quality assurance and test coverage analysis

# Documentation & Templates
- [Test_Coverage_Analysis.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Test_Coverage_Analysis.md)
- [Quality_Metrics_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Metrics_Framework.json)
- [Quality_Gates_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Gates_Implementation.md)
- [Validation_Criteria.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Validation_Criteria.json)

# Primary Responsible Agent
@test-orchestrator-agent

# Supporting Agents
- @functional-tester-agent

# Agent Selection Criteria
The @test-orchestrator-agent is selected for its expertise in quality assurance, coverage analysis, and reporting. The @functional-tester-agent supports with test development and validation.

# Tasks (Summary)
- Develop and execute test coverage analysis and reporting
- Implement quality gates and validation

# Subtasks (Detailed)
## Subtask 1: Test Coverage Analysis & Reporting
- **ID**: P04-S15-T07-S01
- **Description**: Develop test coverage analysis with quality metrics and gap identification.
- **Agent**: @test-orchestrator-agent
- **Documentation**: [Test_Coverage_Analysis.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Test_Coverage_Analysis.md), [Quality_Metrics_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Metrics_Framework.json)
- **Steps**:
    1. Implement test coverage analysis with quality metrics and reporting (edit_file)
    2. Generate coverage reports and analyze quality metrics (run_terminal_cmd)
- **Success Criteria**:
    - Test coverage analysis documented and covers code coverage, quality metrics, and gap analysis
    - Coverage analysis completed successfully

## Subtask 2: Quality Gates & Validation
- **ID**: P04-S15-T07-S02
- **Description**: Develop quality gates with validation criteria and automated quality checks.
- **Agent**: @test-orchestrator-agent
- **Documentation**: [Quality_Gates_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Gates_Implementation.md), [Validation_Criteria.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Validation_Criteria.json)
- **Steps**:
    1. Implement quality gates with validation criteria and automated checks (edit_file)
    2. Configure release criteria and quality validation workflows (run_terminal_cmd)
- **Success Criteria**:
    - Quality gates documented and cover validation rules, automated checks, and release criteria
    - Quality gates configured successfully

# Rollback Procedures
- Debug and fix failing coverage or quality gates
- Revert to previous implementation if validation fails

# Integration Points
- Quality assurance ensures comprehensive testing and quality validation

# Quality Gates
- All coverage and quality gates pass

# Success Criteria
- Application meets quality and coverage requirements

# Risk Mitigation
- Escalate to @coverage-analysis-lead or @quality-gates-lead if tests fail after 3 attempts

# Output Artifacts
- [Test_Coverage_Analysis.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Test_Coverage_Analysis.md)
- [Quality_Metrics_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Metrics_Framework.json)
- [Quality_Gates_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Quality_Gates_Implementation.md)
- [Validation_Criteria.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Validation_Criteria.json)

# Next Action
Develop and execute test coverage analysis and quality gates with @test-orchestrator-agent

# Post-Completion Action
Proceed to P04-S15-T08-CI-CD-Testing-Integration.md 
>>>>>>> 8f6410b869c68e2dec6a6798282a4437e78b5f85
