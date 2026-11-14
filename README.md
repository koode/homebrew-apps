# Koode Homebrew tap

Apps made by [Koode](https://koode.nl/?utm_source=github.com&utm_medium=referral&utm_campaign=homebrew-apps&utm_content=readme).

```bash
brew trust --cask koode/apps/stew && brew install --cask koode/apps/stew
```

Homebrew loads casks from a tap other than its own only after you trust them, hence `brew trust` first.

| Cask | What it is |
|---|---|
| `stew` | A floating macOS panel that lets Claude Code ask you for permission, ask a question or tell you something, without taking keyboard focus. [stewcli.com](https://stewcli.com) |

Casks here are updated by each app's release script. The apps update themselves too, so `brew upgrade` and the app's own updater never fight over the version.
