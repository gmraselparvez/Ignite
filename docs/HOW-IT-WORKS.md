# How Ignite Works

A walkthrough of the app's flow, from starting a session to sending an invoice.

---

## The basic loop

```
   Add a client  ->  Create a project  ->  Add tasks  ->  Focus on a task
                                                              |
                                                              v
        Invoice the client  <-  Review reports  <-  Time is tracked automatically
```

Ignite is built around one idea: **the time you focus becomes the reports and invoices you send.** You don't track time separately — focusing on a task *is* tracking it.

---

## 1. Set up your work

- **Clients** — the people or companies you work for (name, company, email, phone, address, currency).
- **Projects** — belong to a client, and carry a billing mode (hourly / fixed / non-billable) and rate.
- **Tasks** — belong to a project, with a priority, due date, target time, and optional per-task billing.

You manage all three from dedicated pages in the dashboard.

## 2. Focus and track

- Open the **menu-bar popover** and you'll see your timer and a stacked "task deck."
- Press **play on a task** to start focusing on it. The Pomodoro timer runs; the time counts toward that task.
- **Switch tasks anytime** — Ignite records the partial session and moves your focus to the new task.
- Prefer open-ended work? Use the **manual (count-up) timer**.
- Step away and Ignite notices you're idle; it can pause so idle minutes aren't billed.

## 3. Take smart breaks

- When a focus block ends, a **break screen** appears (full-screen or windowed).
- You choose how strict breaks are: **Casual** (skip anytime), **Balanced** (skip after 10s), or **Hardcore** (no skips).
- If you're **in a meeting** when a break is due, Ignite postpones it silently and reminds you afterward — it never interrupts a call.
- Breaks can show **wellness tips** (stretch, eye rest, posture, hydration) and optionally lock your screen.

## 4. Stay focused with blocking

- Turn on **distraction blocking** to hide chosen apps and close chosen website tabs.
- Use a **blocklist** (block these) or **whitelist** (allow only these).
- Blocking can run **during focus sessions**, on a **daily schedule**, or on-demand with **"Block now for 1 hour."**

## 5. Capture meetings

- Ignite **detects meetings** automatically (camera, microphone, or a meeting app in front).
- A small **floating panel** appears where you can jot participants, notes, and action items — it never steals focus from your call.
- Optionally **record & transcribe** your mic on-device.
- Afterward, press **Generate AI Minutes** to turn notes + transcript into a title, summary, key points, decisions, action items (with assignees), and follow-ups.
- Turn any action item into a task in one click. Export the meeting to PDF.

## 6. Review your work

- The **Overview** shows today's focus, deep-work sessions, meeting time, revenue, streaks, and a billable-vs-non-billable split.
- **Reports** let you scope by project, client, or date range, with an hours-per-day chart and a time-by-project breakdown.
- Toggle per-task detail on or off; export to **A4 PDF** (with charts) or **CSV** for Excel.

## 7. Get paid

- Generate an **invoice** from tracked time. Billing is always **project total time × the project rate**, so the math is transparent.
- Every field is **editable before export** — line items, rates, tax, discount, notes, and the Bill From / Billed To blocks.
- Add your **logo, business name, and accent color** for branded invoices.
- Preview live, then export to **A4 PDF** or print.

---

## Where your data lives

Everything is stored locally on your Mac (Application Support). There's no sign-in and no cloud sync. The only network activity is the optional AI-minutes request, which you trigger manually with your own API key.
