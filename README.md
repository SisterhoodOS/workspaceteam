# Workspace Monika

Work and earnings tracker for Monika Purba, independent contractor at Saha Synergy Group Ltd.

**Live:** https://sisterhoodos.github.io/workspaceteam/

## Tabs

- **Month Summary** — what you earn this month, split between approved and awaiting approval, plus an admin-hours-per-week check against the 25 hr cap
- **Log Work** — entry form, rate fills in automatically from the work type, with fields for the link to the work and approval status
- **Approvals** — everything still waiting on Sophia's sign-off
- **Rate List** — the full rate card from the contract
- **Working Terms** — contract terms and the example month
- **Data & Backup** — JSON backup and CSV export

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
