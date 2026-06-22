# ITSM Automation Portfolio Project

## Overview

This project demonstrates the implementation of an IT Service Management (ITSM) Automation Solution using ServiceNow. The solution automates service request fulfilment, catalogue task management, approval workflows, and integrates with Jira for issue tracking.

The project was built on a ServiceNow Personal Developer Instance (PDI) and showcases workflow automation, request management, task lifecycle handling, and REST API integration.

## Project Objectives

- Automate Service Catalogue Request Processing
- Implement Catalogue Item and Request Workflows
- Manage Approval Processes
- Automate Catalogue Task Lifecycle
- Integrate ServiceNow with Jira using REST APIs
- Demonstrate ITSM best practices

## Technologies Used

### ServiceNow
- Service Catalogue
- Catalog Items
- Requested Items (RITM)
- Catalog Tasks (SCTASK)
- Workflow Engine
- Flow Designer
- Business Rules
- REST Messages
- Basic Authentication

### Jira
- Scrum Project
- Issue Tracking
- Sprint Board

### Other Tools
- GitHub
- Loom (Documentation Video)

## Project Workflow

### Service Catalogue Request Flow

1. User submits a catalogue request.
2. Request (REQ) is generated.
3. Requested Item (RITM) is created.
4. Catalogue Task (SCTASK) is generated.
5. The approval process is executed.
6. Task is completed.
7. RITM moves to Closed Complete.
8. Request moves to the Approved/Completed state.

## Jira Integration

A REST Message was configured in ServiceNow to communicate with Jira.

### Features

- Jira REST API Integration
- Basic Authentication Configuration
- HTTP POST Method Configuration
- API Testing
- Successful Response Validation

## Key Records Created

| Record Type | Example |
|------------|-----------|
| Request | REQ0000001 |
| Requested Item | RITM0000001 |
| Catalog Task | TASK0000001 |
| Incident | INC0010001 |
| Jira Issues | SCRUM-1, SCRUM-2 |

## Screenshots

### Phase 1 – Setup

- ServiceNow PDI Setup
- Catalog Item Configuration
- Service Catalogue Configuration

### Phase 2 – Request Management

- Request Creation
- Requested Item Generation
- Catalogue Task Generation

### Phase 3 – Workflow Automation

- Approval Process
- Task Completion
- RITM Closure
- Request Closure

### Phase 4 – Jira Integration

- Jira Project Board
- REST Message Setup
- Authentication Configuration
- API Testing
- ServiceNow ↔ Jira Integration

## Jira Integration Screenshots

| Screenshot |
|------------|
| 26_jira_project.png |
| 27_rest_message_setup.png |
| 28_authentication_setup.png |
| 29_api_testing.png |
| 30_servicenow_jira_integration.png |

## Repository Structure

text
serviceNow-itsm-automation-portfolio/
│
├── README.md
│
├── screenshots/
│   ├── phase1/
│   ├── phase2/
│   ├── phase3/
│   └── phase4-jira-integration/
│
├── workflows/
│   └── workflow_exports.xml
│
└── docs/
    └── project_summary.pdf


## Results

### Successfully Implemented

- Service Catalogue Request Management
- Catalogue Task Automation
- Request Lifecycle Tracking
- Approval Workflow
- Catalogue Task Closure
- RITM Closure
- Request Completion
- Jira REST Integration
- API Communication Testing

## Learning Outcomes

Through this project, I gained hands-on experience with:

- ServiceNow Administration
- ITSM Processes
- Workflow Automation
- Catalog Management
- REST API Integration
- Jira Integration
- Business Process Automation
- Service Operations

---

## Project Status

✅ Completed

This project successfully demonstrates ITSM workflow automation and ServiceNow-Jira integration using a Personal Developer Instance (PDI).
