# BlueprintKit Monorepo

Complete project planning and execution framework organized as a monorepo with separate skill and starter pack components.

## Repository Structure

This monorepo contains two main components:

### 📦 `skill/` - Skills Repository Component

The skill-only files for publishing to [skills.sh](https://skills.sh). This directory contains:

- `.claude/skills/blueprintkit/` - Complete skill definition with all 14 planning sections and 9 execution skills
- `SKILL.md` - Root skill definition for skills.sh compatibility
- `LICENSE` - MIT License

**Publishing**: This component is also available as a separate repository at [JustineDevs/skills-collection](https://github.com/JustineDevs/skills-collection) for clean skills.sh installation.

**Installation**:
```bash
npx skills add JustineDevs/skills-collection
```

### 🚀 `starter-pack/` - Complete Starter Pack

The full starter pack with frontend, documentation, and all project files:

- `src/` - Next.js frontend application
- `docs/` - Complete documentation
- `scripts/` - Automation scripts
- `prisma/` - Database schema
- `public/` - Static assets
- `context/` - LLM context files
- `package.json` - Dependencies and scripts
- Configuration files (TypeScript, ESLint, Prettier, etc.)
- Planning documentation and guides

**Usage**: Navigate to `starter-pack/` directory to use the complete starter pack.

## Quick Start

### For Skills Installation

Install the skill for your AI agent:

```bash
npx skills add JustineDevs/skills-collection
```

### For Starter Pack Usage

1. Navigate to the starter pack:
   ```bash
   cd starter-pack
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Read the documentation:
   - [START-HERE.md](./starter-pack/START-HERE.md) - Entry point
   - [BEGINNER-GUIDE.md](./starter-pack/BEGINNER-GUIDE.md) - Step-by-step guide
   - [QUICK-START.md](./starter-pack/QUICK-START.md) - 5-minute overview

## What's Included

### Skill Component (`skill/`)

- **14 Planning Sections** - Complete strategic and operational planning templates
- **9 Claude Skills** - Specialized execution capabilities:
  - Technology Selection
  - Architecture Documentation
  - Code Quality Enforcement
  - CI/CD Automation
  - Agile Execution
  - Risk Management
  - Automation Orchestration
  - Web Application Testing
  - Web Artifact Building

### Starter Pack Component (`starter-pack/`)

- **Frontend Application** - Next.js documentation site
- **Complete Documentation** - Technical guides, API references, architecture docs
- **Configuration Files** - CI/CD pipelines, linting, testing, build configs
- **Automation Scripts** - Setup, validation, and deployment scripts
- **Skills Reference Library** - Example skill implementations

## Repository Organization

```
BlueprintKit/
├── skill/                    # Skill-only files (for skills.sh)
│   ├── .claude/
│   │   └── skills/
│   │       └── blueprintkit/
│   ├── SKILL.md
│   └── LICENSE
│
├── starter-pack/             # Complete starter pack
│   ├── src/                  # Next.js frontend
│   ├── docs/                 # Documentation
│   ├── scripts/              # Automation scripts
│   ├── prisma/               # Database schema
│   ├── public/               # Static assets
│   ├── context/              # LLM context
│   ├── package.json
│   └── [config files]
│
├── README.md                 # This file
└── LICENSE                   # MIT License
```

## Related Repositories

- **Skills Repository**: [JustineDevs/skills-collection](https://github.com/JustineDevs/skills-collection) - Clean skill-only repository for skills.sh
- **Main Repository**: [JustineDevs/BlueprintKit](https://github.com/JustineDevs/BlueprintKit) - This monorepo

## Installation Options

### Option 1: Install Skill Only (Recommended for AI Agents)

```bash
npx skills add JustineDevs/skills-collection
```

This installs only the skill files, perfect for AI agent usage.

### Option 2: Use Complete Starter Pack

```bash
git clone https://github.com/JustineDevs/BlueprintKit.git
cd BlueprintKit/starter-pack
npm install
npm run dev
```

This gives you the complete starter pack with frontend and all documentation.

## Documentation

### Skill Documentation

- [Skill Definition](./skill/.claude/skills/blueprintkit/SKILL.md) - Complete skill documentation
- [Planning Sections](./skill/.claude/skills/blueprintkit/planning/) - All 14 planning templates

### Starter Pack Documentation

- [START-HERE.md](./starter-pack/START-HERE.md) - Entry point and navigation
- [BEGINNER-GUIDE.md](./starter-pack/BEGINNER-GUIDE.md) - Step-by-step walkthrough
- [QUICK-START.md](./starter-pack/QUICK-START.md) - 5-minute overview
- [Technical Summary](./starter-pack/docs/reference/TECHNICAL-SUMMARY.md) - Tech stack reference
- [System Architecture](./starter-pack/docs/reference/SYSTEM-ARCHITECTURE.md) - Architecture overview

## Contributing

We welcome contributions! To contribute:

1. **Fork** the repository
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes** and commit with descriptive messages
4. **Push to your branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request** with a clear description of your changes

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

Contributions to this project are accepted under the same license.

## About

Starter Pack Template that synthesizes end-to-end execution playbooks, frameworks, and blueprints from practitioners who've generated measurable ROI.

[plan.jstn.site](https://plan.jstn.site/)
