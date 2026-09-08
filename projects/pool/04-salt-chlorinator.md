# 04 — Salt chlorinator: Pentair iChlor

Photos: `ichlor-display-closeup.jpg`, `ichlor-set-21pct.jpg`,
`ichlor-salt-3350ppm.jpg`, `heater-bypass-valves-and-ichlor.jpg`.

## What it does

Electrolysis: dissolved salt (NaCl) passes between titanium plates in the clear cell,
and a low‑voltage DC current splits chloride into chlorine gas that dissolves instantly
as hypochlorous acid, the same sanitizer as liquid chlorine. The chlorine does its job
and turns back into salt, so salt is only lost to splash‑out, backwash, and overflow.

## The display and buttons

| Control | Function |
|---|---|
| Display | Alternates between `SET xx%` (output) and `xxxx PPM` (salt) |
| `<` `>` arrows | Raise or lower output in steps |
| `INFO` | Cycles through salt ppm, output %, water temperature, cell life, and any alerts |
| `BOOST` | 100% output for 24 hours of pump run time, then returns to the setpoint |
| `FLOW` LED green | Water is moving through the cell; the cell will not run without it |
| `CHLORINATING` LED | Cell is actively producing |
| `WARNING` LED | Press INFO to read the fault |

The black knurled fitting under the cell with a cable is the cell's cord and sensor
connection, not a solenoid. Flow sensing is built into the cell body.

## Salt range

| Salt reading | Meaning |
|---|---|
| < 2800 ppm | Low‑salt warning, output reduced or stopped |
| 3350 ppm | Reading on 2026‑09‑08, fine |
| 3600 ppm | Ideal per the label |
| > 4500 ppm | High salt, can shorten cell life |

Adding salt: roughly 50 lb of pool salt raises 20,000 gal by 300 ppm. Pour it into the
shallow end with the pump running, brush it around, and wait 24 hours before trusting
the display. Use plain pool salt (sodium chloride, 99%+), never rock salt with
anti‑caking agents or water‑softener salt with additives.

## Output percentage

Output is a duty cycle. 21% means the cell produces for 21% of the time the pump runs.
The right number is whatever holds free chlorine in range, so it changes with:
- pump run hours (fewer hours → higher %),
- water temperature (warmer → more demand),
- bather load and rain,
- stabilizer (CYA) level (low CYA burns off chlorine in sunlight).

Adjust in 5–10% steps and wait 2–3 days between changes. Use BOOST for events, not as
a substitute for a correct setpoint.

## Temperature cutoff

The iChlor stops producing below about 52 °F water. In late fall you must supplement
with liquid chlorine or accept that the water is too cold for algae anyway.

## Cell cleaning

Inspect the plates through the clear housing monthly. White crusty scale between
plates means calcium buildup. Clean with a 4:1 water‑to‑muriatic‑acid soak for no more
than 15 minutes, rinse, reinstall. Frequent scaling means pH or calcium is running
high; fix the chemistry rather than cleaning more often. Expected cell life is roughly
10,000 hours.
