# Week 1 — Linux Fundamentals + Python Basics

## Status (updated 2026-07-13)

**Roadmap position:** Phase 1, Week 1 (Linux + Python in parallel)

### Completed
- Day 0: macOS basics
- Day 1: Homebrew, git, VS Code, first GitHub repo pushed
- Ubuntu Server ARM64 VM running in UTM
- ✅ CHECKPOINT: SSH from Mac → Ubuntu VM working (verified with systemctl output)

### In progress
- Linux Day 1–2: filesystem navigation (`~/practice/{logs,scripts,backups}` exercise)
  - Victory condition: paste `ls -R ~/practice` output + the `find` command for all `.log` files under `~`
- Python: Automate the Boring Stuff ch. 1–2
  - Victory condition: TCP port validator script (1–65535) pushed to GitHub

### Quiz results (2026-07-13)
- ✅ `ip a` to get VM IP
- ❌ SSH syntax — wrote `ssh @arif <ip>`, correct is `ssh arif@<ip>`
- ❌ Didn't know sshd / `systemctl status ssh`
- → re-quiz both next session

## Commands I had to look up
- `ssh user@host` — user BEFORE the @, like an email address
- `systemctl status ssh` — check if SSH server is running
- `mkdir -p dir/{a,b,c}` — create nested dirs in one command

## Mistakes log
- 2026-07-13: Ran Mac commands inside the SSH session → files landed in the VM.
  Lesson: always check `hostname` to know which machine the terminal is on.

## Pending habit check
- Automate one thing at work this week — NOT DONE YET, pick something small
