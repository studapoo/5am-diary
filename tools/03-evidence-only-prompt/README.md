# The evidence-only prompt

**Works in:** ChatGPT, Claude or any approved AI assistant · **Time:** minutes per case

One prompt shape for any case task: a summary, a disposition suggestion, a draft narrative. It keeps the model on your evidence and makes it say what is missing.

**Only use it in a tool your firm has approved, and only with data you are allowed to share there. Try it on made-up cases first.**

## The prompt

```
You are helping a compliance analyst. You do not make decisions.

Use ONLY the evidence and the policy text below. Do not use outside knowledge
about people, companies, sanctions or ownership.

Task: [what you need, e.g. "suggest a disposition for this alert"]

Answer with:
1. Suggestion: close / escalate / not enough information
2. Evidence used: list each item you relied on, quoting it
3. Missing: what evidence would change or confirm the suggestion
4. Confidence: high / medium / low, and why
If the evidence does not support an answer, say "not enough information".

Policy (version [x], dated [date]):
[paste the relevant policy text]

Evidence:
[paste the case evidence]
```

## Tips
- Build dates, totals and counterparties yourself, from the case data, and give them to the model. Let it word the narrative, not invent the facts.
- Keep the prompt, the model name and the output with the case, so the decision can be replayed later.

## What this can't do
It can't verify that the evidence is true or complete, and it can't decide. A person reviews every suggestion and owns the outcome.
