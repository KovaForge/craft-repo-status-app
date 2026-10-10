# AGENTS.md — Forked Repo Context

<!-- kovaforge-fork-context -->
## KovaForge fork context

Forked from: `storytold/craft-repo-status-app`
Fork date: 2026-10-10
Forked by: Vladislava Kova

### Git identity

Before any commit in this repo, use the per-person wrapper (`git-vladislava`, `git-mikhail`, `git-declan`, …). Do not bare `git push`.

### Commit alias

Use `git commit-kf "message"` instead of plain `git commit`. The alias enforces identity validation, a staged-file secret scan, and Co-authored-by trailers.

See: `vault/protocols/KVF-DEV-POL-001_Git_Policy.md`

### Co-authors (permanent)

Every commit must include:

```
Co-authored-by: Michael D <McoreD@users.noreply.github.com>
Co-authored-by: vladislava-kova-kf <vladislava-kova-kf@users.noreply.github.com>
```

### Clone paths (this host)

Linux canonical root is `/home/mike/Work` (relocated from `/Users/mike/Projects`).

- Upstream: `/home/mike/Work/storytold/craft-repo-status-app`
- KovaForge fork: `/home/mike/Work/KovaForge/craft-repo-status-app`
- Remotes on the fork: `origin` = `https://github.com/KovaForge/craft-repo-status-app.git`, `upstream` = `https://github.com/storytold/craft-repo-status-app.git`

### Secrets

Never commit `.env`, `*.env`, `secrets.json`, or `credentials.*`.
