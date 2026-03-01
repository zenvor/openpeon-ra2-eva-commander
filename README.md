# openpeon-ra2-eva-commander

A [peon-ping](https://github.com/PeonPing/peon-ping) voice pack featuring Red Alert 2 Allied EVA commander voice lines mixed with Tanya responses. Your AI coding assistant will now sound like a battlefield command center.

## Install

```bash
peon packs install ra2_eva_commander
peon packs use ra2_eva_commander
```

## Sound Map

| Event | Trigger | Voice Lines |
|---|---|---|
| `session.start` | Session opens | "Battle control online" / "Establishing battlefield control, stand by" |
| `task.acknowledge` | AI accepts task | "Unit ready" / "Unit ready" (Soviet) / "Building" |
| `task.complete` | Task finished | "Construction complete" / "Reinforcements have arrived" / "Unit promoted" / "Tech building captured" |
| `task.error` | Something failed | "Unit lost" / "Warning, nuclear missile launched" / "Building infiltrated" / "Our ally is under attack" / "Tech building lost" |
| `input.required` | Waiting for input | "New construction options" / "Incoming transmission" |
| `resource.limit` | Rate limit hit | "Insufficient funds" / "Low power" |
| `user.spam` | Too many messages | "Hahahaha!" / "Shake it baby!" (Tanya) |
| `session.end` | Session closes | "Battle control terminated" / "You have resigned" |

## Sources

- Allied EVA voice lines from *Command & Conquer: Red Alert 2*
- Soviet EVA voice lines from *Command & Conquer: Red Alert 2*
- Tanya voice lines from *Command & Conquer: Red Alert 2*

## License

CC-BY-NC-4.0
