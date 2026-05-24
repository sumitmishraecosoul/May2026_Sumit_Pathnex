# Linux Course — PathNex (5 sessions)

| Day | Branch   | Focus |
|-----|----------|--------|
| 1   | `day1`   | Basics, file & directory ops (`ls`, `cd`, `find`, `grep`, `awk`, `sed`) |
| 2   | `day2`   | Permissions (`chmod`, `chown`, `umask`) |
| 3   | `day3`   | Processes (`ps`, `top`, `htop`, `kill`, `nice`) |
| 4   | `day4`   | Networking (`curl`, `wget`, `ssh`, `ss`, `dig`) |
| 5   | `day5`   | Logs, `journalctl`, `systemctl`, packaging (`apt`/`yum`) |

## Daily Git workflow

1. `git checkout main` && `git pull`
2. `git checkout -b dayN` (or switch to existing `dayN`)
3. Add `timings/DayNN-DD-Mon-YYYY.txt` and `coding practice/DayNN-DD-Mon-YYYY.txt`
4. `git add .` → `git commit -m "Added DayNN files"` → `git push -u origin dayN`
5. Open PR → merge to `main` → delete branch (optional)

Repo naming: `May2026_Sumit_Pathnex`
