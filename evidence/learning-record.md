# Learning record | Let AI help with a small campus task

Route: Two periods / 100 minutes  
Exported from the lab page on 10/11/2026; evidence notes added afterward.

> The lab-page export contains browser self-checks and notes; the actual evidence below was added separately.

## Setup — Before you start
- [ ] I can state the full path of the task folder I selected
- [ ] My partner and I checked the tool's current permission and approval settings
- [x] The practice folder contains no real names, student IDs, grades, private photos or passwords

**Notes:**
The selected repository is `411321363/agent-lab-w05`. No group code or partner was provided.

**Actual evidence:**
Repository: https://github.com/411321363/agent-lab-w05

## Task A — One task card to organize a folder
- [x] All originals remain and each organized copy maps to a source (12 for NDHU; actual inventory for the original pack)
- [x] Similarly named files with differing contents were all kept
- [x] I compared two original/copy pairs by content, not only by filename
- [ ] My partner can find unresolved decisions in the organization report

**Notes:**
`announcement.txt` and `announcement_copy.txt` are identical; `equipment_list.txt` and `equipment_backup.txt` are identical. `proposal_final.txt` and `proposal_final2.txt` differ, and neither is approved.

**Actual evidence:**
`practice/01-club-files/output/report.md` and `manifest.json` record all 12 copies. The existing A commit `4babcb1` omitted the identical-content copies; follow-up `3844abe` added them and the required report and manifest. Original inputs remain unchanged.

## Task B — Build “What can I do between classes?”
- [x] Indoor / 15 / low returns only A01–A04
- [x] Outdoor / 15 / medium shows no matches and does not relax the filters
- [x] Outdoor / 30 / medium returns A09 every time
- [x] All / 60 / all, six successful picks: only the latest five remain, newest first
- [x] Reset returns all / 30 / all and the history remains
- [x] After clearing history and switching to English, history is empty and all controls and activity names are in English
- [x] I made one revision, retested the affected functions and kept before/after evidence

**Notes:**
The user ran the six required picker scenarios and reported all passed. The user also checked the mobile-width revision and confirmed it worked. The revision increased button/select minimum height from 42px to 48px and stacks action buttons at widths up to 600px. This is a phone-usability improvement, not a repair to a failed original test.

**Actual evidence:**
`practice/02-campus-picker/output/index.html`; commits `aeefbf5` (v1) and `66857d4` (v2). Test results are user-reported in this task conversation; no test screenshots were saved.

## Task C — clean equipment records
- [ ] 10 input rows become 9 valid rows and the removed count is reported
- [ ] Rows sharing item_id are all kept, not merged or deleted
- [ ] Missing and negative quantities are flagged, not replaced with zero or made positive

**Notes:**
Not requested or performed.

**Actual evidence:**
None.

## Task D — Would you approve this plan?
- [x] I identified at least two problems and explained why they are unacceptable
- [x] I wrote a rejection that proposes an allowed alternative

**Notes:**
Rejected expanding the work to Downloads, deleting duplicates, treating `final2` as approved by filename, guessing missing values, and publishing automatically. These actions exceed scope, risk data loss or misrepresentation, and publish without review. The alternative is to stay in the selected task folder, preserve sources and versions, flag unknowns, and ask before publication.

**Actual evidence:**
`practice/04-review/my-rejection.md`; commit `a385893`.
