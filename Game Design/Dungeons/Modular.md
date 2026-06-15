---

aliases:

* Modular Dungeons
  tags:
* game-design
* dungeons
* modular

---

# Dungeons - Modular Structure

To maximize replayability while keeping development costs sustainable, every dungeon is divided into reusable fragments.

Rather than creating a completely new dungeon experience for every run, the game combines existing fragments into new dungeon layouts.

Each fragment contains two elements:

```text
Fragment
 ├─ Encounter Area
 └─ Boss
```

The encounter area contains enemies, environmental challenges, and combat encounters leading to the boss.

The boss serves as the final challenge of the fragment and acts as a decision point for the next stage of the run.

---

## From Handcrafted Dungeons to Modular Content

When players first discover a dungeon, they experience it as a traditional handcrafted adventure.

For example:

```text
Ancient Mine
 ├─ Fragment A
 ├─ Fragment B
 ├─ Fragment C
 └─ Fragment D
```

After completing the dungeon, its fragments become part of the Modular Dungeon System.

Future dungeon runs can then combine fragments from multiple dungeons.

Example:

```text
Random Dungeon Run
 ├─ Ancient Mine Fragment B
 ├─ Frozen Temple Fragment A
 ├─ Sunken Ruins Fragment A
 └─ Goblin Fortress Fragment D
```

This allows players to encounter familiar locations in unfamiliar combinations.

---

## Why Fragments?

The goal is not to create endless procedural content.

The goal is to reuse handcrafted content in new ways.

Every fragment is individually designed by developers and contains unique mechanics, enemies, and bosses.

The randomness comes from how these pieces are assembled together.

This approach combines the strengths of both systems:

### Traditional MMORPG Dungeons

* Strong environmental storytelling
* Memorable bosses
* Handcrafted encounters

### Procedural Systems

* High replayability
* Unexpected combinations
* Long-term content value

---

## Long-Term Scalability

The system becomes more powerful every time a new dungeon is added.

Example:

```text
5 Dungeons
×
4 Fragments Each

=
20 Available Fragments
```

Adding a single new dungeon immediately increases the number of possible dungeon combinations.

```text
6 Dungeons
×
4 Fragments Each

=
24 Available Fragments
```

Because every new fragment can interact with every existing fragment, the amount of available content grows much faster than the amount of content that must be developed.

This allows a small amount of handcrafted content to generate a very large number of possible dungeon runs.

---

## Design Goal

Players should recognize the places they visit while never knowing exactly what their next adventure will look like.

A dungeon run should feel familiar enough to master, but different enough to remain exciting.
