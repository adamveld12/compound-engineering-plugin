# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-12-11

### Added

- Initial release of Bobsled compound-engineering plugin
- 22 specialized agents for code review, research, design, and workflow
- 17 workflow and utility commands
- 8 skills for code generation and workflow automation
- 2 MCP servers (Playwright, Context7)

### Agents

**Review (9):**
- `agent-native-reviewer` - Verify features are agent-native
- `architecture-strategist` - Analyze architectural decisions
- `code-simplicity-reviewer` - Final pass for simplicity
- `data-integrity-guardian` - Database migrations and data integrity
- `pattern-recognition-specialist` - Analyze code patterns
- `performance-oracle` - Performance analysis and optimization
- `python-reviewer` - Python code review
- `security-sentinel` - Security audits and vulnerability assessments
- `typescript-reviewer` - TypeScript code review

**Research (4):**
- `best-practices-researcher` - Gather external best practices
- `framework-docs-researcher` - Research framework documentation
- `git-history-analyzer` - Analyze git history
- `repo-research-analyst` - Research repository structure

**Design (3):**
- `design-implementation-reviewer` - Verify UI implementations
- `design-iterator` - Iteratively refine UI
- `figma-design-sync` - Synchronize with Figma designs

**Workflow (6):**
- `bobsled-style-editor` - Edit content to Bobsled's style guide
- `bug-reproduction-validator` - Reproduce and validate bug reports
- `git-god` - Advanced git operations
- `pr-comment-resolver` - Address PR comments
- `spec-flow-analyzer` - Analyze user flows
- `typescript-coder` - TypeScript development

### Commands

**Workflow:**
- `/workflows:plan` - Create implementation plans
- `/workflows:review` - Run comprehensive code reviews
- `/workflows:work` - Execute work items systematically
- `/workflows:compound` - Document solved problems

**Utility:**
- `/changelog` - Create changelogs
- `/create-agent-skill` - Create Claude Code skills
- `/generate_command` - Generate new commands
- `/heal-skill` - Fix skill issues
- `/plan_review` - Multi-agent plan review
- `/report-bug` - Report plugin bugs
- `/reproduce-bug` - Reproduce bugs
- `/resolve_parallel` - Resolve TODOs in parallel
- `/resolve_pr_parallel` - Resolve PR comments in parallel
- `/resolve_todo_parallel` - Resolve todos in parallel
- `/triage` - Triage and prioritize issues

### Skills

- `agent-native-architecture` - Build AI agents
- `bobsled-style-editor` - Style guide compliance
- `create-agent-skills` - Create Claude Code skills
- `file-todos` - File-based todo tracking
- `frontend-design` - Production-grade frontend interfaces
- `gemini-imagegen` - Image generation with Gemini API
- `git-worktree` - Manage Git worktrees
- `skill-creator` - Guide for creating skills

### MCP Servers

- `playwright` - Browser automation via `@playwright/mcp`
- `context7` - Framework documentation lookup
