# AI Org - Claude Code Starter Kits

Build faster with Claude Code. We create tools and templates that help founders ship products in days, not months.

## Our Open Source Tools

### [@aiorg/cli](https://github.com/aiorgdev/cli)
Official CLI for downloading and managing aiorg kits.

```bash
# Get started with free kit
npx @aiorg/cli init claude-starter ~/my-project

# For paid kits
npx @aiorg/cli login
npx @aiorg/cli init marketing-os ~/my-project
```

**Features:**
- Download starter kits instantly
- Smart upgrades that preserve your customizations
- License management for paid kits

---

### [claude-plugins](https://github.com/aiorgdev/claude-plugins)
Free Claude Code plugins for your projects.

**Available plugins:**

| Plugin | Description | Install |
|--------|-------------|---------|
| **aiorg-todo** | Team task board in your repo | `/plugin install aiorg-todo` |
| **aiorg-prd** | Interactive PRD designer | `/plugin install aiorg-prd` |
| **aiorg-changelog** | Auto-generate release notes | `/plugin install aiorg-changelog` |

```bash
# Register marketplace (one time)
/plugin marketplace add aiorgdev/claude-plugins

# Install a plugin
/plugin install aiorg-todo --scope project
```

---

## Getting Started

1. **Try free plugins** - Add team tasks, PRD design, or changelog to any project
2. **Get the free starter kit** - `npx @aiorg/cli init claude-starter ~/my-project`
3. **Explore paid kits** - Visit [aiorg.dev](https://aiorg.dev) for SaaS templates, Marketing OS, and more

## Links

- [aiorg.dev](https://aiorg.dev) - Our website
- [Documentation](https://aiorg.dev/docs) - Full documentation
