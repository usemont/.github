# Mont

Native video editing, a shared SDK, and command-line project workflows.

Mont keeps project semantics in a shared native SDK so clients can work with the same core. Our editor, SDK, and engine are not open source.

## Open skills and templates

[**Mont skills**](https://github.com/usemont/skills) contains original, Apache-2.0-licensed agent instructions and runnable project recipes. Start with the release-brief workflow: create a project, apply native commands, validate it, and export a portable offline bundle.

## CLI status

Mont CLI is a **Developer Preview** for SDK-backed project workspaces, media registration, command dispatch, explicit cloud synchronization, and offline bundles. The [signed, Apple-notarized 0.1.0-preview.1 release](https://github.com/usemont/mont-cli/releases/tag/v0.1.0-preview.1) is available for **Apple Silicon (ARM64), macOS 14 or newer**, under Nauchu AB's proprietary preview terms.

```sh
brew install usemont/tap/mont
```

No SDK checkout or Rust toolchain is needed. See the [CLI documentation](https://github.com/usemont/mont-cli#readme) for manual installation, commands, and a standalone example.

**This CLI preview does not compose timelines or render MP4s.** A project bundle is not a rendered video. No compatibility with the Flutter editor's project format is promised.

## Get involved

- [Report a CLI issue](https://github.com/usemont/mont-cli/issues)
- [Report a CLI vulnerability privately](https://github.com/usemont/mont-cli/security/advisories/new)
- [Explore and contribute original skills and recipes](https://github.com/usemont/skills/blob/main/CONTRIBUTING.md)
- [Report an issue or propose a recipe](https://github.com/usemont/skills/issues)
- [Visit Mont](https://usemont.com)

Only content explicitly licensed in the public repositories is open source. The public skills license does not grant rights to Mont's proprietary SDK, engine, or binaries.
