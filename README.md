# spec-kit-test

Testing out spec-driven development with [GitHub Spec Kit](https://github.com/github/spec-kit).

## What is Spec-Driven Development?

Spec-Driven Development helps you build software by starting with detailed specifications that guide implementation. Instead of "vibe coding", you define clear requirements and let AI assistants help turn those specs into working code.

## Using Spec Kit in This Repository

This repository is set up to work with GitHub Copilot and spec-kit. You can use the following commands in GitHub Copilot:

### Available Commands

- **`/speckit.specify`** - Create or update a feature specification from a natural language description
- **`/speckit.plan`** - Generate a technical implementation plan from a specification
- **`/speckit.tasks`** - Break down a plan into actionable development tasks
- **`/speckit.constitution`** - Create project principles and development guidelines
- **`/speckit.implement`** - Implement specific features or changes based on specifications
- **`/speckit.analyze`** - Analyze the codebase and provide insights
- **`/speckit.clarify`** - Get clarification on specifications or requirements
- **`/speckit.checklist`** - Create checklists for implementation tracking
- **`/speckit.taskstoissues`** - Convert tasks into GitHub issues

### Getting Started

1. Start by defining your project principles:
   ```
   /speckit.constitution Create principles focused on code quality and testing
   ```

2. Create a specification for your feature:
   ```
   /speckit.specify Add user authentication with OAuth2
   ```

3. Generate an implementation plan:
   ```
   /speckit.plan Create a plan for the authentication feature
   ```

4. Break it down into tasks:
   ```
   /speckit.tasks Generate actionable tasks for the auth implementation
   ```

### Directory Structure

```
.github/
  agents/       # Copilot agent command definitions
  prompts/      # Copilot prompt files
.specify/
  scripts/      # Helper scripts for spec-driven workflows
  templates/    # Templates for specs, plans, and tasks
  memory/       # Context and state for ongoing work
.vscode/
  settings.json # VS Code configuration
```

## Learn More

- [Spec Kit Documentation](https://github.github.io/spec-kit/)
- [Spec Kit Repository](https://github.com/github/spec-kit)
