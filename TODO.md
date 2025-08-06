# TODO - Claude Template

## 🔴 High Priority

### 1. GitHub CLI Installation
- [ ] Install GitHub CLI (`sudo pacman -S github-cli`)
- [ ] Authenticate with `gh auth login`
- [ ] Test issue creation from Issue Tracker agent
- [ ] Verify orchestrator can delegate to Issue Tracker properly

## 🟡 Medium Priority

### 2. Issue Tracking Integration
- [ ] Complete GitHub Issues workflow testing
- [ ] Create automatic TODO scanning on session end
- [ ] Link commits to issues automatically
- [ ] Test batch issue creation from multiple TODOs

### 3. Documentation
- [ ] Create user guide for managed sessions
- [ ] Document agent coordination flow
- [ ] Add troubleshooting guide for common issues
- [ ] Create examples of different project types using template

## 🟢 Nice to Have

### 4. Future Enhancements
- [ ] Add support for GitLab issues
- [ ] Create project board integration
- [ ] Add milestone management
- [ ] Implement PR template generation
- [ ] Add support for multiple git remotes
- [ ] Create backup/restore functionality for sessions
- [ ] Add metrics dashboard for productivity tracking
- [ ] Implement voice notes to session summary
- [ ] Create integration with external task managers
- [ ] Add AI-powered code review suggestions

## 📝 Session Notes

### Session: 2025-08-06
- **Completed**: Full session orchestration system with LLM Project Manager
- **Blocker**: GitHub CLI not installed, needed for issue creation
- **Next Step**: Install `gh` CLI and test issue creation workflow

### Known Issues
- GitHub CLI (`gh`) needs manual installation
- Issue creation tested in theory but not in practice
- Need to verify full orchestration → issue creation flow

---
*Last updated: 2025-08-06 by Session End Manager*