# Claude Plugins

This repository serves as a Claude plugin marketplace for plugins and tools by n33kos.

For more information about Claude Code plugin marketplaces, see the [official documentation](https://code.claude.com/docs/en/plugin-marketplaces).

## Installation

To add this marketplace to your Claude Code installation:

```bash
/plugin marketplace add n33kos/claude-plugins
```

## Available Plugins

### clicky-keys

Audio feedback for Claude Code - hear keyboard typing sounds while Claude is working.

**Commands**:

- `/setup` - Configure clicky-keys audio settings (volume, speed, triggers)
- `/test` - Test the clicky-keys sound for a few seconds
- `/mute` - Toggle clicky-keys sounds on/off

**Source**: External repository ([n33kos/claude-clicky-keys](https://github.com/n33kos/claude-clicky-keys))

### voice-multiplexer

Remote voice interaction with multiple Claude Code sessions. Talk to your running Claude sessions from anywhere — switch between them and control them by voice.

**Commands**:

- `/auth-code` - Generate an authentication code to link a new device to your voice-multiplexer instance
- `standby` - Put the current Claude session in standby mode, connecting it to the multiplexer for remote voice interaction
- `/service-status` - Check the status of the voice-multiplexer services
- `/start-services` - Start the voice-multiplexer services (if not already running)
- `/stop-services` - Stop the voice-multiplexer services

**Source**: External repository ([n33kos/claude-voice-multiplexer](https://github.com/n33kos/claude-voice-multiplexer))
