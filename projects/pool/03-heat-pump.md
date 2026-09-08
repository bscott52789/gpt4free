# 03 — Heat pump: Pentair UltraTemp 110

Photos: `heatpump-nameplate.jpg`, `heatpump-control-panel.jpg`,
`heatpump-conduit-and-subpanel.jpg`.

## Nameplate

| Field | Value |
|---|---|
| Model / P/N | UltraTemp 110, P/N 460962 (black) |
| Serial | 1003237020, built 2026‑04‑18, plant 1307 |
| Output | 110,000 BTU/hr at 80 °F air / 80% RH / 80 °F water |
| COP | 6.1 at 80/80/80, 5.8 at 80 °F air 63% RH, 4.0 at 50 °F air |
| Supply | 208/230 V, 1 phase, 60 Hz |
| MCA | 42.0 A |
| MOCP | 50 A minimum, 70 A maximum |
| Compressor | 31.1 RLA, 182 LRA |
| Fan | 3.9 RLA |
| Refrigerant | R‑410A, 4.5 lb charge |
| Design pressures | Low 250 psig, high 450 psig |
| Listing | ETL, AHRI 1160 certified, IPX4, outdoor only |
| Support | Pentair 800‑831‑7133 |

## How it works

An air conditioner run backward. The fan pulls outside air across the evaporator
coil; R‑410A boils and absorbs heat from the air; the compressor raises its pressure
and temperature; a titanium heat exchanger (condenser) gives the heat to the pool
water; an expansion valve drops the pressure and the cycle repeats. It **moves** heat
rather than making it, which is why one kilowatt in yields up to six kilowatts of
heat out.

Consequences:
- Output and efficiency fall with air temperature. Below ~50 °F air it barely helps
  and will cycle on its own low‑temperature cutoff.
- It needs water flow (its own flow/pressure switch) and it needs the fan clear.
  Keep 2 ft clear around it and never stack anything on top.
- It runs long and slow. A gas heater adds 1–2 °F per hour; this adds roughly
  0.5–0.7 °F per hour on a 20,000 gal pool at full output.

## Control panel

`ON/OFF`, `POOL/SPA`, `MENU SELECT`, red up / blue down arrows, `ON` and `SERVICE`
LEDs. Startup: press ON/OFF, select POOL, set target temperature with the arrows,
allow 5 minutes. A dark display means it is switched off or has no power; check the
60 A breaker in spaces 1/3.

## Cost and performance math

Heat needed: 1 BTU raises 1 lb of water 1 °F. A 20,000 gal pool is ~166,800 lb, so
each degree costs ~167,000 BTU, i.e. ~1.5 hours of full output before losses.

| Air temp | COP | Electrical draw | Cost/hr at $0.14/kWh |
|---|---|---|---|
| 80 °F | 6.1 | ~5.3 kW | ~$0.75 |
| 65 °F | ~5.0 | ~6.4 kW | ~$0.90 |
| 50 °F | 4.0 | ~7.4 kW | ~$1.05 |

## Operating strategy for Chesterfield

- **Run it in the afternoon** when air is warmest, not overnight.
- **A solar cover is worth more than the heater** on 60 °F nights. Most heat leaves
  as evaporation off the surface.
- Set the thermostat and leave it; chasing the setpoint with on/off costs more.
- Keep the heater bypassed and off when the water is already where you want it.
- Shoulder season target: 82–84 °F water through September, decide in October
  whether to keep paying.

## Do not

- Do not run without water flow.
- Do not let the salt cell sit upstream of it (it isn't; see `02-equipment-pad.md`).
- Do not attempt refrigerant work. R‑410A requires EPA 608 certification.
