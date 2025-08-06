# Prime - Session Initialization

## 🚀 Session Start Instructions

To start a managed session with full orchestration:
1. Tell Claude: "Read prime.md and start managed session"
2. The LLM Project Manager will take over and orchestrate everything

## 📋 Current Session Objectives

<!-- Add your session goals here -->
- [ ] Task 1: [Describe your first task]
- [ ] Task 2: [Describe your second task]
- [ ] Task 3: [Describe your third task]

## 🎯 Project Context

<!-- Add relevant project context here -->
### Current State:
- What's working well
- What needs improvement
- Known issues

### Priority Focus:
1. High priority item
2. Medium priority item
3. Nice to have

## 🔧 Session Configuration

### Preferred Agents:
<!-- Uncomment the agents you want to prioritize -->
<!-- - git-expert (for git operations) -->
<!-- - issue-tracker (for TODO management) -->
<!-- - code-error-detective (for debugging) -->
<!-- - pragmatic-web-dev (for web development) -->
<!-- - ux-focused-frontend-dev (for UI work) -->

### Session Preferences:
- Auto-commit at end: true
- Create issues for TODOs: false
- Run tests automatically: true
- Clean up temp files: true

## 📝 Notes from Previous Session

<!-- This section is for handoff notes -->
<!-- The session-end-manager will update this -->

### Last Session Summary:
- Date: [Previous session date]
- Completed: [What was accomplished]
- Pending: [What needs to continue]

### Important Decisions:
- [Any decisions that affect current work]

### Blockers Identified:
- [Any blockers from last session]

## 🚦 Quick Start (Without Manager)

If you prefer to work without the project manager:
- Just start giving Claude your requests normally
- The session tracking will still work in the background
- At session end, cleanup will still be suggested

## 🤖 Invoke Project Manager

To start a fully managed session, say:
**"Please use the llm-project-manager agent to orchestrate this session based on prime.md"**

The Project Manager will:
1. Read this file for context
2. Create a comprehensive task list
3. Coordinate specialized agents
4. Manage the entire session lifecycle
5. Ensure clean session closure with git commits

---
*This file is your session control center. Update it with your objectives before starting a managed session.*