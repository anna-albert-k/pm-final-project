# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** A BNPL-minded online shopper like Lena: a digital-native consumer who shops at multiple merchants and wants to decide what to keep before paying.
- **Goal , what this user is ultimately trying to achieve:** Stay in control of her money by paying only for what she actually keeps, without having to manage a different provider at every checkout.
- **Friction / moment of misery , the specific pain blocking their goal:** Riverty only appears at checkout when a merchant chooses to show it, so Lena can’t rely on it. She ends up using whichever provider each merchant offers, and her spending is spread across providers with no single view of what she owes.
- **Current workaround , the external tool or manual process they rely on (M2):** Klarna and PayPal for her BNPL purchases, and spreadsheets to track her finances across them.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** Riverty is only visible where merchants choose to show it, so shoppers like Lena default to Klarna and PayPal, and with CCD2 turning BNPL into credit and adding checkout friction, every month of delay deepens rivals’ habit and makes those shoppers harder to win back.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** A Riverty card that lets Lena pay only once she has decided to keep what she bought, at any merchant, online or in-store, so she keeps control without choosing a different provider at each checkout.

## Read the evidence in your case
- **Where does your case say people stall or leave? Does that match the friction you wrote in Module 2?:** 1. Approved to activated is the main product stall. It is the weakest step after application, and 155 approved people never activated. The invite-to-apply drop is larger, but that is interest in the offer, not experience friction. Note that the data does not say why people didn’t activate. That is a gap to flag, not fill with a guess.

2. Early usage fades. Roughly 1 in 5 activated cards makes no purchase in the first month, and about 28% of first-time buyers don’t reach 3 purchases. Retention by cohort also falls from about 75 to 85% active in month 0 to about 64 to 69% in month 1.

Smaller leaks with clear causes:

Identity check: T-106 (repeat document upload, some applicants give up) explains part of the 88 lost.
Wallet: 143 activated cards never reached the phone wallet (T-102). Wallet isn’t a funnel step, but it likely hurts in-store use.
In-store declines with no reason shown: 48 in the log (T-101), 8.7% in-store decline rate in Month 4.

Merchant visibility is the problem the card is meant to solve. This funnel measures the card’s own journey, so it can’t confirm that problem, but it does show what blocks the solution: activation, wallet setup, unexplained declines and split balances. Habit is also a risk (N-03: “I would tap my bank card”; N-02: a third app to check).
- **What got better or worse in the case, and does that support the workaround your persona uses?:** Volume and spend improved, but usage quality did not. The card is mostly used online, where Lena’s existing workaround already works, and the feature that should set it apart (in-store) is where it fails most. So the data only partly supports the workaround story, and it can’t show whether she replaced Klarna and PayPal.
- **Which user in the case is carrying the pain, and is that the person your Module 2 persona describes?:** By age, 25-34 is the largest group (453 invited) with the highest spend (EUR 235.75). Activation barely varies by age (71 to 73% for most bands, 81.2% for 45-54 on only 65 activated cards), so BNPL intensity separates users far more than age does.

Who carries the pain?

Heavy BNPL users. This is my inference, because the data measures usage and not pain directly.

They adopt most and use most, so they are the people who actually run into the card’s problems.
They have the highest instalments share (25.4%), which is where the two-balance and two-due-date confusion bites (T-103, T-104, N-07).
They already juggle several providers (N-02: “I already have two of these apps”).
Light users are different: they activate least and are wary of anything that sounds like credit (N-05). They are not your persona.

Two tensions to resolve:

The core persona lives online. Heavy users barely use the card in-store, so “works anywhere, online or in-store” is not what they feel most. Their pain is more likely fragmented balances and due dates (B3, B8) than in-store reach. In-store matters more to light users (24.5%) and a few voices like N-04, who are not your core segment.
Visibility is still unproven. Heavy users concentrate on partner merchants, where Riverty is already visible. The segment data cannot show that merchant visibility is the pain.

## Step 2 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** N-07: “I could not see in one place what I owe on the card and what I owe on my normal pay later orders.” Supported by N-02: “I already have two of these apps. A third card is one more thing to check before payday.”
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** Only about half of cardholders keep buying: 51.0% (Month 1 cohort) and 57.1% (Month 2 cohort) are still active at month 2, after losing 13 to 20 points between month 0 and month 1. Heavy users are the people exposed: 5.82 purchases per active month, EUR 320.88 monthly spend, 25.4% instalments share. Gap: T-103 and T-104 (two balances, two due dates) have no ticket counts, so the pain itself is not yet quantified.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** A heavy BNPL user aged 25-34, placing 4+ pay later orders a month across several providers. She wants purchases to leave her account only after she keeps them. The confirmed friction is that she has to track a second balance and due date.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Heavy BNPL users cannot see in one place what they owe on the Riverty card and on their regular pay later orders, so the card adds work instead of removing it and they fall back to their existing workaround.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Expected behaviour: she keeps the Riverty card as a regular payment method and shifts pay later purchases to it. Retention: fewer lapses after month 1. Revenue: more volume per active card (Month 4 baseline EUR 233) and a higher instalments share (17.4%). Churn: fewer shoppers drifting back to Klarna and PayPal.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Month 2 activity rate of activated heavy users (share still making at least one purchase). Baseline 51 to 57% across all users. Assumption: target 65% or higher.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Existing Riverty pay later checkout volume per active user must not fall. The pack has no baseline, so you need to set one. A second guardrail from the data is the overall decline rate, which should not go above the Month 4 level of 3.5%.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** Two full activation cohorts observed through month 2, roughly 3 to 4 months after release, with at least about 130 heavy activated users per cohort (the pilot had 138). Assumption: scale at 65% or higher, iterate at 55 to 64%, pivot or kill below 55% (no better than baseline). Factor in N-11: any change to terms or due dates goes through approval, which takes months.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on N-07 (“I could not see in one place what I owe on the card and what I owe on my normal pay later orders”) and the pilot data showing only 51.0% to 57.1% of cardholders still active at month 2, I believe that giving one balance view and one due date for the card and regular pay later orders to heavy BNPL users aged 25-34, who place 4+ pay later orders a month across several providers, will result in them keeping the Riverty card as a regular payment method instead of reverting to Klarna and PayPal, as measured by a 10 to 15 percentage point increase in Month 2 activity among activated heavy users (from the 51 to 57% baseline to 65% or more). I will protect existing Riverty pay later checkout volume per active user and keep the overall decline rate at or below the Month 4 level of 3.5%, and will make a go/no-go decision after two activation cohorts have been observed through month 2 (roughly 3 to 4 months after release).
