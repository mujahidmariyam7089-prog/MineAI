# MineGov AI Design Direction

## Three stylistic approaches considered

### Theme Name: Civic Control Room
Very Brief Intro: A disciplined government-technology command center that pairs editorial hierarchy with operational clarity. Light surfaces, deep navy structure, and calibrated risk colors create a trustworthy environment for review and accountability.
Probability: 0.07

### Theme Name: Field Ledger
Very Brief Intro: A tactile regulatory workspace inspired by inspection ledgers, field notebooks, and stamped evidence trails. Warm paper neutrals, mineral accents, and tabbed panels make compliance feel grounded and human.
Probability: 0.03

### Theme Name: Signal Grid
Very Brief Intro: A restrained dark operations room with restrained teal telemetry accents and clear signal bands. The mood is vigilant and technical, prioritizing live anomaly awareness over decorative spectacle.
Probability: 0.08

## Chosen approach: Civic Control Room

### Design Movement
Contemporary government technology with an editorial information-design influence: clear hierarchy, measured density, visible provenance, and a calm command-center rhythm.

### Core Principles
1. **Trust through structure:** every page should expose status, ownership, evidence, and the next responsible action.
2. **Signal before decoration:** color is reserved for operational meaning—critical, elevated, compliant, or in review.
3. **Human oversight is visible:** AI recommendations are framed as explainable inputs to officer decisions, never as autonomous authority.
4. **Operational density with breathing room:** compact data modules sit inside generous page rhythm so judges can scan and narrate the demo quickly.

### Color Philosophy
Use a light zinc background as the neutral field, deep navy for institutional structure, slate teal for intelligence and active navigation, green for verified/operational states, amber for attention, and crimson for critical hazards. Risk colors must never become decoration; they communicate urgency and are paired with text labels for accessibility. The ownable brand color is **Signal Teal #187C78**, a sober bridge between public-service blue and mining-field mineral tones.

### Layout Paradigm
A persistent left navigation rail anchors the application like a control-room console. The main workspace uses an asymmetric editorial grid: wide narrative/action panels on the left, narrow evidence and status rails on the right, with occasional full-width tables for registry and ledger views. Pages should feel like layered briefings rather than centered marketing cards.

### Signature Elements
1. A slim **governance rail** on priority cards showing the Detect → Explain → Review → Act → Verify → Audit sequence.
2. **Provenance chips** with source, timestamp, quality, and responsible role attached to important evidence.
3. **Stamped status labels** using compact uppercase typography for DEMO DATA, HUMAN REVIEW, VERIFIED, and POTENTIAL NON-COMPLIANCE.

### Interaction Philosophy
Every control explains its consequence. Risk cards open into a review surface; approving a recommendation creates an assigned action and writes to the audit ledger; navigation preserves state without reloads; exports provide a clear demo confirmation. Hover and focus states reveal context without hiding primary content.

### Animation
Use fast, calm transitions under 220ms. Sidebar collapse should slide content by a small distance; tabs should underline with a short teal sweep; modals should enter at 96% scale with opacity; toasts should rise gently from the lower right. Avoid looping motion except a subtle live-status pulse. Respect reduced-motion preferences.

### Typography System
Use **IBM Plex Sans** for the UI and data labels, with **Space Grotesk** for high-level page titles and key numbers. Headlines are compact, slightly tracked, and sentence case. Metadata is 11–12px uppercase with increased letter spacing. Numbers use tabular figures for KPI and audit readability.

### Brand Essence
MineGov AI is an explainable compliance command center for mining authorities and operators who need faster, more accountable safety decisions without surrendering human oversight. Personality: **vigilant, accountable, pragmatic**.

### Brand Voice
Headlines are direct and operational. CTAs describe the next accountable step rather than generic conversion language. Microcopy states provenance and limitations plainly.

Example lines:
- “Review the evidence. Assign the accountable officer.”
- “AI flagged the pattern; human governance closes the loop.”

### Wordmark & Logo
Use a compact symbol combining a mine-shaft frame with a split signal node: two vertical navy pillars, a teal center beam, and a small amber verification notch. The mark should work independently in the sidebar and favicon; the “MineGov AI” wordmark is set beside it in a custom-weighted institutional lockup, never as a default logo image.

### Signature Brand Color
**Signal Teal — #187C78**. It is the visual shorthand for explainability, connected evidence, and the controlled movement from detection to verified action.

## Style Decisions
- Keep the interface light, serious, and non-cyberpunk.
- Pair every high-severity color with a text label and icon.
- Treat all data as simulated or representative and never imply official Government of India operation.
- Use the same governance rail and provenance language across dashboard, actions, inspections, reports, and audit views.
- Prefer functional motion and state feedback over decorative animation.


### Accepted style review amendments
- Keep every primary route inside the persistent left navigation rail with MineGov AI identity, environment context, role context, and operational navigation.
- Make the governance sequence visible in priority and evidence surfaces, not only in the dedicated pathway panel.
- Ensure every high-severity card includes at least one provenance chip showing source, time, quality, or responsible role.
- Use the mine-shaft / split signal-node symbol as the first-glance identity anchor and reserve Signal Teal #187C78 for explainability, active navigation, and accountable progress.
- Push the interface toward briefing sheets and stamped records through compact metadata, evidence chips, and restrained surface depth rather than broad rounded SaaS card language.
