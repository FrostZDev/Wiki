# Creating a settlement

A settlement is an outpost of the colony. You establish one by placing a founding-capable building in unclaimed wilderness. There is no separate settlement marker or approval step.

## Before you start

- Be a member of the colony's **[current governing faction](../Factions/Voting.md)**.
- Empty your hands before opening the building menu.
- Gather the materials shown for **[Resourcedepot](Resource%20Depot.md)**, the current founding building.
- Find a suitable location outside the colony and existing settlements.

Your settlement will have a **60-metre radius**, centered on the founding building's placement point. Its boundary must be at least **200 metres** from every other territory boundary.

| Neighbouring territory | Minimum distance from your founding point to its centre |
| --- | --- |
| Colony | 430 metres |
| Another settlement | 320 metres |

Distances are horizontal. Hills and valleys do not change territory membership or spacing.

## Found your settlement

1. Open the building menu using your **Open Building Menu** keybind.
2. Select **Resourcedepot** in the **TECH** category. Hover over its entry to see the cost and a short diagnostic.
3. Put the required resources **on the ground within 3 metres of your character**. Resources in your inventory or containers do not count for founding. Existing depots cannot pay the founding cost.
4. Move the hologram to your intended founding point. Keep your character near the loose resources while completing the action.
5. Read the placement notifications. Move farther away if the candidate overlaps another territory or is too close. A valid founding location shows **Creates a new settlement outpost** and **Territory rules allow placement**.
6. Complete **Place Building**. A successful placement creates the depot and settlement, consumes the founding materials and displays **Settlement founded** with its assigned name.

> **Note:** **Territory rules allow placement** confirms the territory check only. You still need permission, sufficient resources and a valid building position. Slopes, collisions and building-specific requirements can prevent placement.

Previewing or canceling does not claim land. If another player founds a conflicting settlement before your action finishes, your placement is rejected without a resource charge.

## Build inside your settlement

Stock your resource depot before placing more buildings. **Construction inside an established territory uses only a depot within that same territory.** Loose materials on the ground and depots outside the settlement cannot supply or supplement the cost.

In the current catalogue, settlements permit:

- Resource depots.
- The guard tower.
- Plain plank variants: `1×1`, `1×2`, `2×1`, `2×2`, `3×1` and `3×2`.

Angled and pipe plank variants remain colony-only. Most other buildings also remain colony-only. A building being allowed inside a settlement does **not** mean it can found one: the current founding entry is **Resourcedepot**.

Membership depends on the building's placement point. That point must lie inside the settlement, including its exact edge; the building's geometry may extend beyond the boundary if ordinary placement checks allow it.

## Upgrades and upkeep

- Resource-paying upgrades use a depot in the **building's territory**, regardless of where your character stands. Nearby resources and foreign depots cannot pay for them.
- Keep a depot available: without one, resource-paying construction and upgrades cannot proceed, including construction of a replacement depot.
- Settlement boundaries stay fixed. Adding buildings does not expand or move them.
- Settlements survive normal server restarts and remain claimed even after every building is removed.
- Founding grants no personal ownership or special building privilege. Authority follows the colony's current governing faction.

## Quick troubleshooting

| Message or problem | What to check |
| --- | --- |
| Invalid territory | This building is not permitted in the area at the checked origin. |
| Settlement required | Use an existing settlement; this building cannot found one. |
| Overlapping territory | Move the founding point away from the neighbouring territory. |
| Too close to existing territory | Allow at least 200 metres between territory boundaries. |
| Missing resources | For founding, check loose materials near your character. Inside a settlement, check its depot stock. |
| No permission | Confirm that you belong to the current governing faction. |
| Territory allowed, but placement unavailable | Check resources, slope, collisions and the building's placement requirements. |

Menu diagnostics use your character's position before you choose a hologram location. During placement, territory checks use the hologram's position. Placement notifications appear for six seconds and repeat only when the territory status changes.

## Related guides

- [Building basics](Basics.md)
- [Resource Depot](Resource%20Depot.md)
- [Building upgrades](Upgrades.md)
- [Governing faction and voting](../Factions/Voting.md)
