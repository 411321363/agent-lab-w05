# Club file organization report

Each of the 12 input files has one organized copy. Originals remain in `input/`.

## Categories
- `communications/`: announcement and its separately retained copy.
- `materials/`: unapproved simulated budget draft, equipment files, and poster text.
- `feedback/`: feedback questions.
- `planning/`: meeting notes, next steps, both proposals, and rain contingency.

## Identical contents
- `announcement.txt` and `announcement_copy.txt` have identical SHA-256 hashes. Both copies are retained.
- `equipment_list.txt` and `equipment_backup.txt` have identical SHA-256 hashes. Both copies are retained.

## Differing versions and unresolved questions
- `proposal_final.txt` and `proposal_final2.txt` differ. Names do not establish approval. Both proposals remain undecided; a person must choose which, if either, to advance.
- The budget is simulated and unapproved. Confirm before treating it as an expense.
- The announcement leaves time and place undecided. Confirm before sharing it as a real event notice.

## Checks
- Counted 12 input files and confirmed 12 organized copies, each mapped once in `manifest.json`.
- Compared SHA-256 hashes for both identical-content pairs and for the two proposal versions.
- Preserved every original. No source file was deleted or overwritten.
