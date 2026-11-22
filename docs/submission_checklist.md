# Submission checklist (BUAN 3301 final)

## Before you start
- [ ] In your Claude account settings, turn off "help improve Claude" / model training (the assignment requires this for consumer tools)
- [ ] Use only the synthetic data in this repo

## Screenshots to take (save into `screenshots/` with these exact names)
| File | How to get it |
|---|---|
| `redteam-1.png` | Red team tab → set Prompt = v1 naive and Code guardrails = off → run attack 1 → set v2 + guardrails on → run again. Put both results side by side (or take two shots). |
| `redteam-2.png` | Same for attack 2 (GM impersonation) |
| `redteam-3.png` | Same for attack 3 (−$150 refund) |
| `loop.png` | Triage tab after running REQ-1009 (shows all 4 loop stages + guardrail checks) |
| `hitl.png` | Approval queue signed in as Concierge, showing the locked GM-level approval |
| `tracker.png` | Tracker after "Run all & score" (shows accuracy %, tier split, cost, audit trail) |

If v1 happens to resist an attack on a given run (LLMs vary), say so honestly in the README and point out that the code guardrail is what guarantees the block.

## Portfolio (public, no login)
- [ ] Create a public GitHub repo, e.g. `concierge-triage-agent`
- [ ] Upload everything in this folder (README.md renders as the portfolio page; the Mermaid diagram renders automatically)
- [ ] Add your screenshots to `screenshots/`
- [ ] Paste your Loom link into the README's "Video pitch" row
- [ ] Open the repo in a private/incognito window to confirm it's public

## Video
- [ ] Record with `docs/video_script.md` (3:00–5:00)
- [ ] Loom sharing set to "anyone with the link"

## Canvas PDF (single file)
- [ ] Header: Syed Tulush Shams Mahmood · ss5355 · BUAN 3301 · Final Assignment
- [ ] Public portfolio URL (GitHub)
- [ ] Video URL (Loom)
- [ ] Backup export: GitHub README printed to PDF (browser → Print → Save as PDF), including screenshots, the CREATE prompt and the synthetic data sample table
