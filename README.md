# arx-isv-guide — ARX OS App Porting Reference Kit

**English** | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md)

A reference kit for ISVs (independent software vendors) who build or port apps for ARX OS: runnable example apps, porting documentation, and skills for AI agents.

> This repository holds documentation only. Download the kit from [Releases](https://github.com/ardge-cookbook/arx-isv-guide/releases).

## Download

| Version | File |
|---|---|
| Latest | [Releases › Latest](https://github.com/ardge-cookbook/arx-isv-guide/releases/latest) |
| v0.6.7 | [arx-isv-guide-v0.6.7.zip](https://github.com/ardge-cookbook/arx-isv-guide/releases/download/v0.6.7/arx-isv-guide-v0.6.7.zip) |

Verify the download with the `SHA256SUMS.txt` attached to the same release:

```bash
sha256sum -c SHA256SUMS.txt
```

## What's inside

| Path | Purpose |
|---|---|
| `apps/` | Runnable minimal examples, reference apps, and third-party app porting examples |
| `docs/` | Platform capabilities, porting approaches, and template field reference |
| `.claude/skills/` | AI agent skills for building, validating, and operating ARX OS apps |

After unzipping, start with the kit's top-level `README.md`, then pick a path that matches your app (start from scratch, port from docker-compose, or port a third-party app). The kit's documentation is written in Traditional Chinese.

## Documentation

- [ARX OS Developer Guide](https://developer.ardge.com/en/guide/overview): the official, versioned guide — it takes precedence
- [ARX ISV Cookbook](https://arx-isv-cookbook.pages.dev/en/): practical examples and lessons learned

## Versions

See the [CHANGELOG](CHANGELOG.md). v0.6.4 from the Developer Guide (`arx-isv-skills-v0.6.4.zip`) contains the skills only; this repository provides the full kit starting with v0.6.7.

## Questions and feedback

Issues are not enabled for this repository. Please contact your ARDGE representative.

## License

Copyright © 2026 ARDGE. All rights reserved. See [LICENSE](LICENSE) for permitted use.
