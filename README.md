# Music Rating Scale

**Status: work in progress.** The six rungs and the Sleeper entry state are
locked. Words for bad and overrated songs are still open.

<p align="center">
  <img src="assets/scale.svg" alt="Music Rating Scale pyramid: Sleeper, Heater, Fire, Banger, Certified Banger, Certified Platinum Banger, Generational Banger" width="800">
</p>

## The ladder

Banger is the noun. Everything above it is a modifier on Banger.

| # | Full name | Short | Meaning |
|---|---|---|---|
| 0 | **Sleeper** | | Before the ladder. You just found it and don't know yet. Could be fire. |
| 1 | **Heater** | | New and clearly on its way. "This could become a banger for sure." |
| 2 | **Fire** | | Past heater. Not yet a banger. |
| 3 | **Banger** | | It hits. |
| 4 | **Certified Banger** | Certified | Has held up over time. Certified means proven. |
| 5 | **Certified Platinum Banger** | Platinum | Top of what a song earns. |
| 6 | **Generational Banger** | Generational | Eternal platinum. Never falls off. Certification is baked in. |

## How songs move

- A song you have just found is a **Sleeper**. It is a state, not a rung: the
  uncertainty before a song has earned a place.
- Songs enter the ladder as a **Heater** and move up as they prove themselves:
  Heater, Fire, Banger, then the certified tiers.
- **Platinum** is the top of what a song earns. **Generational** is a Platinum
  that will never fall off.

## Example

- "Other Side" by Macklemore: Generational Banger. Whether to call it a
  "Certified Generational Banger" is still being chewed on.

## Open questions

Candidate names are suggestions, not decisions.

1. **A song that is just not good.** Candidates: **Brick** (cold, and a missed
   shot), **Cold**, **Dud**.
2. **A song that is overrated.** Candidates: **Fool's Gold** (looks certified,
   isn't), **Counterfeit**, **Overcooked**.
3. **What "certified" means concretely.** Time held, listen count, or still hits
   on a cold listen after a long break.
4. **"Certified Generational Banger."** Emphasis, or a distinct thing?

<details>
<summary>Text versions of the ladder</summary>

```text
  ┌──────────────────────────────┐
  │     Generational Banger      │   rung 6, eternal platinum
  ├──────────────────────────────┤
  │  Certified Platinum Banger   │   rung 5, top of what a song earns
  ├──────────────────────────────┤
  │       Certified Banger       │   rung 4, has held up
  ├──────────────────────────────┤
  │            Banger            │   rung 3, it hits
  ├──────────────────────────────┤
  │             Fire             │   rung 2, past heater
  ├──────────────────────────────┤
  │            Heater            │   rung 1, on its way
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┘
  ╎           Sleeper            ╎   before the ladder, don't know yet
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┘
```

```mermaid
flowchart LR
    S[Sleeper] -.-> H[Heater] --> F[Fire] --> B[Banger] --> CB[Certified Banger] --> CP[Certified Platinum Banger] --> GB[Generational Banger]

    style S  fill:#0d1219,stroke:#33445a,stroke-dasharray:6 4,color:#6f8398
    style H  fill:#141f31,stroke:#141f31,color:#a9bcc6
    style F  fill:#172c42,stroke:#172c42,color:#b4c7cc
    style B  fill:#193b4c,stroke:#193b4c,color:#bfd2d2
    style CB fill:#1a4a4f,stroke:#1a4a4f,color:#c9dcd8
    style CP fill:#1c5a4d,stroke:#1c5a4d,color:#d3e6df
    style GB fill:#1f6b4d,stroke:#3fa37a,color:#e8f5ee
```

</details>
