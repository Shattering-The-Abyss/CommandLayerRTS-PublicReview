# Next-Generation RTS Design Seed

## One-Line Thesis

The next generation of RTS should not be only a faster version of base building, unit production, and APM execution.

It should ask a deeper question:

> Under fog of war, limited attention, and irreversible timing pressure, how does a player maintain better battlefield judgment?

## Core Read

RTS is not defined by one fixed surface shape.

Bases, workers, units, resources, tech trees, control groups, and high APM are expressions of the genre, not the whole genre.

The deeper RTS loop is:

- making decisions with incomplete information
- allocating limited attention under pressure
- reading timing windows
- scouting, misleading, pressuring, retreating, and rotating
- correcting mistakes before they become fatal
- deciding when to personally intervene and when to let a planned behavior run

The goal is not to make a prettier StarCraft clone.

The goal is to explore a modern real-time command game.

## Command Layer

The player should feel less like a high-speed click machine and more like a real-time commander.

A possible structure:

- **Command layer**: fronts, objectives, priorities, commitments
- **Logistics layer**: economy, production, supply, reinforcement
- **Tactical layer**: engagements, positioning, abilities, retreats
- **Intel layer**: scouting, sensors, bait, map control, uncertainty
- **Doctrine layer**: preset unit behavior such as formation, target priority, retreat threshold, harassment rules

Skill should not disappear. It should move upward.

The best players are not only faster. They know what deserves attention now, what can be delegated to doctrine, and when the original plan must be overridden.

## Automation Boundary

Automation can help, but it must not turn the game into an autoplay simulation.

Good automation reduces low-value repetition and returns attention to real decisions.

Possible examples:

- workers execute reasonable logistics by default, but the player can override them
- squads follow player-defined doctrine
- scouting routes can run automatically, but interpretation remains the player's job
- production templates can execute, but strategic choice remains human-owned
- the player sets intent: defend, harass, rotate, regroup, retreat, redeploy

Core rule:

> The system may execute player intent, but it must not own player intent.

## Why This Is Interesting

Many RTS stress points come from repeated mechanical upkeep rather than deeper strategic judgment.

If the next generation of RTS reduces low-value repetition, the design space can shift toward:

- more meaningful scouting
- clearer battlefield reading
- heavier strategic commitments
- more real retreat, regroup, and redeployment decisions
- stronger campaign-level command feeling
- gameplay closer to maintaining an accurate battlefield picture

This does not reduce depth.

It moves depth away from hand-speed chores and back toward real-time command judgment.

## What To Avoid

- Do not copy StarCraft with new art.
- Do not make a MOBA with base-building attached.
- Do not let hero units erase the army system.
- Do not automate away player agency.
- Do not hide shallow decisions behind complex tables.
- Do not let visual spectacle destroy battlefield readability.
- Do not build ranked ladder pressure before the game has a soul.

## Current Stage

This is a design seed.

It is not a development commitment.

It is not a final design.

It is not a business pitch.

The question for review is:

> If the heart of RTS is maintaining true judgment under fog of war, what should the next-generation RTS look like?

