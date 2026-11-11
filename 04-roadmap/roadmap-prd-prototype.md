# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** A heavy BNPL user aged 25-34, placing 4+ pay later orders a month across several providers. She wants purchases to leave her account only after she keeps them, and she wants to see what she owes in one place.
- **Primary success metric (M3), your leading indicator:** Month 2 activity rate of activated heavy users (share still making at least one purchase). Baseline is 51.0% to 57.1% across all users; target 65% or more. The target is my assumption.
- **Moment of misery (M2), the specific friction blocking the goal:** She cannot see in one place what she owes on the Riverty card and on her regular pay later orders (N-07, T-103). Two due dates in the same week for different amounts add to it (T-104).
- **Guardrail metric (M3), what must not drop or break:** Existing Riverty pay later checkout volume per active user must not fall (baseline still to be set). Second guardrail: overall decline rate at or below the Month 4 level of 3.5%.

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** B1 Decline reason and retry hint
Why: Mostly an in-app message, with no change to pricing, credit policy or terms, so it likely avoids the approval delay in N-11. It protects your decline-rate guardrail (3.5% overall, 8.7% in-store in Month 4).
Evidence: T-101 (48 in-store declines with no reason), N-06 (declined at a bakery, back to the debit card the same week).
B2 Add to phone wallet from the approval screen
Why: A flow and placement change that targets a measurable leak.
Evidence: T-102 (143 activated cards never reached the wallet), baseline of only 66.8% of activated cards added.
B3 One balance view
Why: Likely a display change that combines data you already hold, so effort may be moderate rather than low. It is your only feature that can score a 5 on Value.
Evidence: N-07, T-103.

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** B4 Choose pay now or pay later: Value 4 to 3, Effort 3 to 4, Next to Later. The AI’s own rationale says there is no evidence it changes Month 2 activity, so Value 4 contradicts the rule that only features moving the primary metric score high. It also likely needs terms changes (N-11), so Effort is higher.
B3 One balance view: Value 5 and Effort 3 unchanged, Next to Now. It is the only feature that removes the moment of misery (N-07, T-103), so it should start this sprint.
B1 Decline reason and retry hint: Value 3 and Effort 2 unchanged, Later to Now. It is cheap and protects the decline-rate guardrail (see the third answer).
B2 Wallet from approval screen: Value 3 to 2, Later to Next. Heavy users are only 12.1% in-store, so it is not the core friction, but the leak is real (T-102).
B8 One due date: scores unchanged, kept in Next, but the terms approval request starts in sprint 1 because approval takes months (N-11).
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** Yes, B4 at Value 4. No interview asks for choosing pay now or pay later per purchase. The only related signal is general control (N-01), which is weak support. The AI scored the Sales-flavored features correctly: B5 partner offers (N-09 comes from merchants, not the persona) and B6 cashback (N-12 says it drives trial, not continued use) both stayed at Value 2 and in Cut. The data pack does not label which features came from Sales or Engineering, so say that this is my reading.
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** Yes, B1 (and partly B2). The AI parked both in Later on persona fit alone, but M3 shows a guardrail problem:

The overall decline rate rose from 2.6% in Month 3 to 3.5% in Month 4, the highest of the pilot, and the in-store decline rate rebounded from 6.4% to 8.7%.
T-101 logs 48 in-store declines with no reason shown, and N-06 shows a user who went back to her debit card the same week.
Only 66.8% of activated cards reached the phone wallet (143 never did, T-102).

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** My “Now” lane (this sprint)

B3 One balance view for card and pay later orders
Value 5, Effort 3 (Major Project)
Why first: It removes the moment of misery (N-07, T-103) and is the only feature that directly moves Month 2 activity among heavy users.
B1 Decline reason and retry hint
Value 3, Effort 2 (Fill-In)
Why now: It is cheap, needs no policy approval, and protects the 3.5% decline guardrail. The overall decline rate rose to 3.5% in Month 4, and in-store declines with no reason (T-101, 48 cases) sent users back to their debit card (N-06).
B8 terms approval request (a task, not a build)
Why now: Approval takes months (N-11). Submitting in sprint 1 keeps the B8 build inside your 12-week window.
- **What I cut, and the “no” I’m protecting the scope from:** B5 Offers from partner merchants inside the card app
Why cut: The interest comes from merchants (N-09), not the heavy BNPL persona, and it needs merchant integrations (Effort 4).
The “no”: Sales and merchant partners will ask for it because it gives them traffic. It does not touch the moment of misery or Month 2 activity, so it stays out until the core friction is fixed.
B6 Cashback on every purchase
Why cut: N-12 says cashback would make her try the card, but whether she keeps using it is “a different question.” Our problem is retention after month 1, not trial.
The “no”: Cashback feels like a fast growth lever, but it adds a margin cost and risks attracting one-time triers who lower the quality of Month 2 activity.
B7 Physical card
Why cut: No evidence it addresses the friction, and it is the most expensive item to produce and ship (Effort 5).
The “no”: A physical card is the obvious answer to “how do I pay in shops,” but heavy users are only 12.1% in-store, so it solves a problem this persona mostly does not have.
- **Prototype/roadmap screenshot link (paste into your deliverables):** _(not filled in)_
