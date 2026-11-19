# Outcome Roadmap & Trade-off Memo: Fable Growth

> Module 2 · Turn Your Strategy into an Outcome Roadmap

## 1. Trade-off memo

> **Rock 1:** Add AI-generated daily check-in prompts personalized to user history (supports KR2): This is the staying-well plan built from the sessions that worked for each user.
>
> **Rock 2:** Fix the notification system (wrong times, timezone bug) (supports KR1): The plan’s reminders and the step-up nudges depend on correct timing and low effort is required to fix that. This is an easy gain for the product.
>
> **Rock 3:** Create a “crisis mode” flow for acute anxiety moments (supports KR3): Users flagged for a new hard stretch get pointed to their own proven sessions, with a clinical guardrail.
>
> **Hard no 1:** Launch a premium tier with therapist-matching: It’s clinical support, which is outside Where to Play. It’s also the hardest no to deliver, and Module 4 asks you to deliver a hard no to a stakeholder.
>
> **Hard no 2:** Redesign the onboarding flow based on 40% drop-off data: The 40% drop-off is real, but it’s an acquisition problem, and we have chosen to focus on recovered users and increase their long term retention. That's the area we are focusing on.
>
> **Hard no 3:** Introduce “Fable for Teams”, a B2B workplace wellbeing offer: B2B and employers are explicitly excluded until the core bet is proven.

## 2. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
| Now (0 to 3 mo) | We bet weekly check-ins built from the sessions that helped each person through their hard time will keep adults who leaned on Fable through stress, sleep problems or a life event practising once they feel better, instead of quietly dropping off (KR2); We bet reminders that arrive at the right local time, not hours off because of a timezone bug, will keep these recovered users practising weekly past their fourth month instead of tuning out mistimed notifications (KR1); We bet that when a recovered user shows early signs of a new hard time, like late-night opens or going back to sleep content, bringing back the sessions that helped them before, with a clinician-approved handoff to professional help, will get them practising again within a week instead of struggling alone until it gets worse (KR3) | Personalisation squad (Product, Data/ML, Design); Platform engineering; Personalisation squad with clinical advisors | Pilot cohort: 50% of plan starters still practise weekly at week 8 (vs. 20%); weekly practice at day 150 moving from 15% toward 25%; 40% of flagged users do 2+ sessions within 7 days (vs. 20%); Q1 survey and pilot show at least 30% of churned engaged users want ongoing practice; consent opt-in and personalisation switch-off rates stay within guardrails |
| Next (3 to 6 mo) | Scale the staying-well plan from the pilot cohort to all users at day 60 to 120 (only if the Q1 test clears 30%; scaling an unproven plan wastes the team); Repackage the existing meditation and sleep library into short modular practices (the plan needs proven demand first, then more building blocks); Build a "what Fable learned about you" moment with consent and transparency controls (trust has to keep up with reach before personalisation goes wide); Cut app load time from 4.2s to under 2s on 4G (a slow start hurts a few-minute session, but the timing and personalisation fixes come first); Close the WCAG 2.1 gap flagged in the audit (a legal obligation with reserved capacity; it isn't a strategic bet and doesn't compete with the Now bets) | Personalisation squad; Content team with Design; Design with Legal and Privacy; Platform engineering; Platform engineering with Legal | 30%+ of users at day 60 to 120 start a plan; plan sessions mostly built from modular practices; consent opt-in holds or rises after the transparency moment and personalisation switch-off stays flat; load time p75 under 2s; audit gap closed |
| Later (6 to 12 mo) | Bet: Apple Watch integration for lower-friction weekly practice and richer early signals of a new hard stretch, pending the consent guardrails holding; Bet: Spanish and Portuguese staying-well plans for existing LATAM users, only once the model works in English; Bet: a win-back-at-the-next-crisis model, kept ready in case the Q1 test fails; Bet: a web version as a second home for weekly practice, if review demand comes from recovered users | Partnerships with Platform engineering; Content team with Sales (LATAM); Growth with the Personalisation squad; Platform engineering | Each bet earns funding only after the Now bets hit their KRs and the bet shows a clear link to day-120+ weekly practice |
