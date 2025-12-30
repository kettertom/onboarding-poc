# onboarding-poc — “First commit in < 60 minutes”

This repo is a small Proof of Concept that demonstrates a simple idea:

> A new developer should be able to clone a repo, run one command, and reach a “green test + first commit”
> regardless of the laptop state (“clean/dirty”) or CPU architecture (Intel / Apple Silicon).

## What this POC proves
- Minimal host requirements (no local Python / Node / JDK needed)
- Reproducible dev environment (same container = same behavior)
- Works across CPU architectures (arm64 / amd64), assuming Docker runs on the machine
- A measurable outcome: **Time to First Commit**

## Prerequisites (host)
- Docker Desktop (or Colima)
- Git

That’s it.

## Quick start
```bash
git clone <YOUR_REPO_URL>
cd onboarding-poc
bash ./onboard
