# Kayak_Battery — Context

## Identity and provenance
- Repository/project: `JBrickey23/Kayak_Battery`, `main`.
- Native Watercraft Titan X 10.5, under-seat hull battery compartment.
- Initial durable reconciliation: 2026-10-07. Based on extensive user/assistant engineering discussion; no installed/proven final system.
- GitHub is durable authority; chats are working sessions. Restore before changing decisions.
- **ChatGPT Project setup (user-confirmed, 2026-10-07):** a ChatGPT Project named `Kayak_Battery` has been created, and this battery-design conversation has been moved into it. GitHub cannot independently verify ChatGPT Project membership. Whether Project Instructions have been configured to automatically restore GitHub on every new chat is **not yet confirmed**.

## The actual goal
**Substantially more usable energy with minimum net installed weight, optimized around the real available hull space.** Prior comparison: 12.8V/200Ah (2.56kWh) to 12.8V/280Ah (3.58kWh) = **40% more**. This is an initial performance *benchmark*, NOT a selected cell count, cell model or strict capacity ceiling/floor. The old ~2–3lb incremental estimate compared **bare cell mass** against **finished commercial batteries**, so it does **not** validate finished-pack mass. Consolidation could eliminate a separate ~50Ah electronics battery, its hardware and wiring; weigh the current system before asserting net savings.

## Electrical scope
- Current 12V MotorGuide Xi3 trolling motor (earlier approx. 52A max; confirm exact model and actual draw).
- Current 12V fish finder/electronics, presently powered separately by ~50Ah battery; possible single-pack design must account for electrical noise, required isolation and simultaneous loads.
- A 24/36V Garmin upgrade remains hypothetical; an acquired non-working 24V Newport is **not** a design requirement. Do not optimize mechanical support for an unpurchased motor.
- LiFePO4 favored. No chosen pack topology (4S1P/2P/3P/4P), cell count, cells, modules, compression hardware, BMS or IP rating.
- Compare high-Ah 4S1P cells, more smaller cells, compressed OEM modules, and finished retail batteries by **installed** weight, actual energy, access, safety, reliability, and price.
- Require appropriate discharge capability, fuse/disconnect, marine cabling, busbar insulation, low-temperature charge controls, BMS and practical wet-environment strategy.

## Mechanical design — agreed framework
- **Hull-supported, not hanging from flange.** Nothing may protrude above the existing upper flange height.
- Two fore/aft longitudinal **20x20 aluminum T-slot extrusions**, with **three support stations** forward, center, rear even if overbuilt.
- Original alternative: transverse, vertically set 1/2–3/4in ABS ribs with bottom contour routed to hull humps, 2–4mm replaceable pads, drainage gaps, 20x20 recesses so rail top is flush with ABS top. L extrusion brackets, through-bolts and T-nuts.
- **Current preferred prototype:** six individual hull-hump saddles, two per F/C/R station, beneath the two longitudinal extrusions. PVC curved pipe segments (~2–3in diameter initial trial) lined with closed-cell foam (~1/2in initial trial), or contoured ABS saddles if PVC shape is unsuitable. Preserve open longitudinal valleys/drainage. Attach each saddle provisionally with **two fore/aft-spaced countersunk M5 bolts into extrusion T-nuts**; count, screw geometry and material require prototype verification.
- Capture/lift-off concept: four padded, fixed-length, pivot-up/second-bolt locking upright struts bracing to suitable underside-of-deck geometry, **without lifting/jacking the deck**. Retention contact structure and loads unvalidated; broad foot optional, not automatic.
- Fore/aft restraint concept: padded contacts/stops against suitable existing hull features, avoiding fragile scupper tubes. Port/starboard restraint may come from saddle/hump engagement. Tape/adhesive is allowed for locating pads/parts, **not primary restraint**.
- Explore a **recessed battery cassette between the rails** so the 20mm rails overlap the cells' vertical packaging, instead of unnecessarily adding a 20mm height penalty. Cell compression self-contained independently of hull support.
- Installation must work through smaller hatch; modular components/in-hull assembly may be necessary. Do not confuse a provisional floor footprint with uniform volume.

## Engineering process guardrails
- Identify status explicitly: MEASURED, APPROVED DIRECTION, PROTOTYPE IDEA, VERIFIED, INSTALLED.
- In particular, hypothetical 12-cell LF100LA/300Ah and 8-cell LF160/320Ah arrangements are *not* new goals.
- Preserve user's fixed decisions and challenge only with concrete fit, safety, or structural evidence.
- When next measurement/prototype step is evident, design it rather than repeatedly suggesting more discussion.

## Immediate continuation
Map 3D hull clearance and access route; mock up six hump saddles, two 2020 rails, four capture struts; then measure recessed cassette envelope and compare viable pack architectures with **net installed weight**.
