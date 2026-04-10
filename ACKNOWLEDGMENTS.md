# Acknowledgments

DraftFrame is built on the shoulders of these excellent open-source projects:

## [SwiftTerm](https://github.com/migueldeicaza/SwiftTerm)
**Author:** Miguel de Icaza  
**License:** MIT  
Terminal emulator library for Swift. Provides the VT100/xterm-compatible terminal view with full ANSI color support, cursor handling, alternate screen buffer, mouse reporting, and more. The foundation of DraftFrame's terminal experience.

## [Claude Code](https://claude.ai/claude-code)
**Author:** Anthropic  
DraftFrame is designed as a companion app for Claude Code — Anthropic's CLI tool for AI-assisted software development. DraftFrame manages multiple Claude Code sessions in parallel.

## [Scape](https://scape.work)
**Author:** Elliot Nash  
DraftFrame is inspired by Scape, the original multi-session Claude Code terminal. Scape pioneered the concept of parallel agentic terminals with worktree isolation, session monitoring, and a command-center UI for AI-assisted development.

---

## Tools Used in Development

- **Swift Package Manager** — Build system and dependency management
- **Apple Speech Framework** — On-device voice transcription
- **Git** — Worktree management for session isolation
