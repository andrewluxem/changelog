# changelog

A changelog turns raw delivery notes into a factual account of what changed for the people affected. This skill produces a Changelog Entry Set or an Internal Release Email while keeping planned, partial, and released work distinct.

It produces:

- **Changelog Entry Set** (A. Entries): built from raw work notes, release status, audience, and available dates.
- **Internal Release Email** (B. Release email): built from release facts, user impact, support material, and internal audience.

It executes the [Changelog playbook](https://www.andrewluxem.com/playbooks/changelog). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/changelog.git
cp -r changelog/skills/changelog ~/.claude/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/changelog
/plugin install changelog@changelog
```

For clients that install from an archive, keep using the versioned [changelog v1.0.0 ZIP](https://www.andrewluxem.com/downloads/changelog-v1.0.0.zip).

## Invoke it

```text
Write the changelog entry from this work
Turn these work notes into release notes for account administrators. Released
Write the changelog from this dump. Some of this may still be in testing and I
```

Naming the skill is always valid: `use the changelog skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/changelog/
  SKILL.md
  meta.yaml
  LICENSE.md
  assets/
  references/
README.md
LICENSE
```

The complete canonical package is copied under `skills/changelog/`, including every asset, reference, example, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, and `.claude-plugin/plugin.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/changelog/LICENSE.md](skills/changelog/LICENSE.md).
