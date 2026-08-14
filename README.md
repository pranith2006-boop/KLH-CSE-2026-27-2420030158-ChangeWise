# ChangeWise: AI-Powered Adaptive Software Change Impact Analysis

## Project Description

ChangeWise is an AI-powered adaptive software change impact analysis system that helps developers understand the impact of a client's requested software change before implementation begins. It connects to an existing GitHub project and analyzes its structure, dependencies, modules, APIs, databases, and related components. Based on the client's change request, ChangeWise identifies potentially affected areas, assesses risks, recommends an implementation sequence, and suggests relevant testing activities.

## Team Details

| Roll Number | Team Member |
|---|---|
| 2420030154 | G. Anusha |
| 2420030288 | G. Harini |
| 2420030533 | P. Chaitra Sree |
| 2420030158 | M. Pranith Reddy |

**Supervisor:** Kalidindi Bhavya Varma

## Abstract

### 1. Problem

Software projects often require changes after they have already been developed and delivered. When a client requests a new feature or modification, developers need to understand which existing modules, dependencies, APIs, databases, and tests may be affected. Identifying these impacts manually can be time-consuming and may lead to missed dependencies, unexpected failures, and inefficient implementation.

### 2. Proposed Solution

ChangeWise is an AI-powered adaptive software change impact analysis system that connects to an existing GitHub project and analyzes its structure, dependencies, and relationships. Developers can enter a new client change request, and ChangeWise evaluates how the requested change may affect the existing software before implementation begins.

### 3. Key Features

ChangeWise identifies potentially affected components, assigns risk levels based on the extent of the impact, explains the relationships between affected components, and recommends an appropriate implementation order. It also suggests relevant test cases and generates an AI-powered change impact report to help developers plan the requested modification.

### 4. Benefits

ChangeWise helps development teams make better decisions before modifying an existing system. It reduces the chances of unexpected failures, saves time in impact analysis, improves testing and implementation planning, and supports safer and more adaptive software evolution in response to changing client requirements.

## Project Objectives

1. Analyze existing software projects by examining their structure, dependencies, modules, APIs, databases, and related components.

2. Analyze client change requests and identify which parts of the existing software may be affected before implementation begins.

3. Use AI to assess change impact and risk, providing explanations for why particular components may be affected.

4. Recommend an implementation sequence so developers know which components should be modified first and which dependent components should follow.

5. Recommend relevant testing activities for affected components to reduce unexpected failures after implementing the requested change.

## Technology Stack

### Frontend

- React
- Vite
- Tailwind CSS

### Backend

- Python
- FastAPI

### AI

- OpenAI API

### Code and Dependency Analysis

- Python AST

### Version Control and Repository Integration

- Git
- GitHub API

### Database

- PostgreSQL
