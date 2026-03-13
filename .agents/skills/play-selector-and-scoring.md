# play-selector-and-scoring

Use this skill to determine which GTM play a team should execute based
on their capacity, data constraints, and expected yield.

## The Play Selection Matrix

Not all plays are created equal. Prioritize based on the **Expected Yield Rating (EYR)**.

### Tier 1: High Yield / Low Volume
*Execute immediately when the trigger conditions are met.*
- **Examples:** Champion Job Change, Inbound Demo Request, High-Intent Pricing Page Visit.
- **Routing:** Immediate manual intervention by an AE or Senior SDR.
- **Capacity Impact:** High per account, low overall volume.

### Tier 2: Medium Yield / Medium Volume
*Execute continuously as data becomes available.*
- **Examples:** Webinar Attendee Follow-up, Recent Funding + ICP Fit, Competitor Tech Stack Renewal.
- **Routing:** Signal-triggered automated sequence with personalized manual step 1.
- **Capacity Impact:** Medium. Requires AI personalization or SDR research blocks.

### Tier 3: Low Yield / High Volume
*Execute when Tier 1 & 2 queues are empty.*
- **Examples:** Cold Persona-based Outbound, Industry Vertical Expansion.
- **Routing:** Fully automated sequencing.
- **Capacity Impact:** Low. Pure machine execution.

## Play Validation Checklist

Before recommending or launching a play, confirm:
1. **Data Availability:** Can we reliably identify the trigger? (e.g., Don't launch a "Tech Install" play if you don't have BuiltWith/HG Insights).
2. **Content Readiness:** Do we have the case studies or specific value props required to make the play work?
3. **Execution Capacity:** Do the SDRs have enough blocks in their day to execute the manual steps?

## Output Contract
When asked to select or validate a play, provide:
- The top 2 recommended plays from the catalog based on the user's constraints.
- Total Addressable Market (TAM) estimate required to make the play viable.
- Tools required to execute it (Data Source + Execution Platform).
- Expected conversion benchmark (from `resources/references/play-catalog.md`).
