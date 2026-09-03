# Music Rating Scale

**Status: work in progress.** The five rungs and the Sleeper entry state are
locked. Words for bad and overrated songs are still open.

<p align="center">
  <img src="assets/scale.svg" alt="Music Rating Scale: Sleeper, Heater, Banger, Certified Banger, Certified Platinum Banger, Generational Banger" width="880">
</p>

## The ladder

Banger is the noun. Everything above it is a modifier on Banger.

| # | Full name | Short | Meaning |
|---|---|---|---|
| 0 | **Sleeper** | | Before the ladder. You just found it and don't know yet. Could be fire. |
| 1 | **Heater** | | New and clearly on its way. "This could become a banger for sure." |
| 2 | **Banger** | | It hits. |
| 3 | **Certified Banger** | Certified | Has held up over time. Certified means proven. |
| 4 | **Certified Platinum Banger** | Platinum | Top of what a song earns. |
| 5 | **Generational Banger** | Generational | Eternal platinum. Never falls off. Certification is baked in. |

## How songs move

- A song you have just found is a **Sleeper**. It is a state, not a rung: the
  uncertainty before a song has earned a place.
- Songs enter the ladder as a **Heater** and move up as they prove themselves.
  A Heater can end up Certified or Platinum.
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
  │     Generational Banger      │   rung 5, eternal platinum
  ├──────────────────────────────┤
  │  Certified Platinum Banger   │   rung 4, top of what a song earns
  ├──────────────────────────────┤
  │       Certified Banger       │   rung 3, has held up
  ├──────────────────────────────┤
  │            Banger            │   rung 2, it hits
  ├──────────────────────────────┤
  │            Heater            │   rung 1, on its way
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┘
  ╎           Sleeper            ╎   before the ladder, don't know yet
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┘
```

```mermaid
flowchart LR
    S[Sleeper] -.-> H[Heater] --> B[Banger] --> CB[Certified Banger] --> CP[Certified Platinum Banger] --> GB[Generational Banger]

    style S  fill:#1f2430,stroke:#6b7280,stroke-dasharray:6 4,color:#e5e7eb
    style H  fill:#fbbf24,stroke:#b45309,color:#000
    style B  fill:#f97316,stroke:#c2410c,color:#000
    style CB fill:#ef4444,stroke:#b91c1c,color:#fff
    style CP fill:#e5e7eb,stroke:#6b7280,color:#000
    style GB fill:#7c3aed,stroke:#fcd34d,color:#fff
```

</details>
