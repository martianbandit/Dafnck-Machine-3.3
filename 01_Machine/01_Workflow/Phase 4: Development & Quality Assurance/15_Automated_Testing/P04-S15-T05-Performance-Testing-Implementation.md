---
phase: P04
step: S15
task: T05
task_id: P04-S15-T05
title: Performance Testing Implementation
<<<<<<< HEAD
agent:
  - "@performance-load-tester-agent"
  - "@test-orchestrator-agent"
=======
>>>>>>> 8f6410b869c68e2dec6a6798282a4437e78b5f85
previous_task: P04-S15-T04
next_task: P04-S15-T06
version: 3.1.0
source: Step.json
<<<<<<< HEAD
---

# Super Prompt
You are @performance-load-tester-agent and @test-orchestrator-agent. Your mission is to collaboratively implement comprehensive performance testing for DafnckMachine v3.1, including load testing, stress testing, scalability validation, bottleneck identification, and performance monitoring. Ensure the application meets all performance and scalability requirements. Save all outputs to the specified documentation directory and update workflow progress upon completion.

1. **Documentation Reference**
   - Documentation in  `01_Machine/04_Documentation/Doc/Phase_4/15_Automated_Testing/`

2. **Collect Data/Input**
   - Reference performance testing and monitoring requirements
   - Review previous performance and benchmarking documentation if available
   - Gather standards for load testing, stress testing, and alerting

3. **Save Output**
   - Save performance testing implementation: `Performance_Testing_Implementation.md`
   - Save load testing configuration: `Load_Testing_Configuration.json`
   - Save performance monitoring setup: `Performance_Monitoring_Setup.md`
   - Save benchmarking framework: `Benchmarking_Framework.json`
   - Minimal JSON schema example for load testing config:
     ```json
     {
       "testType": "load",
       "endpoint": "/api/data",
       "concurrentUsers": 100,
       "duration": "5m"
     }
     ```

4. **Update Progress**
   - Upon completion, update `Step.json` and `DNA.json` to mark this task as SUCCEEDED
   - Proceed to the next task: P04-S15-T06

5. **Self-Check**
   - [ ] All required files are present in the documentation directory
   - [ ] Performance tests and monitoring are comprehensive and pass
   - [ ] Documentation and configs are clear and complete
   - [ ] Task status updated in workflow tracking files 
=======
agent: "@performance-load-tester-agent"
orchestrator: "@uber-orchestrator-agent"
---
## Output Artifacts Checklist
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Testing_Implementation.md — Performance_Testing_Implementation.md (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Load_Testing_Configuration.json — Load_Testing_Configuration.json (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Monitoring_Setup.md — Performance_Monitoring_Setup.md (missing)
- [ ] 01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Benchmarking_Framework.json — Benchmarking_Framework.json (missing)

# Mission Statement
Implement comprehensive performance testing with load testing, stress testing, scalability testing, and bottleneck identification for application performance validation in DafnckMachine v3.1.

# Description
This task covers the development and execution of performance tests, including load testing, stress testing, scalability validation, and bottleneck identification to ensure application performance and scalability.

# Super-Prompt
You are @performance-load-tester-agent responsible for implementing performance testing for DafnckMachine v3.1. Your mission is to develop and execute load and stress tests, analyze performance, and identify bottlenecks to ensure the application meets performance standards.

# MCP Tools Required
- edit_file
- run_terminal_cmd

# Result We Want
- Comprehensive performance tests for load, stress, and scalability
- Bottleneck identification and performance validation

# Add to Brain
- Performance testing implementation and analysis

# Documentation & Templates
- [Performance_Testing_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Testing_Implementation.md)
- [Load_Testing_Configuration.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Load_Testing_Configuration.json)
- [Performance_Monitoring_Setup.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Monitoring_Setup.md)
- [Benchmarking_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Benchmarking_Framework.json)

# Primary Responsible Agent
@performance-load-tester-agent

# Supporting Agents
- @test-orchestrator-agent

# Agent Selection Criteria
The @performance-load-tester-agent is selected for its expertise in load, stress, and performance testing. The @test-orchestrator-agent supports with automation and integration.

# Tasks (Summary)
- Develop and execute load and stress tests
- Implement performance monitoring and benchmarking

# Subtasks (Detailed)
## Subtask 1: Load Testing & Stress Testing
- **ID**: P04-S15-T05-S01
- **Description**: Develop performance tests with load testing, stress testing, scalability testing, and bottleneck identification.
- **Agent**: @performance-load-tester-agent
- **Documentation**: [Performance_Testing_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Testing_Implementation.md), [Load_Testing_Configuration.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Load_Testing_Configuration.json)
- **Steps**:
    1. Implement load testing and stress testing with performance validation (edit_file)
    2. Execute performance tests and analyze bottlenecks (run_terminal_cmd)
- **Success Criteria**:
    - Performance testing documented and covers load, stress, scalability, and bottleneck identification
    - Performance tests completed successfully

## Subtask 2: Performance Monitoring & Benchmarking
- **ID**: P04-S15-T05-S02
- **Description**: Develop performance monitoring with benchmarking, alerting, and optimization recommendations.
- **Agent**: @performance-load-tester-agent
- **Documentation**: [Performance_Monitoring_Setup.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Monitoring_Setup.md), [Benchmarking_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Benchmarking_Framework.json)
- **Steps**:
    1. Implement performance monitoring with benchmarking and alerting (edit_file)
    2. Configure optimization recommendations and performance tracking (run_terminal_cmd)
- **Success Criteria**:
    - Performance monitoring documented and covers benchmarks, monitoring, and alerting
    - Performance monitoring configured successfully

# Rollback Procedures
- Debug and fix failing performance tests
- Revert to previous test implementation if performance validation fails

# Integration Points
- Performance testing ensures application scalability and performance standards

# Quality Gates
- All performance tests and monitoring pass

# Success Criteria
- Application meets performance and scalability requirements

# Risk Mitigation
- Escalate to @performance-testing-lead or @monitoring-lead if tests fail after 3 attempts

# Output Artifacts
- [Performance_Testing_Implementation.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Testing_Implementation.md)
- [Load_Testing_Configuration.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Load_Testing_Configuration.json)
- [Performance_Monitoring_Setup.md](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Performance_Monitoring_Setup.md)
- [Benchmarking_Framework.json](mdc:01_Machine/04_Documentation/vision/Phase_4/15_Automated_Testing/Benchmarking_Framework.json)

# Next Action
Develop and execute performance tests with @performance-load-tester-agent

# Post-Completion Action
Proceed to P04-S15-T06-Security-Testing-Implementation.md 
>>>>>>> 8f6410b869c68e2dec6a6798282a4437e78b5f85
