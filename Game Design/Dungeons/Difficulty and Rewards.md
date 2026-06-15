---
aliases:
  - Difficulty and Reward Rating
tags:
  - game-design
  - dungeons
  - progression
  - rewards
---


## Difficulty Progression

At the end of each fragment, players choose the difficulty of the next one.

Examples:

```text
+1
+2
+5
+10
+15
```

Higher difficulties introduce more mechanics, more dangerous encounters, and greater rewards.

Difficulty can always be lowered during a run.

Because of this, every run remains finishable.

Groups are never trapped by a previous decision.

---

## Reward Rating

Rewards are calculated only after the dungeon is completed.

The final reward tier is determined using a weighted difficulty rating.

The system intentionally values consistency over isolated difficulty spikes.

For each run:

* The lowest chosen difficulty receives a weight of ×4.
* The highest chosen difficulty receives a weight of ×1.
* All other difficulties receive a weight of ×2.

Example:

```text
Difficulties

+15
+10
+10
+5
```

```text
(5×4 + 10×2 + 10×2 + 15×1) / 9

= 8.33
```

Final Reward Rating:

```text
8.33
```

This system discourages "gaming the system" by running most of the dungeon at low difficulty before increasing it at the end.

Stable challenge is always more valuable than occasional peaks.

```text
10 / 10 / 10 / 10
```

is preferable to

```text
5 / 15 / 5 / 15
```

even though both contain difficult encounters.
