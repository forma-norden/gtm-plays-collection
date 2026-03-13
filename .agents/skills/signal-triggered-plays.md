# signal-triggered-plays

Use this skill to design offensive plays that trigger based on external
market events or account-level changes.

## 1. The "Champion Move" Play
**Trigger:** A known past customer or power user takes a new job at an ICP-fit account.
**Timing:** Days 15-45 in the new role. (Don't pitch on day 1).
**Channel:** LinkedIn DM -> Email.
**Angle:** "Congrats on the new gig. Assuming you're evaluating the stack right now. Want me to send over how we handle [Pain] for companies your size so you have it as a baseline?"

## 2. The "Following the Money" Play
**Trigger:** Account announces Series A/B/C funding.
**Timing:** Weeks 2-6 post-announcement.
**Channel:** Multi-channel sequence (Email + Call + LI).
**Angle:** Do NOT say "congrats on the funding." Say: "Usually when companies raise a Series B, the board immediately demands faster yield on [Function]. If you're tasked with shrinking that timeline, we do X..."

## 3. The "Pain-Point Hiring" Play
**Trigger:** Account posts a highly specific job description (e.g., "Director of RevOps").
**Timing:** Immediately.
**Channel:** Email to the hiring manager.
**Angle:** "Saw you're bringing on a Director of RevOps specifically to handle [Pain point mentioned in JD]. While you interview, thought this framework on solving [Pain] might be useful for the interim team."

## 4. The "Tech Stack Shift" Play
**Trigger:** Account installs or drops a specific competitive or complementary technology.
**Timing:** Days 30-90 (Install) or Immediate (Drop).
**Channel:** Email.
**Angle:** "Saw you guys recently moved to [Complementary Tech]. Typically, teams do that to achieve X, but struggle with Y. We plug directly into [Tech] to solve Y..."

## Play Architecture Requirements
For every signal play, you must define:
- **The specific data trigger** (e.g. Apollo funding alert, Clay job change check).
- **The decay window** (when the signal becomes too old to use).
- **The fallback** (how to sequence them if they don't reply to the signal-based hook).

## Output Contract
When designing a signal-triggered play, provide:
- The trigger definition and data source.
- The timing strike zone.
- A 3-step sequence structure (Hook, Follow-up, Breakup).
- The specific angle/premise for the copy.
