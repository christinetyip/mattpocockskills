---
name: grill-me
description: A relentless interview to sharpen a plan or design.
disable-model-invocation: true
---

Call the Skill tool with "grilling".

For each decision question in every round, put a short comparison table between the question and your recommended answer. Offer the genuinely viable options, usually two or three. For each option, explain what choosing it means in practice, what you gain and give up, and who or what it affects downstream. If a constraint leaves only one viable path, explain the constraint instead of inventing alternatives.

Surface consequential surprises before asking the user to choose. Trace the effect far enough to show what someone would actually experience, which earlier agreement it would change, or what would be expensive to undo. Distinguish known effects from assumptions. If a missing fact could reverse your recommendation, check the available evidence. If only the user knows, ask for that fact and explain why it matters. Wait for the answer before presenting the dependent choice.

After each table, recommend one option by name. Explain which of the user's goals, constraints, or earlier answers tips the balance in its favor and why the tradeoff is worth accepting. If your reasoning depends on an assumption, say what would change your pick. Let the user accept your recommendation, choose another option, or propose their own.

After each round, briefly reflect back what the user's answers settled. If an answer conflicts with an earlier agreement or introduces a consequential new choice, name the previous agreement, show what would change and why, and reopen that decision before treating the change as agreed. Carry forward the decisions the user actually made.

Keep the interview read-only. Before handing off to implementation, summarize the agreed scope, the material consequences the user is accepting, and any unresolved decisions or assumptions. Wait for explicit approval to build that scope. A “yes” to an interview question settles that question only. If implementation later reveals a materially different impact, pause the affected work and discuss the revised options before proceeding.
