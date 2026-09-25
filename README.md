# homebrew-lirts

Homebrew tap for [lirts](https://github.com/EvilUnicornLabs/lirts), a btop-style terminal
dashboard for ports, processes, Docker containers and the services behind them.

```bash
brew tap evilunicornlabs/lirts
brew install lirts
```

The formula installs lirts with the `mcp` extra, so `lirts mcp` (the MCP server for coding
agents) works out of the box. It is regenerated from
[packaging/homebrew/lirts.rb](https://github.com/EvilUnicornLabs/lirts/blob/master/packaging/homebrew/lirts.rb)
on every lirts release.

Licensed under the Apache License 2.0, like lirts.
