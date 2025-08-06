# Claude Template

A project template with Claude Code hooks for automatic session tracking and cleanup.

## Features

### Automatic File Tracking
- Tracks all files created or edited during a Claude Code session
- Stores tracking data in `.claude/session_files.json`

### Session End Cleanup
- Automatically triggered at session end
- Analyzes files created/modified during the session
- Suggests cleanup actions for temporary files
- Archives session data for history

### Hook System
The template includes several hooks:
- **PreToolUse hooks**: Track Write, Edit, and MultiEdit operations
- **Stop hook**: Triggers session-end cleanup workflow

## Structure

```
.claude/
├── settings.json           # Claude Code configuration
├── hooks/
│   ├── track_file.py      # File tracking during operations
│   ├── session_end.py     # Session end handler
│   └── cleanup_complete.py # Post-cleanup archiver
├── session_files.json     # Current session tracking
├── pending_cleanup.json   # Cleanup marker file
└── archive/               # Historical session data
```

## Usage

1. Clone this template
2. Start working with Claude Code
3. Files will be automatically tracked
4. At session end, cleanup will be suggested
5. Run the cleanup_complete script to archive and reset

## Configuration

The hooks are configured in `.claude/settings.json`. They run automatically without user intervention.

## Session Lifecycle

1. **During Session**: All file operations are tracked
2. **Session End**: Summary is displayed, cleanup agent requested
3. **After Cleanup**: Archive session and reset for next time

## License

MIT