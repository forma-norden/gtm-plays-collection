# play-measurement-iteration

Use this skill to establish KPIs for GTM plays, diagnose underperformance,
and determine when to iterate or retire a play entirely.

## The Play Scorecard

Every play must be measured against a predefined scorecard.

| Metric | Definition | Healthy Benchmark |
|--------|------------|-------------------|
| Play Volume | Number of accounts enrolled per week | Matches EYR expectations |
| Open Rate | Indication of deliverability/subject lines | > 40% |
| Reply Rate | Total replies / Total sent | > 5% (Cold), > 15% (Signal) |
| Positive Reply | "Yes, let's chat" / Total replies | > 15% of all replies |
| Meeting Rate | Meetings Booked / Accounts Enrolled | > 1% (Cold), > 5% (Signal) |

## The Iteration Cycle

Do not change a play until it has reached statistical significance (minimum 250-500 accounts for cold, 50-100 for high-intent signals).

### Symptom 1: High Open Rate, Low Reply Rate (< 3%)
- **Diagnosis:** The hook/premise is weak, the email is too long, or the CTA is too aggressive.
- **Iteration:** Reword the first sentence. Change the CTA from "15 minute call?" to "Worth sending over a 2-min video?"

### Symptom 2: High Reply Rate, Low Positive Rate (< 10%)
- **Diagnosis:** The targeting is slightly off, or the pain isn't acute enough. You are getting "We use a competitor" or "Not a priority right now."
- **Iteration:** Tighten the ICP filters. E.g., Stop targeting "Managers" and only target "Directors," or add a technographic filter to exclude competitor users.

### Symptom 3: Low Meeting Show Rate (< 70%)
- **Diagnosis:** The play pitch was misleading, or there was no urgency established in the sequence.
- **Iteration:** Implement a pre-call agenda email and a day-of reminder. Ensure the sequence copy aligns exactly with what the AE pitches.

## Retirement Criteria

Kill a play completely if:
1. It has run for > 60 days with a Meeting Rate < 0.5%.
2. The data source feeding the trigger breaks or becomes unreliable.
3. The market has shifted (e.g., "Post-COVID return to office" plays are dead).
4. The cost of acquiring the signal data exceeds the CAC (Customer Acquisition Cost) targets.

## Output Contract
When asked to measure or troubleshoot a play, provide:
- A diagnosis of the specific bottleneck based on the scorecard metrics.
- 2 distinct iteration variables to test (e.g., Subject Line A/B test, or Audience Filter shift).
- At what volume you should evaluate the test results.
