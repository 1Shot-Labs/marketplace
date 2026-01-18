# 1 Shot Labs Plugin Marketplace

Official plugin marketplace for 1 Shot Labs Claude Code plugins.

[![Plugins](https://img.shields.io/badge/plugins-1-blue.svg)](https://github.com/1Shot-Labs/marketplace)
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

## Usage

### Adding the Marketplace

```bash
# In Claude Code
/plugin marketplace add 1Shot-Labs/marketplace
```

### Installing Plugins

```bash
# Install squadron-comms
/plugin install squadron-comms

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
/plugin marketplace remove marketplace
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

Made with ❤️ by [1 Shot Labs](https://1shotlabs.com)
