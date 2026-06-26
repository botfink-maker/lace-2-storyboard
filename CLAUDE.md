# LACE 2.0 — Project Coordinator Brief

## STOP. READ THIS FIRST.
Before taking any action, read this document in full. Do not generate, upload, or modify anything until you have mapped the request against the brief below and confirmed the plan with Dan.

---

## Roles
- **Dan Logan** — Creative Director (Botfink Creative)
- **Claude** — Senior Producer

---

## Tool Assignments

| Asset Type | Tool | Notes |
|---|---|---|
| Live-action footage stills | **Higgsfield image gen** | Generate still first. Dan reviews. Then Seedance. |
| Live-action footage animation | **Higgsfield Seedance 2.0** | ONLY after still is approved. start_image, 16:9, 5s, drama |
| Style frame animations (title cards) | **HeyGen** | Motion graphics — not Seedance |
| HyperFrames overlays | **HyperFrames** | Text/graphic overlays, renders as ProRes 4444 |
| Archive / client footage | Dan supplies directly | Already in NLE timeline |
| Storyboard reference | `LACE_2.0_Storyboard_v3.html` | Aligned to Script v03 — this is the live reference |
| GitHub Pages (stakeholder share) | `botfink-maker/lace-2-storyboard` | Push share file + assets after every edit |

---

## ⚠️ GENERATION WORKFLOW — DO NOT SKIP

1. Generate **still image** in Higgsfield
2. Show Dan — wait for **explicit approval**
3. Only then fire **Seedance** to animate
4. Never fire Seedance speculatively

**If we return to storyboarding at any point — no Seedance on any new visual until Dan has signed off the still. No exceptions. Credits are real money.**

---

## Scene Map v3 — Asset Status (aligned to Script v03)

| Scene | Label | Style Frame | AI-gen Clips | Archive/Client | Seedance Video | HyperFrames |
|---|---|---|---|---|---|---|
| S01 | Opening | ✅ | — | — | — | ✅ s01_opening.html |
| S02 | Acknowledgement | ✅ | Clip 01 ✅ · Clip 02 ❌ TBC · Clip 03 ❌ TBC | — | — | — |
| S03 | Market Pressure | ✅ | Clip 05 ✅ · Cargo Ship ✅ · Markets Clip ✅ | — | ✅ job e52f331e | — |
| S04 | AI Shift | ✅ | Clip 06 ✅ · Clip 08 ✅ · Clip 09 ✅ · Clip 09b ✅ | — | ✅ jobs e7e38ad1, 183666cc, 62150a93, 75701c0a | — |
| S05 | Foundation | ✅ | Clip 23 ✅ | S05 Archive A ✅ · Archive B ❌ · Archive C ❌ | ✅ job 7f0c9d17 | — |
| S06 | Hero Reveal | ✅ | — | Clip 19 ✅ · Scene 6c ✅ | — | — |
| S07 | Human + AI | ✅ | Still: 65b550a5 ✅ (AI data network) · Portal re-prompt ❌ | — | ⚠️ Seedance 784529ac (fired early) | — |
| S08 | Reconfiguring | ✅ | Still: 1539edb0 ✅ (railway) · Still: 72c75a10 ✅ (retail) | — | ⚠️ Seedance d30c208c, c6162b22 (fired early) | — |
| S09 | External Presence | ✅ | Clip 12a ✅ · Clip 12b ✅ · Clip 15 ✅ · Clip 15b ✅ · London: ad4d6637, 32344d43 (Dan's) | — | ✅ jobs 37de3987, 470e0cbb, c373b283 · ⚠️ 2167644b, 46f97fb8 (fired early) | — |
| S10 | People First | ✅ | — | Clip 17 ✅ | — | — |
| S11 | Career Promise | ✅ | — | S11 Archive 1 ✅ · S12a ✅ · S12b ✅ | ✅ jobs d6f957f9, f587b22a | — |
| S12 | Convergence | ✅ | — | Clip 20 ✅ · Archive 1 ❌ TBC · Archive 2 ❌ TBC | — | — |
| S13 | Final Hero | ✅ | — | — | — | — |

---

## Outstanding Items

| Priority | Item | Scene | Status |
|---|---|---|---|
| ❌ | Clip 02 + 03 | S02 | Dan to supply or generate |
| ⏳ | Review: AI data network still (65b550a5) | S07 | Awaiting Dan approval |
| ⏳ | Review: Railway still (1539edb0) | S08 | Awaiting Dan approval |
| ⏳ | Review: Retail still (72c75a10) | S08 | Awaiting Dan approval |
| ⏳ | Review: London images (ad4d6637, 32344d43) | S09 | Awaiting Dan approval |
| ❌ | S07 portal re-prompt | S07 | New still needed |
| ❌ | S05 Archive B + C | S05 | Dan to supply |
| ❌ | S12 new archive x2 | S12 | Dan to supply |
| ❌ | HyperFrames S02–S13 | All | Not started |

---

## Stop-Think-Plan Rules

1. **Map the request** — scene, asset type, tool?
2. **Check this brief** — done? Dependency?
3. **State the plan** — one line per action, credit cost. Wait for Dan.
4. **Then act.**
5. **Stills before Seedance — always.** No animation until Dan approves the still.

Never fire a generation job without confirming the plan first. Credits are real money.
