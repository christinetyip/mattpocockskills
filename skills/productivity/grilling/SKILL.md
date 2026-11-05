---
name: grilling
description: Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.
---

Interview the user relentlessly until you reach a shared understanding. Map this as a **design tree**: every decision branches into the decisions that hang off it.

Work the tree in **rounds**. The **frontier** contains every decision whose prerequisites are settled. Ask the whole frontier as numbered questions, then wait for the user's answers. If one choice depends on another, ask the upstream question first and save the dependent one for the next round.

For each question, compare the viable options, usually two or three. Spell out any consequence the user could easily miss before asking them to choose. For example, if anyone with a link can open a draft, a recipient who forwards it is effectively deciding who else can read it. Focus on effects that could change the user's answer, including earlier agreements the choice would reopen or work that would be costly to undo. If only one option is feasible, explain the constraint.

```
❓ **Q1. <What decision does the user need to make?>**

| Option | What it means in practice | What you gain and give up | Who or what it affects |
| --- | --- | --- | --- |
| <A> | ... | ... | ... |
| <B> | ... | ... | ... |

➡️ **I recommend <option>.** <Explain which user goal, constraint, or earlier decision tips the balance and why the cost is worth accepting.>
```

The user can say "yes" to accept a question's recommendation, pick another option, or suggest their own. A recommendation stays a proposal until the user chooses.

After each round, briefly reflect back what the answers settled and recompute the frontier. If a later answer or discovery conflicts with an earlier agreement, name that agreement, explain what would change, and let the user decide whether to revise it.

Use the available evidence to distinguish known effects from assumptions. For facts you can look up, dispatch a subagent with a fresh context window if available, or check directly. Keep the investigation read-only. While a fact is pending, continue with independent questions. If only the user knows a fact that could reverse your recommendation, ask for it before presenting the dependent choice.

When every branch has been discussed, summarize the agreed scope, the material consequences, and anything the user chose to defer. Keep the interview in the conversation. Start implementation only after the user explicitly approves building that scope. A "yes" to a design question settles only that question. If the build reveals a materially different impact, pause the affected work and discuss it with the user before proceeding.
