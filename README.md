# Workspace Monika

Work and earnings tracker for Monika Purba, independent contractor at Saha Synergy Group Ltd.

**Live:** https://sisterhoodos.github.io/workspaceteam/

## Tabs

- **Month Summary** — what you earn this month, split between approved and awaiting approval, plus an admin-hours-per-week check against the 25 hr cap
- **My Schedule** — standing weekly and monthly commitments (how many reels, how many hours, due by which day) with live progress against what has actually been logged
- **Daily Admin** — the day-to-day task list: WhatsApp number, link, time, category, who it involves, notes, billable hours. Finished hours push through to Log Work as one admin entry per day, and each task is only ever billed once
- **Log Work** — entry form, rate fills in automatically from the work type, with fields for the link to the work and approval status
- **Approvals** — everything still waiting on Sophia's sign-off
- **Salary Paid** — what Sophia paid, when, at what time, with transfer proof, plus logged-versus-paid reconciliation
- **Petty Cash** — company money in and out, receipt attachments, monthly movement, spending by category, CSV import
- **Contract** — the full rate card, general terms, and the example month
- **Data & Backup** — JSON backup and CSV export

## Palette

Burgundy `#6A1024`, olive `#6B7524`, chocolate `#362017`, ivory `#F2EDE8`.

## Petty cash seed

Monika's existing finance spreadsheet (March to July 2026) ships preloaded: 191 records, IDR 46,400,000 in and IDR 46,995,417 out, closing at minus IDR 595,417. The importer accepts more CSVs in the same shape (Date, Description, Debit, Credit; blank dates carry down).

## Basis of calculation

Follows the document signed 16 July 2026, the version with admin hours at 15 to 25 per week. Reference rate 18,000 IDR per USD.

## Data

Saved in browser `localStorage` under the key `monika_workspace_v1`. Never sent to a server. It only exists on the machine used to open the page, so download a backup regularly.

## Layout

Responsive. On phones the tables restack as labelled cards rather than scrolling sideways. Verified with no horizontal overflow at 390px, 768px, and 1280px.

## Making changes

Edit `index.html`, then:

```
git add -A
git commit -m "your message"
git push
```

GitHub Pages serves branch `main` from root. Changes appear about a minute after the push.
