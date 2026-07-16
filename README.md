<div align="center">

<img src="docs/assets/Ignite.png" />

# Ignite

### Focus. Track. Deliver.

A distraction-free **macOS** menu-bar app that combines focus sessions, project & task management, automatic time tracking, AI meeting minutes, reporting, and invoicing — built for freelancers and focused professionals.

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-000000?logo=apple)
![Type](https://img.shields.io/badge/app-native%20menu--bar-orange)

**[⬇ Download the latest version](../../releases/latest)**

</div>

---

## What is Ignite?

Ignite lives in your menu bar. Start a focus session and it tracks your deep work, keeps you honest with smart breaks, blocks distractions, quietly captures your meetings, and turns all of it into reports and client-ready invoices.

Everything runs **locally on your Mac** — no account, no cloud, no tracking.

## Features at a glance

- ⏱️ **Focus timer** — Pomodoro + manual count-up modes, with per-task tracking right from the menu bar.
- 🧘 **Smart breaks** — enforcement tiers, meeting-aware postponing, and wellness reminders (stretch, eyes, posture, hydration).
- 🚫 **Distraction blocking** — block apps & websites, on a schedule or during focus, with a "block now" override.
- 📁 **Projects, clients & tasks** — full hierarchy with priorities, due dates, billing, and editable tracked time.
- 🎙️ **Meetings & AI minutes** — auto-detects calls, transcribes on-device, and generates structured minutes (summary, decisions, action items).
- 📊 **Reports** — hours-per-day and time-by-project charts; export to A4 PDF or CSV.
- 🧾 **Invoices** — generated from tracked time, fully editable, with custom branding and A4 PDF export.
- 🖥️ **Dashboard** — focus, revenue, streaks, and billable split at a glance.

---

## How Ignite works

Ignite is built around one idea: **the time you focus becomes the reports and invoices you send.** You don't track time as a separate chore — focusing on a task *is* tracking it.

```
   Add a client  →  Create a project  →  Add tasks  →  Focus on a task
                                                            │
                                                            ▼
      Invoice the client  ←  Review reports  ←  Time is tracked automatically
```

### 1. Set up your work

Ignite organizes everything in a simple hierarchy:

- **Clients** — the people or companies you work for. Store name, company, email, phone, address, and preferred currency.
- **Projects** — each belongs to a client and carries a billing mode (**hourly**, **fixed price**, or **non-billable**) and a rate.
- **Tasks** — each belongs to a project, with a priority, status, due date, target time, labels, notes, and optional per-task billing that can override the project's.

You manage all three from their own dedicated pages in the dashboard, so nothing feels buried.

### 2. Focus and track time

- Open the **menu-bar popover** to see your timer and a stacked "task deck" of what's next.
- Press **▶ play on any task** to start focusing on it — the Pomodoro timer runs and the time counts toward that task automatically.
- **Switch tasks anytime.** Ignite records the partial session for the task you were on and moves your focus to the new one — no manual stop/start.
- Prefer open-ended work? Use the **manual (count-up) timer** instead of a fixed Pomodoro block.
- The timer is **drift-free** — it stays accurate across sleep/wake — and **idle detection** can pause it when you step away, so idle minutes aren't billed.
- Need to correct a time? **Tracked time is fully editable** on any task, and the change flows through to reports and invoices instantly.

### 3. Take smart breaks

- When a focus block ends, a calming **break screen** appears (full-screen or a centered window — your choice).
- You decide how strict breaks are:
  - **Casual** — skip anytime.
  - **Balanced** — skip unlocks after 10 seconds.
  - **Hardcore** — no skipping.
- **Meeting-aware:** if a break is due while you're on a call, Ignite **postpones it silently** and reminds you once the meeting ends — it never throws a full-screen break over your video call.
- Breaks can show **wellness tips** (stretching, 20-20-20 eye care, posture, hydration) and optionally **lock your screen** on long breaks so you actually step away.

### 4. Block distractions

- Turn on **distraction blocking** to hide chosen apps and close chosen website tabs while you focus.
- Choose your style:
  - **Blocklist** — block the apps/sites you list.
  - **Whitelist** — allow only the apps/sites you list, block everything else.
- Blocking can run **during focus sessions**, on a **daily schedule** (e.g. Mon–Fri 09:00–17:00), or on demand with **"Block now for 1 hour."**
- Need a moment? A **temporary override** lets you pause blocking briefly.

### 5. Capture meetings automatically

- Ignite **detects when you're in a meeting** — via your camera, microphone, or a meeting app in front (Zoom, Webex, FaceTime; calls in Discord/Slack/Teams/WhatsApp/Meet are detected by mic/camera use).
- A small **floating panel** appears where you can note participants, jot notes, and add action items — it's non-intrusive and never steals focus from your call.
- Optionally **record & transcribe** your microphone, fully **on-device** using Apple's speech recognition.
- Afterward, press **Generate AI Minutes** to turn your notes + transcript into a clean, structured report:
  - a title and concise summary,
  - key discussion points,
  - decisions made,
  - action items (with assignees where identifiable),
  - and follow-ups.
- Turn any action item into a **task** with one click, **search** past meetings, and **export** any meeting to PDF.

### 6. Review your work

- The **Overview** shows today's focus time, deep-work sessions, meeting time, revenue, current/longest streaks, and a billable-vs-non-billable split, plus a 14-day focus chart.
- **Reports** let you scope by **project, client, or date range**, with an hours-per-day bar chart and a time-by-project donut.
- Toggle **per-task detail** on or off, then **export to A4 PDF** (charts included) or **CSV** for Excel.

### 7. Get paid

- Generate an **invoice** straight from tracked time. Billing is always **project total time × the project rate**, so the math is transparent and consistent.
- **Every field is editable before export** — line items, quantities, rates, tax, discount, notes, and the **Bill From / Billed To** blocks.
- Add your **business logo, name, and accent color** for fully branded invoices.
- **Preview live**, then export to **A4 PDF** or print.

---

## Installation

1. Download **`Ignite.dmg`** from the [latest release](../../releases/latest).
2. Open the DMG and drag **Ignite** into your Applications folder.
3. **First launch:** right-click (or Control-click) the Ignite app and choose **Open**, then click **Open** again.
   > This is only needed the first time. macOS shows a warning because the app isn't distributed through the App Store.

### Requirements
- macOS 14 (Sonoma) or later

---

## Permissions

Ignite only asks for what a feature needs, when you use it:

| Permission | Why |
|---|---|
| Notifications | Session and break alerts |
| Microphone + Speech | On-device meeting transcription (only while recording) |
| Automation (Safari/Chrome) | Closing distracting tabs during blocking |
| Network | AI meeting minutes (only when you press "Generate") |

All your data stays on your Mac. The only time anything leaves your device is an AI-minutes request you explicitly trigger, using your own API key.

## Optional: AI meeting minutes

To enable AI-generated minutes, add an Anthropic API key in **Settings → Meetings & AI**. It's stored locally and only used when you generate minutes.

---

## Version history

See **[CHANGELOG.md](CHANGELOG.md)** for the full list of changes.

---

<div align="center">
Made for people who value deep work.
</div>
