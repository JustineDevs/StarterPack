<div align="center">
  <img src="./public/img/banner.png" alt="The Blueprint for High-Velocity Technical Execution" width="800" />
</div>

# Project Planning Starter Pack
Complete monorepo structure for planning, executing, and delivering technical projects. This toolkit provides comprehensive templates, guides, AI assistance, and ready-to-use configurations to accelerate project development from planning to deployment.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Documentation](#documentation)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Project Planning Starter Pack is a complete system for planning, executing, and delivering technical projects. It combines strategic planning templates, technical execution guides, AI-powered assistance, and production-ready configurations into a single, organized monorepo.

This toolkit helps you:
- Plan projects using structured templates covering all aspects from vision to deployment
- Execute technical work with clear workflows and best practices
- Deliver production-ready code with automated quality checks and CI/CD pipelines
- Leverage AI assistance for key technical decisions and implementations

## Features

- **12 Planning Sections** - Complete strategic and operational planning templates covering executive summary, objectives, scope, architecture, execution workflow, phases, resources, risks, strategy, monitoring, ROI, governance, and continuous improvement
- **Technical Execution Guide** - Comprehensive 200+ page documentation covering all aspects of implementation
- **Claude Skills Integration** - Auto-activated AI assistance for key technical decisions and implementations
- **Skills.sh Publishing** - Consolidated skill available for installation via skills.sh CLI
- **Claude Plugin Package** - Distributable .claude-plugin for Claude Code with bundled skills
- **Reference Guides** - Quick access to architecture documentation, technical summaries, and complete file indexes
- **Configuration Files** - Ready-to-use CI/CD pipelines, linting rules, testing frameworks, and build configurations
- **Ready-to-Build Structure** - Organized directories for application code with TypeScript, Next.js, and modern tooling
- **Skills Reference Library** - Example skill implementations and templates for creating custom AI skills

## Quick Start

### Prerequisites

- Node.js 18.0 or higher
- npm 8.0 or higher
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd BlueprintKit
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Verify installation**
   Open http://localhost:3000 in your browser. You should see the project dashboard.

For detailed setup instructions, see [BEGINNER-GUIDE.md](./BEGINNER-GUIDE.md).

### Install as Skills.sh Skill

Install BlueprintKit as a skill for your AI agent:

```bash
npx skills add JustineDevs/BlueprintKit
```

This installs the consolidated skill from `.claude/skills/blueprintkit/SKILL.md` which combines all 14 planning sections and all 9 project planning capabilities into a single skill.

### Install as Claude Plugin

The `.claude-plugin/` directory provides a plugin package for Claude Code:

1. Clone this repository or copy the `.claude-plugin/` directory to your project
2. Claude Code automatically detects and loads the plugin
3. Access all nine bundled skills through the unified plugin interface

See [.claude-plugin/README.md](./.claude-plugin/README.md) for detailed plugin documentation.

## Project Structure

```
BlueprintKit/
├── Entry Points
│   ├── START-HERE.md          # Entry point and navigation guide
│   ├── BEGINNER-GUIDE.md      # Step-by-step beginner walkthrough
│   ├── QUICK-START.md         # 5-minute overview
│   └── FINAL-CHECKLIST.md     # Pre-launch verification
```

See [COMPLETE-MONOREPO-STRUCTURE.md](./docs/reference/COMPLETE-MONOREPO-STRUCTURE.md) for complete file structure details.

## Documentation

### Entry Points

- **[START-HERE.md](./START-HERE.md)** - Your entry point to the system. Start here to understand navigation and structure.
- **[BEGINNER-GUIDE.md](./BEGINNER-GUIDE.md)** - Complete step-by-step walkthrough for new users. Recommended for first-time users.
- **[QUICK-START.md](./QUICK-START.md)** - 5-minute overview of the complete system.

### Planning Framework

- **[Planning Sections](./.claude/skills/blueprintkit/planning/)** - 14 comprehensive planning templates:
  - [Master Index](./.claude/skills/blueprintkit/planning/0-Master-Index.md) - Overview of all planning sections
  - [Executive Summary](./.claude/skills/blueprintkit/planning/1-Executive-Summary.md) - Vision and problem statement
  - [Objectives & Success Metrics](./.claude/skills/blueprintkit/planning/2-Objectives-Success-Metrics.md) - Quantified goals
  - [Scope Definition](./.claude/skills/blueprintkit/planning/3-Scope-Definition.md) - Project boundaries
  - [System Architecture & Design](./.claude/skills/blueprintkit/planning/4-System-Architecture-Design.md) - Technical blueprint
  - [Technical Execution Workflow](./.claude/skills/blueprintkit/planning/5-Technical-Execution-Workflow.md) - Implementation approach
  - Additional sections covering phases, resources, risks, strategy, monitoring, ROI, governance, and continuous improvement

### Technical Reference

- **[TECHNICAL-SUMMARY.md](./docs/reference/TECHNICAL-SUMMARY.md)** - Quick reference for technical decisions and architecture
- **[SYSTEM-ARCHITECTURE.md](./docs/reference/SYSTEM-ARCHITECTURE.md)** - Complete system architecture overview
- **[COMPLETE-MONOREPO-STRUCTURE.md](./docs/reference/COMPLETE-MONOREPO-STRUCTURE.md)** - Detailed file structure documentation
- **[API-REFERENCE.md](./docs/reference/API-REFERENCE.md)** - API documentation and endpoints

### Additional Resources

- **[Claude Skills Documentation](./docs/mdx/claude-skills.mdx)** - Guide to using Claude Skills for AI assistance
- **[Planning Framework Guide](./docs/mdx/planning-framework.mdx)** - Detailed planning methodology
- **[Technical Guide](./docs/mdx/technical-guide.mdx)** - Implementation and development guide
- **[SKILL.md](./.claude/skills/blueprintkit/SKILL.md)** - Consolidated skill definition for skills.sh
- **[Claude Plugin Documentation](./.claude-plugin/README.md)** - Plugin installation and usage guide

### Publishing

To publish this skill or validate the publishing setup:

```bash
./scripts/publish-skill.sh
```

This script validates the skill structure and .claude-plugin configuration and provides publishing instructions for both skills.sh and Claude Code plugin distribution.

## Getting Started

### First Time Users

1. **Read BEGINNER-GUIDE.md** - Complete beginner-friendly walkthrough with step-by-step instructions
2. **Read START-HERE.md** - Understand the system structure and navigation
3. **Review QUICK-START.md** - Get a 5-minute overview of the complete system
4. **Explore Planning Sections** - Start with Section 1 (Executive Summary) in the `.claude/skills/blueprintkit/planning/` directory
5. **Test Claude Skills** - Ask Claude about your tech stack or project decisions

### Ready to Plan

Start with the Planning Sections in order:
1. [Executive Summary](./.claude/skills/blueprintkit/planning/1-Executive-Summary.md) - Define your vision and problem statement
2. [Objectives & Success Metrics](./.claude/skills/blueprintkit/planning/2-Objectives-Success-Metrics.md) - Set quantified goals
3. [Scope Definition](./.claude/skills/blueprintkit/planning/3-Scope-Definition.md) - Define project boundaries
4. [System Architecture & Design](./.claude/skills/blueprintkit/planning/4-System-Architecture-Design.md) - Create technical blueprint

### Ready to Build

1. Review [Technical Execution Workflow](./.claude/skills/blueprintkit/planning/5-Technical-Execution-Workflow.md)
2. Use Claude Skills for automated assistance with technical decisions
3. Follow configuration files for setup (see `package.json` scripts)
4. Start coding in the `src/` directory

## Contributing

We welcome contributions to improve the Project Planning Starter Pack. To contribute:

1. **Fork** the repository
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes** and commit with descriptive messages
4. **Push to your branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request** with a clear description of your changes

For detailed contribution guidelines, see [CONTRIBUTING.md](./CONTRIBUTING.md) if available.

### Code of Conduct

Please maintain a professional and respectful environment when contributing. Follow clean code principles and project standards defined in `.cursor/rules/`.

## License

This project is licensed under the [MIT License](./LICENSE) - see the LICENSE file for details.

Contributions to this project are accepted under the same license.
