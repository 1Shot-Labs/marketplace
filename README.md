# 1Shot Labs Plugin Marketplace

Official plugin marketplace for 1Shot Labs Claude Code plugins.

[![Plugins](https://img.shields.io/badge/plugins-3-blue.svg)](https://github.com/1Shot-Labs/marketplace)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Quick Start

Add this marketplace to Claude Code:

```bash
/plugin marketplace add 1Shot-Labs/marketplace
```

## Available Plugins

### Squadron Comms

Voice communication system with ElevenLabs TTS for multi-agent coordination.

**Install:**
```bash
/plugin install squadron-comms
```

**Features:**
- 🎯 Four specialized squadron agents (Red, Gold, Blue, Green)
- 🎙️ Voice broadcasting with ElevenLabs TTS
- 📝 Mission logging system
- 🔒 Concurrent-safe audio playback
- 🎨 Color-coded squadron identification

**Repository:** [1Shot-Labs/squadron-comms-plugin](https://github.com/1Shot-Labs/squadron-comms-plugin)

**Documentation:** [README](https://github.com/1Shot-Labs/squadron-comms-plugin#readme)

---

### Elite Skills Library

Premium Claude Code skills library with AI-powered skill distribution.

**Install:**
```bash
/plugin install elite-skills
```

**Features:**
- 📚 270+ professional-grade skills
- 🎯 AI-powered skill distribution
- 🔐 Subscription-based access
- 🎓 Domain expertise transformation
- 🚀 Continuous skill updates
- 💼 Professional workflow automation

**Repository:** [1Shot-Labs/elite-skills-library-plugin](https://github.com/1Shot-Labs/elite-skills-library-plugin)

**Homepage:** [skills.1shotlabs.com](https://skills.1shotlabs.com)

---

### Chief of Staff

Comprehensive personal AI assistant plugin for Claude Code - replicates all Clawdbot capabilities.

**Install:**
```bash
/plugin install chief-of-staff
```

**Features:**
- 💬 Multi-channel communication (Slack, Discord, Telegram)
- 🔄 Lobster-inspired workflow engine
- 🧠 Persistent memory with vector database
- 🌐 Browser automation via Chrome DevTools Protocol
- ⏰ Scheduling & automation (cron, webhooks, heartbeat)
- 🎨 Visual canvas system with A2UI
- 🤖 Multi-agent coordination
- 🔒 Security & sandboxing
- 📱 Device integration (camera, screen, notifications)
- 🎯 87% Clawdbot feature parity

**Repository:** [1Shot-Labs/chief-of-staff](https://github.com/1Shot-Labs/chief-of-staff)

**Documentation:** [README](https://github.com/1Shot-Labs/chief-of-staff#readme) | [Getting Started](https://github.com/1Shot-Labs/chief-of-staff/blob/master/docs/getting-started.md)

## Usage

### Adding the Marketplace

```bash
# In Claude Code
/plugin marketplace add 1Shot-Labs/marketplace
```

### Installing Plugins

```bash
# Install any plugin from the marketplace
/plugin install squadron-comms
/plugin install elite-skills
/plugin install chief-of-staff

# List installed plugins
/plugin list

# Update marketplace
/plugin marketplace update
```

### Uninstalling

```bash
# Uninstall a plugin
/plugin uninstall squadron-comms

# Remove marketplace
/plugin marketplace remove 1shot
```

## Plugin Submission

Want to add your plugin to this marketplace?

1. Create a Claude Code plugin following [best practices](https://docs.anthropic.com/claude/docs/building-plugins)
2. Open an issue at [1Shot-Labs/marketplace/issues](https://github.com/1Shot-Labs/marketplace/issues)
3. Include:
   - Plugin repository URL
   - Plugin description
   - Documentation link
   - Keywords for discoverability

## Marketplace Structure

This marketplace follows the Claude Code plugin marketplace specification:

```json
{
  "name": "marketplace",
  "plugins": [
    {
      "name": "plugin-name",
      "source": {
        "source": "github",
        "repo": "org/plugin-repo"
      },
      "description": "...",
      "version": "1.0.0"
    }
  ]
}
```

## Support

- **Marketplace Issues**: [Report here](https://github.com/1Shot-Labs/marketplace/issues)
- **Plugin Issues**: Report in the specific plugin repository
- **General Questions**: [Discussions](https://github.com/1Shot-Labs/marketplace/discussions)

## License

MIT License - see individual plugin repositories for their licenses.

---

Made with ❤️ by [1Shot Labs](https://1shotlabs.com)
