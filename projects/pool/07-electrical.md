# 07 — Electrical

Photos: `subpanel-breakers.jpg`, `heatpump-conduit-and-subpanel.jpg`,
`heatpump-nameplate.jpg` (bonding lug visible at right).

## Subpanel

Square D Homeline 12‑space, NEMA 3R rainproof, main‑lug‑only (the "remove twistout
only when main breaker installed" knockout is intact). Fed from the house panel;
feeder size and the house breaker feeding it are **not yet recorded**.

| Spaces | Breaker | Label | Load |
|---|---|---|---|
| 1, 3 | 60 A 2‑pole, HOM260, HACR rated | Pool Heat | UltraTemp 110 |
| 2 | 20 A 1‑pole | Pool Lts + Rec | Underwater light, GFCI receptacle |
| 4, 6 | 20 A 2‑pole GFCI, common trip, TEST button | Pool + Salt Pump | SuperFlo VS and iChlor power center |
| 5, 7–12 | empty | | |

Interrupting rating 10 kA. Liquid‑tight flexible conduit runs from the panel to the
heat pump and the pump.

## Why the numbers are right (Article 440 logic)

The heat pump is listed hermetic refrigerant equipment, so the nameplate governs, not
Table 310.16 alone:

- **Conductor** sized by MCA 42 A → #8 Cu THHN at 75 °C (50 A) is compliant.
- **Overcurrent device** sized by MOCP 50–70 A → a 60 A HACR breaker is compliant even
  though it exceeds the conductor's 50 A ampacity. That is the allowance in
  440.22/440.32 for motor‑compressor loads. Classic exam question.
- Pump: listed VS unit, nameplate max 7.1 A at 230 V. A 20 A 2‑pole is generous and
  fine. 680.21(C) requires GFCI on pool pump motor circuits ≤ 60 A and ≤ 150 V to
  ground, satisfied by the 2‑pole GFCI breaker.

## NEC 680 items to know

Virginia enforces the **2020 NEC** through the 2021 USBC (effective Jan 2024).
- 680.12: maintenance disconnect within sight of the equipment, at least 5 ft from the
  water. The subpanel itself is within sight of the heat pump and pump, which serves.
- 680.26: equipotential bonding. The bare #8 solid copper on the heat pump lug ties
  the heater, pump, ladder/handrail, and the deck's bonding grid together. Never remove
  it. Any metal added within 5 ft of the water (fence sections, a new light niche, a
  metal umbrella base sunk in concrete) must be bonded.
- 680.22(A): at least one 15 or 20 A GFCI receptacle 6–20 ft from the water. The
  white box on the stand is the likely candidate; test it monthly.
- 680.23: underwater luminaire must be GFCI protected unless it is a listed low‑voltage
  system. Confirm which one this is.
- 2020 NEC does **not** yet require GFCI on the heat pump circuit; 2023 NEC 680.5 will
  when Virginia adopts it. The plain 60 A breaker is compliant today.

## Load picture

| Load | Running amps at 240 V |
|---|---|
| Heat pump | ~30 A (31.1 RLA compressor + 3.9 fan) |
| Pump at 3200 rpm | ~5.5 A |
| Pump at 2200 rpm | ~2 A |
| iChlor | < 1 A |
| Light + receptacle | variable, small |

Everything running lands near 40 A, so a 60 A feeder is adequate and a 100 A feeder
is comfortable. Record the feeder breaker size in the house panel.

## Monthly

- Press TEST on the 20 A 2‑pole GFCI breaker; it must trip. Reset.
- Press TEST on the deck GFCI receptacle.
- Look for insects and moisture inside the NEMA 3R panel; the door gasket matters.
