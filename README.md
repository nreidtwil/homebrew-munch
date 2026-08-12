# homebrew-munch

Homebrew tap for [`munch`](https://github.com/nreidtwil/munch), a terminal UI for
exploring an MCP server over streamable HTTP.

[Demo: connecting to Twilio's MCP server and running a docs search](https://github.com/nreidtwil/munch/blob/main/demo/twilio-docs-search.webm)

```
brew tap nreidtwil/munch
brew install munch
```

If Homebrew refuses the install with "Refusing to load formula ... from untrusted
tap", trust this tap first (recent Homebrew versions require this for any third-party
tap on first use):

```
brew trust nreidtwil/munch
```

Upgrade with:

```
brew upgrade munch
```

The `munch` source code is not yet open source, so this repository contains only the
Homebrew formula and compiled release binaries — no source code.
