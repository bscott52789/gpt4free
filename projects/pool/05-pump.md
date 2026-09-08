# 05 — Pump: Pentair SuperFlo VS

Photos: `pump-nameplate.jpg`, `pump-superflo-vs-keypad.jpg`, `pump-basket-lid.jpg`.

## Nameplate

| Field | Value |
|---|---|
| Model | 358204, motor warranty number 358204W35125MX010041‑9U |
| Volts | 115 / 208–230 V, 1 phase, 50/60 Hz (wired 230 V here, L1/L2) |
| Max amps | 13.6 A at 115 V, 8.2 A at 208 V, 7.1 A at 230 V |
| Speed | 450–3450 rpm |
| THP / HHP | 2.2 total HP, 1.09 hydraulic HP |
| WEF | 8.6 (DOE weighted energy factor, thousand gal per kWh) |
| SF | 1.0 |
| Enclosure | TEFC, Type 3, IPX6, insulation class F, 50 °C ambient |

## Keypad

| Control | Function |
|---|---|
| `Display` | Cycles the readout between Speed, Time, Duration, Watts |
| `1` `2` `3` | Three programmable speeds |
| `Quick Clean` | Temporary high‑speed run for vacuuming or skimming |
| `+` `−` | Adjust the selected speed (or time/duration in program mode) |
| `Start/Stop` | Run or stop |
| `Ext. Control Only` LED | Lit when an automation system is in charge (off here) |
| Lightning LED | Power present |

On 2026‑09‑08: Speed 1 active at 3200 rpm, running, no external control.
Keypad walk‑through video showed:

| Readout | Value |
|---|---|
| Watts at 3200 rpm | **1186 W** (1174–1189 W as speed was nudged 3190–3220) |
| Time | 10:53, matches real time, so schedules will fire when expected |
| Duration (Speed 1) | 2:07 displayed. If that is 2 h 07 min per day, the pump is badly under‑running; a salt pool needs 8–12 h. Verify and reprogram. |

Programming a speed on the SuperFlo VS: press and hold the speed button until the
display flashes, use `+`/`−` to set rpm, press the speed button again to advance to
start time, again for duration, then `Start/Stop` to save. The lid decal has the full
sequence.

## Energy math

Pump power follows the cube of speed. Half the rpm ≈ one eighth the watts. Scaled from the measured 1186 W at 3200 rpm:

| Speed | Approx. watts | Cost per 10 hrs at $0.14/kWh |
|---|---|---|
| 3200 rpm | 1,186 measured | ~$1.66 |
| 2600 rpm | ~640 | ~$0.90 |
| 2200 rpm | ~390 | ~$0.55 |
| 1800 rpm | ~210 | ~$0.30 |

Press `Display` until Watts lights to read the real number.

## Choosing speeds

Minimum flow needs:
- iChlor: ~20 GPM to keep the FLOW light on.
- UltraTemp 110: ~30 GPM minimum, more is better for heat transfer.
- Skimmer: enough surface draw to pull leaves in, usually 1800+ rpm.

Suggested program (verify by watching the FLOW light and the heater):

| Speed | RPM | Use |
|---|---|---|
| 1 | ~2200 | Everyday filtering, 10–12 hrs |
| 2 | ~2800 | When the heat pump is running |
| 3 | 3200–3450 | Quick Clean, vacuuming, priming, backwash |

Method: with the pump on Speed 1, press `−` until the iChlor FLOW light drops out,
then add ~300 rpm of margin. Longer run time at lower speed filters better and costs
less than short runs at high speed.

## Strainer basket

Weekly, more often in pine‑needle season:
1. `Start/Stop` to stop.
2. Relieve pressure at the filter air relief.
3. Unscrew the clear lid, lift the basket, dump and rinse.
4. Wipe the lid o‑ring, lube with **silicone** grease only, hand‑tighten.
5. Fill the pot with a hose, restart, bleed air at the filter.

A growing air pocket under the lid while running means a suction‑side air leak: lid
o‑ring, suction union, or a low skimmer water level.
