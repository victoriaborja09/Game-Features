# Creator Launchpad

**A prototype marketplace for game playtesting, built as an independent Roblox feature concept.**

Creator Launchpad explores how developers could find relevant players to test early-stage games, commission structured feedback, and fund predefined rewards in Robux without coordinating separate recruitment and payment channels.

The product is a standalone interactive demonstration. It is **not affiliated with Roblox** and does not connect to real Roblox accounts, transfer Robux, or verify gameplay.

## Product opportunity

Roblox already supports beta testing, playtest access, and gameplay analytics. What is missing from these workflows is a centralized marketplace where developers can find eligible testers, specify tasks, hold a fixed reward budget, collect comparable evidence, and enforce payments according to published completion criteria.

This concept addresses a potential bottleneck in game development: finding outside players whose feedback helps creators identify confusing instructions, balancing problems, and other issues before release. The marketplace also introduces players to games they might not otherwise discover, without treating compensated testing as organic demand.

## Explore the prototype

**Developer view**
1. Explore sample games and existing playtests.
2. Create a campaign with specific objectives, tester eligibility, and a fixed Robux reward.
3. See the full reward commitment and illustrative platform fee before publishing.
4. Review structured submissions and their observations.

**Player view**
1. Browse available testing opportunities and their requirements.
2. Accept an assignment and complete the structured feedback form.
3. Record attempted tasks, observed outcomes, device details, and recommendations.
4. See simulated earned Robux after meeting the published completion standard.

Switch between **Developer** and **Player** in the app to follow the same campaign from both perspectives.

## Incentives and safeguards

- Developers fund the displayed reward amount before participants begin.
- Payout eligibility follows predetermined submission requirements, not whether a developer likes the review.
- Participants are paid for completing defined testing work, not for minutes spent or positive comments.
- Paid sessions would be excluded from organic discovery metrics in a production implementation.
- Any actual game verification, fraud controls, disputes, moderation, age checks, and Robux transactions would require Roblox platform infrastructure. The prototype demonstrates form-based validations only.

## What I would measure

| Product question | Proposed measurement |
| --- | --- |
| Does the marketplace reduce recruitment friction? | Time to recruit eligible testers and time to first reproducible finding |
| Does testing change development outcomes? | Development iteration time and publication rate, compared with existing testing methods |
| Does this help player discovery? | Voluntary subsequent play and seven-day return, measured separately from paid test sessions |
| Can the economic model work? | Developer adoption, reward spending, fees, and incremental Robux purchases rather than transfers alone |

These metrics are hypotheses for a pilot, not reported results.

## Implementation

The prototype uses **HTML, CSS, and vanilla JavaScript**, with browser-local demo state. It runs without a build step or backend. All games, users, Robux balances, and campaign results are illustrative.

| File | Purpose |
| --- | --- |
| `index.html` | Interactive prototype, styling, and simulated campaign logic |
| `assets/icon.svg` | Creator Launchpad logo and favicon |
| `README.md` | Product explanation and operating notes |

To preview locally, open `index.html` or serve the repository using `python3 -m http.server 8000`.

To publish, enable GitHub Pages for the `main` branch at the repository root. The expected site address is `https://victoriaborja09.github.io/Game-Features/` once deployment succeeds.

---

*Independent portfolio concept. Not endorsed by or affiliated with Roblox.*
