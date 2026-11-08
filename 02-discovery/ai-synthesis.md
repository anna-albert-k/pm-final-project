# AI Synthesis, Product Health & Insights Summary (Module 2)

## Responses
- **Assumption to validate #1:** Consumer card is the product users would love
- **Assumption to validate #2:** Customer loyalty features will incetivise to use the card
- **Assumption to validate #3:** Consumer card can increase Riverty brand prpesence
- **Moment of misery / red flag #1 (e.g., “user gave up after 3 tries”):** Interest fee
- **Moment of misery / red flag #2:** Decline made user churn
- **Moment of misery / red flag #3:** No transparency over spendings
- **Product Health & Insights Summary (Claude's output):** Product Health & Insights Summary: First Consumer Card (Test Launch)

Basis: fictional practice data from a 1,200-person invite-only test over four months.

Executive Summary

The card is not failing at the core transaction. Online purchases work, approval is high, and heavy BNPL users adopt it readily, but the in-store experience, wallet setup and fragmented balance and due-date views erode trust at the moments that matter most. Roughly one in four approved users never activates, and only about half of each cohort is still active two months later, so technical friction and unclear value compound each other. Because the test group skews toward employees and friends, these results probably flatter real-market performance.

Thematic Synthesis
1. Technical Stability (In-Store and Wallet)

The online path is stable, but the physical-world path is not. In-store declines run far above the overall decline rate, they spiked again in Month 4 after improving, and the app gives users no reason when a payment fails. Wallet provisioning is a separate weak point: about a third of activated cards never reach the phone wallet, which blocks the tap-to-pay habit that in-store use depends on. Users who hit a decline in a shop tend to revert to their debit card.

In-store declines with no reason shown (Critical): in-store decline rate ran 12.1%, 7.5%, 6.4% and 8.7% across the four months, against 2.2% to 3.5% overall. Users abandon the card after one embarrassing failure.
Wallet provisioning fails or is abandoned (High): 143 of 431 activated cards (33%) never reached the wallet.
Delayed purchase notifications (Medium): late pushes lead users to assume the payment failed and pay again with another card.
2. Onboarding and Activation

The funnel is healthy through approval, then leaks at activation. Of 586 approved users, 155 (26.5%) never activate. Identity verification also loses applicants, and the retry flow adds avoidable friction.

Approved-but-not-activated users (High): 73.5% activation of approved, with light BNPL users at 62% against 83% for heavy users.
Repeated document photo request after a failed upload (Medium): some applicants give up at this step. 88 people were lost between application and completed identity check, though not all are attributable to this issue.
Early engagement fades quickly (High): 81% of activated cards make a first purchase, but only 72% of those go on to three or more purchases in the activation month.
3. Trust and Clarity

The recurring theme in both interviews and tickets is that users cannot tell what they owe, to whom, and when. The card and regular pay later orders sit on separate screens with separate due dates, so reminders conflict and users question which total is real. For a credit-adjacent product with a nervous, instalment-averse segment, this ambiguity is a trust problem as much as a UX one.

No unified view of card balance and pay later orders (High): participants ask which total is the real one.
Misaligned statement and pay later due dates (High): two reminders for different amounts can land in the same week.
Perceived “instalments equals credit card with interest” (Medium): light users (45-54) report nervousness about the framing, which depresses uptake in that segment.
4. Value Proposition and Sustained Usage

Adoption is strongest where the card extends an existing habit, mainly online pay later among heavy users, who generate roughly 2.5 times the monthly spend of light users. Outside that group the reason to use the card instead of a debit card or another app is weak, and in-store share stays low at about 17%. Cashback is cited as a trigger to try the card but not a reason to keep using it. Merchants are split: they want demand sent to them rather than to large marketplaces.

Weak habit displacement in stores (High): users default to their bank card and forget the card exists.
Retention decay (High): activity after two months is 51% to 57% of an activation cohort, and active cards fell from Month 3 to Month 4 even as volume grew.
Unclear merchant value (Medium): enterprise merchants ask what they gain over their own checkout, and SME merchants value offers only if traffic is not diverted to marketplaces.
App fatigue (Medium): heavy BNPL users already juggle several similar apps.
5. Support Load

Support demand is largely a by-product of the clarity and stability issues above, and the self-service content to absorb it does not yet exist. Expect inbound volume to scale with launch size, driven by “why was I declined,” “which balance is correct” and “does this affect my credit score.”

Declines with no explanation (High): drives contact and churn simultaneously.
Duplicate or conflicting reminders and balances (Medium): generate “which amount do I pay” queries.
Double payments after delayed notifications (Medium): create refund and reconciliation work.
6. Evidence Quality and Delivery Constraints

These findings should be read with caution, and they bear on how quickly any issue can be addressed.

Biased test population (High): employees are 53% of invitees, so the 93.3% approval rate and repayment behavior likely overstate real customers.
Short observation window (Medium): four months cannot support annual churn or lifetime spend. The EUR 2,595 annual spend figure is a 12x extrapolation, not an observation.
Slow change cycle (Medium): proposition changes require pricing, credit policy and terms approval that takes months, which limits how fast learnings can be applied.
Minor Technical Debt

Instalment option shown inconsistently by purchase category, no help article on credit score impact, and small cohort-level volatility in activity metrics (Low).
- **Did the AI catch the specific moment of misery / pain point you found in Step 1?:** no
- **Did it smooth over a critical frustration into a generic bullet point?:** yes
- **Did the AI try to suggest features or a roadmap despite the constraints?:** no
- **Logic leak / hallucination #1 (e.g., “AI suggested a new search bar feature, roadmap leak”):** _(not filled in)_
- **Logic leak / hallucination #2:** _(not filled in)_
