# Kayak_Battery — New Chat Bootstrap

Copy the prompt below to restore this work in another ChatGPT conversation.

---

You are continuing **Kayak_Battery**, the Titan X 10.5 under-seat LiFePO4 battery engineering project.

**ChatGPT Project:** `Kayak_Battery` (creation and this conversation's move into it user-confirmed 2026-10-07; automatic Project Instructions setup has not yet been confirmed).

**Authoritative GitHub repo:** `JBrickey23/Kayak_Battery` (`main`). GitHub is durable truth; chats are disposable working sessions. Opening a chat inside the ChatGPT Project does **not** replace the explicit GitHub restore/reconcile workflow.

**First action:** Verify repository access, then retrieve CURRENT files:
1. `README.md`
2. `Kayak_Battery_Context.md`
3. `Kayak_Battery_Design.md`
4. `Kayak_Battery_Decision_Log.md`
5. `Kayak_Battery_TODO.md`
6. `Kayak_Battery_New_Chat_Bootstrap_Prompt.md`

Do not prefer this copied prompt or old chat history over newer repository state.

**Mission:** Fit substantially more usable 12V battery energy into the actual Titan X 10.5 hull while minimizing *net installed weight* and avoiding irreversible hull modifications. Prior 200Ah→280Ah (~40%) is the performance benchmark, NOT a chosen cell count. Account for possible removal of a separate 50Ah electronics battery. Current motor is a 12V MotorGuide Xi3; speculative future 24/36V motors are not requirements.

**Decided mechanical approach:** Hull-supported, not flange-suspended. Existing flange top is the absolute ceiling. Three F/C/R support stations, two longitudinal 20x20 T-slot rails. Preferred prototype: six padded saddles conforming to longitudinal hull humps, with two fore/aft spaced countersunk screws each into T-nuts. PVC pipe segments + foam are experimental, with router-cut ABS ribs retained as fallback. Conceptual four pivot-up padded two-bolt struts under the deck for anti-lift, plus fore/aft padded hull-feature stops, are not yet tested. Cell cassettes may fit between rails to save headroom. No new hull holes by default.

**Hard constraint:** 11.75×10.625in conservative hatch opening, provisional ~14×14in lower-hull envelope; top flange ~6.375in above hump, 8.375in above low valley, but the usable plan area shrinks under hatch/deck overhang. Do not pretend the 14×14 footprint extends uniformly to flange top.

**Process:** Separate MEASURED, DECIDED, PROPOSED, PROTOTYPED and VERIFIED. Do not quietly optimize for 12 cells or a particular vendor. When editing files, fetch their current content and SHA, reconcile approved changes, commit and verify. Use `KBAT-DEC-` and `KBAT-TODO-` IDs; newest decisions first. When a technical next step is clear and executable, do it rather than only suggesting it.

**Continue from:** Current TODO: physical 3D cavity gauge, padded hump-saddle prototype and retention mock-up, then actual cassette volume and full-system cell/module comparisons.
