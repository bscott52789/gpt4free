# 10 — Troubleshooting

Work top to bottom. Most pool problems are flow problems first, chemistry second,
equipment third.

## Pump

| Symptom | Likely cause | Fix |
|---|---|---|
| Won't start, keypad dark | Breaker 4/6 tripped or GFCI tripped | Reset once. Trips again → moisture in the motor/junction box or a failing motor. Do not keep resetting a GFCI. |
| Runs but no flow, lid full of air | Lost prime; suction air leak | Fill the pot, check lid o‑ring, check the suction union, raise pool water level, check the 3‑way valve isn't shut. |
| Air bubbles at returns | Suction air leak | Same list. Shaving cream on suction joints while running; it gets sucked in where the leak is. |
| Loud grinding or squeal | Bearings | Motor replacement or a new pump. |
| Drip behind basket housing | Shaft seal | Shaft seal kit, cheap part, moderate job. |
| Error code on display | See Pentair SuperFlo VS manual | Note the code, power cycle once at the breaker, call if it returns. |

## iChlor

| Symptom | Likely cause | Fix |
|---|---|---|
| FLOW light off, pump running | Low flow or dirty flow sensor | Raise pump speed, clean baskets, backwash, check bypass valves aren't starving the return. |
| Low salt warning but drop test is fine | Cold water or scaled plates | Water below ~60 °F reads low; clean the cell. |
| Low salt confirmed | Splash‑out, rain overflow, backwash | Add salt per `04-salt-chlorinator.md`. |
| Chlorine keeps testing low | Output too low, CYA too low, high demand, cell worn | Raise %, fix CYA to 50–80, run BOOST, inspect cell life via INFO. |
| WARNING light | Read via INFO | Common: low salt, high salt, low water temp, cell needs cleaning, cell life. |
| Cell scale | pH/CH high | Acid soak; fix chemistry. |

## Filter

| Symptom | Likely cause | Fix |
|---|---|---|
| Pressure high, weak returns | Dirty sand | Backwash. |
| Pressure never rises, water stays cloudy | Channeled or dead sand | Deep clean or replace sand. |
| Sand in the pool | Broken lateral or standpipe | Open the tank (clamp warning), replace lateral. |
| Water leaks from waste port in FILTER | Worn spider gasket in the multiport | Replace gasket or the valve. |
| Pressure spikes, gauge pinned | Closed valve downstream | Stop pump. Open the correct valve. |

## Heat pump

| Symptom | Likely cause | Fix |
|---|---|---|
| Display dark | Off, or breaker 1/3 | Press ON/OFF; check breaker. |
| Runs but water not warming | Bypass open, low flow, air too cold, undersized runtime | Check V1/V2/V3, raise pump speed, run afternoons, give it days not hours. |
| Flow error code | Water flow below minimum | Pump speed up, clean baskets/backwash, open V2/V3 fully. |
| Low or high pressure fault | Coil blocked, fan issue, refrigerant | Clear coil, check fan spins freely. Refrigerant faults need a tech. |
| Water dripping from the cabinet | Normal condensate | Warm humid air on a cold coil sweats. A puddle when off is a leak; test it for chlorine. |
| Ice on the coil | Cold, humid weather | Normal defrost cycles handle it; if it never clears, shut it down for the season. |
| SERVICE LED on | Fault stored | Read the code via MENU SELECT; log it before calling. |

## Water

| Symptom | Likely cause | Fix |
|---|---|---|
| Cloudy | Low FC, high pH, poor filtration, high CH | Test, BOOST, extend pump hours, backwash only if pressure says so. |
| Green | Algae | Brush, BOOST or liquid chlorine to shock level, run pump 24 hrs, vacuum to WASTE, hold FC high until clear overnight. |
| Yellow/mustard on shady walls | Mustard algae | Same as green but higher FC for longer; brush daily. |
| Chlorine smell, stinging eyes | Chloramines (combined chlorine) | Shock; the smell is not "too much chlorine," it is not enough. |
| Brown/black stains | Metals or organic debris | Vitamin C tablet test: if it lifts, it's iron; use a metal sequestrant. |
| White crust at waterline or on cell | Calcium scale | Lower pH/CH; use a vinyl‑safe tile and liner cleaner at the waterline. |
| Water level dropping > 1/4 in/day | Liner or fitting leak | Bucket test; dye test around skimmer, returns, light niche, and step seams. |

## Electrical

| Symptom | Likely cause | Fix |
|---|---|---|
| GFCI breaker trips on start | Pump motor moisture, damaged cord/conduit, iChlor power center | Isolate: disconnect the iChlor power center and retry, then the pump. Megger the motor if you have one. |
| Heat pump trips 60 A on start | Weak compressor, low voltage, failed capacitor | Measure voltage under start; check run capacitor; call for compressor. |
| Tingle at ladder or handrail | Bonding failure or stray voltage | Get everyone out. Kill the subpanel feeder. Check the bonding conductor continuity. Investigate before re‑energizing. |

## When to call versus DIY

DIY: baskets, backwash, o‑rings, shaft seal, sand change, cell cleaning, salt and
chemical dosing, breaker and GFCI checks, valve settings, pump programming.

Call: anything under the heat pump cabinet involving refrigerant, compressor, or
control board; any full drain of a liner pool; a persistent bonding or stray‑voltage
issue; a leak you cannot find in a day.
