# CSP Screen Reviews

Side-by-side reviews of Wiom CSP in-app screens & notifications, comparing the **current** with **suggested** revisions. Each item is shown beside its suggested version with every change called out.

## 1. Daily Report — `index.html`
The CSP daily report sent at 10 AM over two pages.
- **Page 1 — कल कैसा रहा?** (yesterday's status): All Done · None Done · Partial
- **Page 2 — आज के काम** (today's tasks): All Assigned · None Assigned · Some Unassigned

Screens embedded from `page1-yesterday/`, `page2-today/` (current) and `suggested-v1/` (revised).

## 2. SR-3 & SR-4 Timer Nudges — `sr34-review.html`
Full-screen SLA timer nudges with live countdowns.
- **SR-3** (pre-breach & deadline): 4-hr · 24-hr · time-over (0:00)
- **SR-4** (overdue re-ping): bomb + count-up · churn warning

Screens embedded from `sr34/current/` and `sr34/suggested/`.

## 3. Push Notifications — `push-notifications-review.html`
Lock-screen previews of the SR-1 / SR-3 / SR-4 push-notification hooks.
- Each series shows **Recommended · Alternate · Sol. Design's Recommendation**.
- Live character-count checks against the lock-screen limits (title ≤ 40, body ≤ 90).
