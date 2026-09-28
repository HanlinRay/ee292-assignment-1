# EE292 — Assignment 1

Two independent parts.

## `ass1_part1/` — Development environment verification

Demonstrates a working development environment: **Git, GitHub, Docker, Make,
and a coding agent.** The Python program is trivial for verify chain

```bash
cd ass1_part1
make verify
```

`make verify` runs pytest locally, builds the Docker image, and runs pytest
again inside the container. It exits nonzero if any stage fails.

## `ass1_part2/` — Real AI mistake report

It documents an actual mistake a coding agent made while configuring Git/GitHub.
