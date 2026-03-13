# Ecosystem: gtm-plays-collection

How this repo connects to the rest of the Forma Norden GTM library.

## Works With

| Repo | Relationship | When to use together |
|------|-------------|---------------------|
| ``cold-email-copy-playbook`` | Downstream | Once a play is selected, use the copy frameworks to write the actual emails. |
| ``buying-window-signal-workflow`` | Upstream | Signals scored in that workflow trigger the "Signal-Triggered Plays" defined here. |
| ``outbound-personalization-playbook`` | Parallel | Strategy applies here: Tier 1 plays get manual deep personalization; Tier 3 get segmentation. |
| ``n8n-gtm-workflow-pack`` | Downstream | Automation routes leads into the correct CRM sequence based on the play selected. |

## Suggested Skill Chains

1. Reacting to Intent: ``signal-scoring-router`` > ``signal-triggered-plays`` > ``n8n-node-patterns``
2. Building Outbound Sequences: ``play-selector-and-scoring`` > ``outbound-sequence-plays`` > ``writing-frameworks`` > ``email-template-library``
