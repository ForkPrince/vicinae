# vicinae Windows ARM64 builds

Upstream vicinae only ships Windows x86_64 builds. This repo builds them for
ARM64 on GitHub's `windows-11-arm` runners.

## What it does

Once a week it checks vicinae for releases it has not built yet, builds each one
for ARM64, and attaches the results here as a GitHub release.

## What you get

- `vicinae-arm64-setup.exe` — installer
- `vicinae-arm64-portable.zip` — portable build
- `SHA256SUMS` — checksums

These builds are unsigned, so Windows will warn you and Vicinae will not
self-update from them.