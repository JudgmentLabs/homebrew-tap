# JudgmentLabs Homebrew Tap

Homebrew formulae for [Judgment Labs](https://judgmentlabs.ai) tools.

## Available formulae

- `judgment-cli` — the [Judgment CLI](https://github.com/JudgmentLabs/cli).

## Install

```bash
brew install JudgmentLabs/tap/judgment-cli
```

`brew upgrade judgment-cli` will pick up new releases automatically.

## How updates work

Formulae in this repo are **auto-generated**. On each release of
[`JudgmentLabs/cli`](https://github.com/JudgmentLabs/cli), its release workflow
regenerates `judgment-cli.rb` (resolving Python dependencies, hashing the source
tarball, and pinning every transitive dep to a PyPI sdist) and pushes the
result here. Don't edit the formula by hand — your changes will be overwritten
on the next release.
