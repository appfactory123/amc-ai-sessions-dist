# AMC AI Sessions — public distribution

Public download mirror for the **AMC AI Sessions** macOS app. The release
artifacts (`Claude-Sessions-arm64.zip`, `support.tar.gz`) and this `install.sh`
are published here automatically by the app's release workflow, so the app can
be installed with no GitHub token.

## Install (macOS, Apple Silicon)

```bash
curl -fsSL https://raw.githubusercontent.com/appfactory123/amc-ai-sessions-dist/main/install.sh | bash
```

This installs **AMC AI Sessions.app** to `/Applications`, provisions a data dir
at `~/.claude-sessions`, and installs the runtime libraries. Re-running is safe.
