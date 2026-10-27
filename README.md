# Blood Products Guide
### คู่มือส่วนประกอบโลหิตและการให้เลือดสำหรับใช้ข้างเตียง

A bedside reference for blood components, transfusion safety, the MDKKU whole-blood massive transfusion protocol and
hemovigilance, by Warodom Phaenthong, M.D. It is one self-contained HTML page (`blood-products-guide.html`, opened by
`index.html`) that runs in the browser, with no installation and no data sent anywhere.

It is decision support for healthcare professionals, not a substitute for the source guidelines, your hospital's
protocols, product labels or clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Blood_Product_Guide/

## What it contains

- 16 blood products and derivatives (whole blood, PRBC, platelets, plasma, cryoprecipitate and freeze-dried cryo,
  PCC, albumin, IVIG, granulocytes, special products): volume, storage, filter, expected response and indications.
  Search, category filters, grid/table view and side-by-side comparison.
- Guide pop-ups:
  1. Donation (Thai Red Cross Blood Donation Manual, 2021): donor eligibility, deferral by disease, procedure and
     medicine, phlebotomy and donor first aid, cold-chain temperatures.
  2. Transfusion Guide: bedside checks, IV gauge and filter, compatible fluids, rates and vital-sign schedule.
  3. WB-MTP (Khon Kaen University Faculty of Medicine trauma centre): activation criteria, sample tubes,
     ROTEM-guided therapy, heat-treated freeze-dried cryoprecipitate, anticoagulant antidotes.
  4. Complications (Thai Red Cross Guidelines on Hemovigilance, 2nd ed., 2023): 7-step reaction protocol,
     recipient and donor reactions, TRALI / TACO / TAD comparison, severity and imputability, incidents and report forms.
  5. Calculators: PRBC dose, platelet corrected count increment, ABC score.
- Colour-coded folding blocks in every guide (with Collapse all / Expand all), light and dark themes, phone layout.

Tap the version badge next to the title for the changelog. The references are a collapsible list at the bottom of the page.
On 2026-10-27 the Donation, WB-MTP and Complications content was checked against the source documents and corrected
(see the v1.1.0 changelog entry). The Transfusion Guide pop-up, the TRALI/TACO/TAD comparison and most product-card
indications rely on the international references cited in the app and were not checked against a local source.

## Editing

`blood-products-guide.html` is a single hand-written file (HTML, CSS and plain JavaScript; no build step).
To check the interface after a change, serve the folder (`node .claude/serve-static.js 8765`), open
`http://localhost:8765/blood-products-guide.html`, load `/.claude/ui-audit.js` in the page and run
`window.__uiAudit(document.body)` at desktop and phone (375 px) width.

## Licence

Copyright (c) 2026 Warodom Phaenthong, M.D. The app's code and text are licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/): share and adapt for non-commercial use,
with credit, under the same licence. The source guidelines and protocols belong to their publishers; see `NOTICE`.
