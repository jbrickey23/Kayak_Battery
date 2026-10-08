# Kayak_Battery — Geometry, Design and Candidate Packaging

## Physical hull measurements

| Feature | Dimension | Evidence |
|---|---|---|
| Clear flange opening | 11.75in wide x 10.75in; use **11.75 x 10.625in** conservatively | User measurement |
| Top of hull hump -> bottom of flange opening | **4.0in** | User measurement |
| Top of hull hump -> top of existing flange | **6.375in = 161.9mm** | User measurement: HARD CEILING |
| Low valley floor -> bottom flange opening | **6.25in** | User measurement |
| Low valley floor -> top flange | **8.375in** | User measurement |
| Approximate clear span between nearby scupper obstructions | ~16in left/right and fore/aft | Provisional |
| Below-opening working envelope | ~**14 x 14in** | Provisional; NOT uniformly rectangular or tall |

**Very important:** The usable horizontal footprint changes with elevation. The hatch opening and underside of upper deck/flange overhang may intrude well below the top flange. A battery can fit at hull floor elevation yet hit the flange/deck higher up. A one-piece 14x14in cradle does not simply pass through the 11.75x10.625in opening. No elevated service deck above the flange.

Hull has **fore/aft running longitudinal humps** with lower valleys between; transverse saddle/rib layouts span right/left (port/starboard). Water must move fore/aft through valleys.

## Original design option: contoured ABS ribs
- Three vertically upright **right/left transverse** ABS webs (~1/2–3/4in thick), at F/C/R.
- Template/rout lower edge to hull hump contour with **selected load-bearing contact patches**; preserve 3–5mm drainage notches/relief where appropriate and avoid forcing hull into shape.
- Replaceable compliant contact pads ~2–4mm to accommodate hull tolerance/flex.
- Two fore/aft **20x20 T-slot rails** set in ~20x20mm notches so ABS top and rail tops are flush, not rail stacked atop ribs.
- Typical 2020 L-brackets into extrusion T-nuts, through-bolted to ABS. Rib option remains fallback, not abandoned.

## Preferred experimental design: discrete conforming saddles
- Replace full-width ABS ribs with short **PVC pipe-section or custom ABS saddles** sitting ON specific fore/aft hull humps.
- Initial 2–3in diameter PVC segments shaped to fit local hump radius; verify real geometry (not necessarily circular).
- Closed-cell compressible foam liner ~1/2in **starting concept**, chosen/tested for load-bearing compressive stiffness and long-term compression set. Replaceable liner.
- Initial frame has 2 longitudinal 2020 rails, each bearing through 3 saddles at F/C/R stations: **six saddle contact pieces**. Final saddle count/rail spacing requires actual hump placement.
- Two countersunk M5 flat head screws **spaced fore/aft** in each saddle into T-nuts of extrusion underside. The counterbores are covered by foam. Screws locate saddle and carry incidental inverted/shear/handling loads; gravity travels cassette→rails→saddle→pad→hull. Validate PVC thickness at countersinks and fastener retention.
- Between hull humps all water passages remain open naturally: no deliberate drainage cuts in full-width ribs.
- Height: saddles under the rails add rigid/pad rise; mitigate by supporting cassette **down between rails** where structurally/physically possible. Height of cassette is measured from actual hull surface, not automatically rail top. Must avoid interference with underside flange.

## Positive retention: geometry-captured frame (design idea, not tested)
- Downwards gravity: saddles/hull contact patches distribute pack load.
- Port/starboard: mating curved saddle/hump geometry, with slip/flex tolerance; test against dislocation.
- Upwards/inversion: initially FOUR fixed-length hinged upright struts, port/starboard on forward and rear support positions; pivot bolt for deployment and secondary locked-position bolt. Replaceable upper deck contact pads, optionally enlarged only if contact area requires it. No jack-like preload, no moving threaded height adjustment unless proven necessary.
- Forward/aft: geometry/padded stops engaging suitable existing reinforced hull features rather than relying solely on friction/tape. A longer cassette/base may provide location; avoid loading scupper tubes or thin hull skin.
- No holes in kayak unless demonstrably necessary. Adhesive/tape only positioning, NOT structural retention.
- Verify upper deck can accept contact loads, vibration, slamming, capsize, hull thermal/flex variation, installation and removal.

## Battery packaging research only, NOT selection
| Candidate | Approx. bare cell dimensions | Nominal example | Constraint |
|---|---|---|---|
| EVE LF280K | verify manufacturer revision; ~205mm upright height | 4S1P ~280Ah/3.58kWh | Upright too tall above hump; alternative orientation must be approved |
| EVE MB31 | ~173.7×71.7×207.2mm | 4S1P ~314Ah/4.02kWh; ~49lb bare cells | Upright too tall; orientation permission unknown |
| EVE LF160 | ~173.9×53.9×153.5mm | 4S2P ~320Ah/4.10kWh; ~53lb bare | Tight vertical room and pack footprint |
| EVE LF100LA | ~160×50.1×118.5mm incl. terminals | 4S2P ~200Ah, 4S3P ~300Ah | More manageable height; 12-cell example was research detour, not goal |
| EVE LF100LA factory 1P4S module | purported ~243.3×164.1×128mm | 100Ah; 2 modules ~200Ah | Verify dimensional drawing, compression, BMS, IP rating, cost and shipping |

Previous early benchmarks: two completed 100Ah 12V batteries collectively ~44lb vs four LF280K bare cells estimated ~46lb. **Apples-to-oranges.** Add compression plates, BMS, electronics, insulation, protection, wiring, structure and battery removal to any weight comparison.

## Environmental and electrical cautions
- IP67 rating for sealed retail/OEM *entire pack* is different from bare prismatic cells or an open compressed cell module. BMS and busbars need terminal covers, proper ingress control, ventilation/pressure considerations, cable glands, moisture management.
- Loosening moisture criteria from full IP68 is worth exploring only with informed risk assessment for kayak flooding.
- Keep pack electrical compression structure separate from deck capture/hull saddle components.
- Need verified continuous current to serve Xi3 and electronics, BMS with charge temperature protections, correct fuse and disconnect, corrosion-resistant wiring.

## Next physical fit experiments
1. Make indexed hull-height gauges at 100, 125 and 150mm above hump datum; trace actual usable cross-section and the hatch insertion path.
2. Record hump location, width/crest profile and curvature along fore/aft axis; see whether 2 rails can sit over suitable structural hump patches.
3. Trial one saddle and foam liner, verify actual **compressed vertical rise** and even support when weighted.
4. Check lower rail plane and potential cassette floor elevation relative to hull humps, and room for edge mount flanges.
5. Template strut/stop contact locations; assess structural path before building pack.
6. Only after above, compare whole-pack orientations, cell/module count, full mechanical compression and installed weight.
