# RepairLens

**A circular repair network for the Township of Tomorrow**
University Hackathon 2026 · Track: Planet

RepairLens is a mobile-friendly web app prototype that helps township residents report a broken laptop, get preliminary guidance, connect with a local repair shop, and find a collection point when repair is not practical.

> **Prototype notice:** All shops, collection points, residents, prices and outcomes are fictional sample data. Access controls are simulated and are not production security. Guidance is preliminary and is not a diagnosis.

## The problem
Residents may not know whether to repair or dispose of a broken device. Repair information is scattered, shops receive incomplete enquiries, and township organisers have no shared view of outcomes. These are hypotheses to validate with residents, repair shops and organisers.

## What the prototype does
**Resident**
- Reports a laptop problem with brand, symptom, description, service area and sharing consent
- Answers follow-up questions, then sees curated guidance with an uncertainty notice and a suggested next step
- Safety escalation: flagged warning signs (swollen battery, burning smell, liquid spill, overheated case) stop troubleshooting and show a safety message
- Browses repair shops, reviews the information to be shared, and submits a request
- Reviews the estimate (accept, decline or ask for clarification), tracks a status timeline, and separately confirms the outcome
- Finds a collection point and records a handover if repair does not proceed

**Repair shop**
- Sees only requests assigned to the selected shop
- Starts an assessment, sends an estimate, marks "not repairable", and updates repair status

**Township admin**
- Dashboard with separate counts: total requests, under assessment, in progress, provider-reported completed, resident-confirmed, disputed, declined, not repairable, handovers reported, handovers partner-confirmed
- Manages verification labels for shop and collection listings, and records partner receipt (demo)

## Demo scenarios
**A. Repair proceeds:** report a charging problem → answer questions → view guidance → choose a shop → submit → switch to *Repair shop*, start assessment and send an estimate → switch to *Resident*, accept → shop marks repair completed → resident confirms → check *Township admin* counts.

**B. Repair does not proceed:** shop marks the device not repairable (or resident declines the estimate) → resident opens collection options and records a handover → admin records partner receipt. The dashboard counts handovers separately from repairs.

## Run it
It is one static file with no build step. Open `index.html` in a browser, or use the GitHub Pages link. Demo data is saved in your browser's local storage; use *Township admin → Reset demo data* to clear it.

## Responsible reporting
The app does not claim carbon saved, waste prevented, longer device life or completed recycling. A collection handover is not described as recycling. Those claims would need a defined measurement method.

## Limitations
- Laptops only, with a small set of curated symptoms. Guidance needs expert review before any public pilot.
- No real accounts, payments, photo upload, notifications or messaging.
- Data lives in the browser, so there is no shared backend.

## Future work
Native Android/iOS apps, more device types, photo upload, notifications, real authentication and data retention controls, verified listings, partner-confirmed collection, and evidence-based environmental estimates.

## Team: THE GOAT
-Amir Hakim bin Nasrul
-Fathul Iman bin Fairul Hasnizam
-Muhamad Raziqbin Muhamad Riduwan
