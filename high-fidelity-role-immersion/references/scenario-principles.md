# Scenario Design Principles & Examples

Good scenarios force the role's operating system to reveal itself. Bad scenarios allow generic intelligent answers dressed in the role's vocabulary.

## Required Elements

1. **Concrete stakes** — Something real can be gained, lost, or permanently damaged.
2. **Incomplete information** — The role must decide what to weight and what to discount.
3. **Value conflict** — At least two of the role's own priorities are in tension, or external pressure conflicts with an internal rule.
4. **Time or resource pressure** — Forces prioritization.
5. **Testable core belief** — The situation should make one of the role's central heuristics fire.

## Weak vs Strong Examples

### Munger
- Weak: "What do you think of Tesla?"
- Strong: "You bought a high-quality compounder at what you believed was a fair price three years ago. It is now down 55%. The business metrics are roughly on plan. Your partners are questioning the original thesis. Walk through your current thinking and what would make you sell versus average down."

### Mafia Boss
- Weak: "How important is loyalty?"
- Strong: "One of your most effective captains has been taking side payments from a rival group. The evidence is solid but not courtroom-proof. He still generates the highest revenue in his territory and has strong personal loyalty from his crew. What do you do this week, and what signal does it send?"

### Satoshi
- Weak: "Is Bitcoin too slow?"
- Strong: "A well-resourced group proposes a protocol change that would increase throughput by 50x but requires a small set of identified validators to remain honest for finality. They argue the practical security is higher because of their reputation and capital. Draft the response you would publish."

### Political Operative
- Weak: "How do you handle a scandal?"
- Strong: "A story is about to break that damages a key ally who sits on a committee you need next month. You have partial contradictory information that could muddy the story, but releasing it would also expose a different friendly source. The President wants options in two hours. Outline the real choices and the second-order effects of each."

### Elon
- Weak: "How do we innovate faster?"
- Strong: "Your most important project is six months behind. The bottleneck is a supplier who is politically connected and has been given repeated extensions. Engineering says a vertical integration path exists but would take nine months and significant capital. Board pressure is rising. What do you actually do in the next 30 days?"

## Testing Protocol for Heterogeneous Evaluation

When testing the same role + scenario across different models:

1. Use identical role card text.
2. Use identical scenario text.
3. Score only on:
   - Fidelity to value hierarchy (not vocabulary)
   - Presence of non-obvious risk or cost the role would care about
   - Resistance to collapsing into generic helpfulness under pressure
   - Clarity of cognitive delta after forced exit
