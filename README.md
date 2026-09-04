# subagents

A pi skill. It spawns pi sub-agents with isolated context windows. Run one
task, or several tasks in parallel.

Use it when a job splits into independent subtasks, when a task would fill the
current context, or when you ask for parallel agents.

## Install

```bash
pi install git:github.com/yuenshingyan/subagents
```

## Scripts

- `skills/subagents/scripts/spawn.sh` — one sub-agent
- `skills/subagents/scripts/parallel.sh` — several sub-agents, up to 4 at a time
