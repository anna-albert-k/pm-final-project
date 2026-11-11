# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** B3 One balance view for card and pay later orders
Core description: A single screen that shows heavy BNPL users everything they owe, across the Riverty card and their regular pay later orders, in one total with a clear breakdown.
- **My finalized Must-Haves (after overriding the AI):** MUST HAVE (first sprint)
One total owed. A single number combining the card balance and open pay later orders. This answers “which total is the real one” (T-103).
Clear split under the total. The card portion and the pay later portion, each labeled, so she can see what the total is made of (N-07).
Amount and due date per obligation. Each item shows what is due and when. This is display only and does not change any due dates. It gives her what she needs to plan before payday (T-104).
One entry point. The view sits in a single place in the app, and the two old screens either redirect to it or stop showing a conflicting total.
Totals that reconcile with source systems. If either source fails to load, show a clear message instead of a partial total. A wrong total would damage trust more than no total.
Read-only. No payment or editing actions in this release.
- **What I demoted from Must → Should/Won’t, and why:** SHOULD HAVE (if capacity allows)
Upcoming payments sorted by due date. Helps with the two reminders in one week for different amounts (T-104).
Usage tracking for the view. Events for views and for Month 2 activity of heavy users, so you can read the primary metric. Challenge: this is not a must-have by your rule, because users can see their balance without it. But treat it as a launch gate, because without it the decision window cannot be run.
Deep link from reminder notifications to the view. Connects the reminder moment to the answer.
Plain-language note on what is included in the total. Reduces confusion cheaply.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The PRD makes explicit that the view shows due dates but does not unify them. A vague brief (“give users one balance view”) would have let that slide, and it hides the biggest scope risk.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** Screen 3 doesn’t fit a read-only feature.
Gap: There is nothing to confirm, because no action is taken. I turned it into an obligation detail with a reconciliation line.
Update: Rename it “Obligation detail” and drop the “success/confirmation” framing, or say the course template forced it.
“Next due” breaks with an overdue item.
Gap: The earliest date is the overdue one, so “Next due” points to the past.
Update: Show “Overdue: 1” on the home tile, or label the earliest open date “Earliest due”.
Failure on the home tile was unspecified.
Gap: The PRD says no partial total anywhere, but doesn’t cover the tile. I made it show “Unavailable”.
Update: Add the tile to the smart behaviors table. Also define what Retry does and add a loading state. Retry currently re-checks and fails again until you change the demo control.
The “due soon” rule has no reference date and a bug.
Gap: “Within 3 days” needs a date, so I fixed one for the demo. A due date of today also reads “Due in 0 days”.
Update: Add a “Due today” rule to the PRD. I can fix the label in the proto
- **My prototype: save Claude's HTML as prototype.html in 04-roadmap/, open it in your browser, and add a screenshot:** _(not filled in)_
