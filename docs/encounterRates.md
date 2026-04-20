# Encounter Rates

Each encounter type has a fixed number of slots, each with a set probability. The slot assigned to a Pokémon determines how likely it is to appear.

Slot probabilities are defined in `src/data/wild_encounters.json` and auto-generated into `src/data/wild_encounters.h`.

---

## Land / Grass (12 slots)

| Slot | Chance |
|------|--------|
| 0    | 20%    |
| 1    | 20%    |
| 2    | 10%    |
| 3    | 10%    |
| 4    | 10%    |
| 5    | 10%    |
| 6    | 5%     |
| 7    | 5%     |
| 8    | 4%     |
| 9    | 4%     |
| 10   | 1%     |
| 11   | 1%     |

---

## Surfing (5 slots)

| Slot | Chance |
|------|--------|
| 0    | 60%    |
| 1    | 30%    |
| 2    | 5%     |
| 3    | 4%     |
| 4    | 1%     |

---

## Rock Smash (5 slots)

| Slot | Chance |
|------|--------|
| 0    | 60%    |
| 1    | 30%    |
| 2    | 5%     |
| 3    | 4%     |
| 4    | 1%     |

---

## Fishing

Fishing uses 10 total slots split across three rods. Each rod draws from its own subset of slots.

### Old Rod (slots 0–1)

| Slot | Chance |
|------|--------|
| 0    | 70%    |
| 1    | 30%    |

### Good Rod (slots 2–4)

| Slot | Chance |
|------|--------|
| 2    | 60%    |
| 3    | 20%    |
| 4    | 20%    |

### Super Rod (slots 5–9)

| Slot | Chance |
|------|--------|
| 5    | 40%    |
| 6    | 40%    |
| 7    | 15%    |
| 8    | 4%     |
| 9    | 1%     |

# Gym Leader Team Counts
1: 3
2: 3
3: 4
4: 4
5: 5
6: 5
7: 6
8: 6