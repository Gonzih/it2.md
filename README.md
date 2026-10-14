# it2

An agent skill for controlling iTerm2 through its bundled native `it2` CLI.

Read [SKILL.md](SKILL.md) for pane discovery, splitting, terminal input, screen and scrollback reading, and event monitoring.

## Install

Ask your skill-capable agent:

> Install the `it2` skill from https://github.com/Gonzih/it2.md using your native skill installer. The skill directory is the repository root (`.`), and its name is `it2`.

The installed entrypoint is `it2/SKILL.md` in your agent's skill directory.

## Requirements

macOS and iTerm2 with its bundled CLI, normally at `/Applications/iTerm.app/Contents/Resources/utilities/it2`. iTerm2 must permit API access from the caller.

Verified against iTerm2 3.7.3 / it2 1.0.0. Consult the installed CLI's help for other versions.

## License and source

[MIT](LICENSE). Adapted from [Travis Cline's it2 skill](https://github.com/tmc/it2/blob/main/plugins/it2/SKILL.md) for iTerm2's bundled native CLI. The original copyright notice is retained.
