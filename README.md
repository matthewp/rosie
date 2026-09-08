# rosie

A fast, cross-platform package manager for AI agent skills. Think npm, but for skills.

```bash
rosie install anthropics/skills
```

## Install

Via npm — works on every platform Node runs on:

```bash
npx rosie-skills install owner/repo
```

Via Homebrew:

```bash
brew tap rosieskills/rosie
brew install rosie
```

Other package managers (apt, AUR, FreeBSD pkg) + a build-from-source path are
on the docs site.

## Documentation

Full docs, including the CLI reference, the typed JavaScript API, lockfile
format, supported agents, and more: **<https://rosieskills.dev/>**.

A quick jump table:

- **[install](https://rosieskills.dev/#install)** — all install methods
- **[cli](https://rosieskills.dev/docs/cli/)** — commands and flags
- **[lockfile](https://rosieskills.dev/docs/lockfile/)** — `.agents/rosie.lock` format
- **[references](https://rosieskills.dev/docs/references/)** — markdown docs as agent context
- **[js api](https://rosieskills.dev/docs/js-api/)** — `import * as rosie from 'rosie-skills'`
- **[supported](https://rosieskills.dev/docs/agents/)** — detected agents
- **[skill format](https://rosieskills.dev/docs/skill-format/)** — anatomy of a skill
- **[how it works](https://rosieskills.dev/docs/how-it-works/)** — what happens on install

## License

BSD 3-Clause
