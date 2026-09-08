# 02 — Equipment pad

Photos: `pad-overview-full.jpg`, `pad-overview-heatpump-side.jpg`,
`heater-bypass-valves-and-ichlor.jpg`, `filter-multiport-and-pump.jpg`.

## Layout (standing at the pad, house wall behind the equipment)

```
 house wall ─────────────────────────────────────────────────────────
   [subpanel]      [iChlor power ctr]                    [gray box / GFCI]
 ┌────────────┐     ┌────────┐
 │ UltraTemp  │     │  Sand  │  (multiport valve on top, gauge, blue waste hose)
 │ 110 heat   │     │ filter │
 │ pump       │     └────┬───┘        ┌──────┐
 └──┬──────┬──┘          │            │ Pump │ SuperFlo VS
    │      │             │            └──┬───┘
   in     out            │               │ suction from pool
    │      │        ┌────┴────┐          │  (gray 3‑way: skimmer / main drain)
    │      └──[V3]──┤  bypass ├──[V2]────┤
    │               │  [V1]   │          │
    └───────────────┴─────────┘          │
                         │
                    [iChlor cell] ── return to pool
```

## Flow path (always in this order)

1. Pool → gray 3‑way valve (skimmer vs. main drain) → **pump** suction
2. Pump discharge → spring **check valve** → **multiport valve** → down through the
   **sand** → back up the standpipe → out the multiport RETURN port
3. Filtered water → bypass tee → **heat pump** (when valves are set to heat) → back
   to the tee
4. → **iChlor salt cell** → return line → pool

The chlorinator is last on purpose. Chlorinated water must never sit in the heat
exchanger while the pump is off.

## The three blue ball valves

Ball valve rule: **handle in line with the pipe = open, handle across the pipe =
closed.**

| Valve | Location | Function |
|---|---|---|
| V1 | Horizontal pipe between the two risers | Bypass around the heater |
| V2 | Riser from filter, below tee | Heater inlet |
| V3 | Riser to iChlor, below tee | Heater outlet |

| Mode | V1 bypass | V2 inlet | V3 outlet |
|---|---|---|---|
| Heating | Closed | Open | Open |
| Bypassed (heater off / winter) | Open | Closed | Closed |
| Partial (throttle flow to heater) | Partly open | Open | Open |

**Never** have all three closed with the pump running. Open the two heater valves
before closing the bypass, and open the bypass before closing the heater valves.

On 2026‑09‑08 the valves appeared to be in the **bypassed** position and the heat pump
display was dark. Verify by hand before starting the heater.

## Other pad components

- **Spring check valve** on the pump discharge near the wall: stops water draining
  back through the pump when it stops and keeps the pump primed.
- **Blue lay‑flat hose** on the multiport WASTE port: backwash discharge. Route it
  away from the house foundation and the gravel bed; salt water kills grass.
- **Gray 3‑way valve** on suction: diverts between skimmer and main drain. Normal
  setting is mostly skimmer with some drain. Never fully close both.
- **Small gray box on the wall** behind the filter: almost certainly the iChlor power
  center (transformer). It should be fed from the pump circuit so the cell can only
  run when the pump runs.
- **White box on a stand** at the far right: likely the GFCI receptacle for the
  "Pool Lts + Rec" circuit. Confirm and test the button monthly.
