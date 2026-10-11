# My lab evidence / 我的實作紀錄

Use a group code, not real names or student IDs in shared files. / 共用檔只寫組別代碼，不寫姓名或學號。

- Group code / 組別：Not provided; fill in if required.
- Tool / 工具：Codex with Git in the `agent-lab-w05` repository.
- Route / 路線：Not recorded.
- Tasks completed / 完成題目：A, B v1, B v2, D, and this learning record.
- Material / 素材：NDHU classroom tasks 東華課堂版.
- For original-pack work: Not applicable.
- My role and what I checked / 我的角色與實際檢查：Codex prepared the files and commits. The user ran the six B checks and the phone-width revision check, then reported that all passed.

## Scope and plan / 範圍與計畫

Allowed input and output folders / 可讀取與輸出的資料夾：
- A: `practice/01-club-files/input/` to `practice/01-club-files/output/`.
- B: `practice/02-campus-picker/activities.json` as source; only `practice/02-campus-picker/output/index.html` as the app output.
- D: read `practice/04-review/bad-plan.txt`; write only `practice/04-review/my-rejection.md`.

What I asked for / 原始需求：Complete A, B v1 and v2, and D; commit and push each task; then prepare a record and commit-history screenshot.

What I checked before execution / 動手前我檢查了什麼：A has 12 inputs. All originals remain. Two pairs are identical by SHA-256; the two proposals differ and neither is approved. The pre-existing A commit had only 10 organized copies; follow-up commit `3844abe` added the two missing copies and required report/manifest.

## Tests actually performed / 我真的做過的測試

| Test / 測試 | Expected / 預期 | Observed / 實際 | Evidence / 證據 |
|---|---|---|---|
| B: six required picker scenarios | Filtering, no-match behavior, A09-only result, five-item history, reset behavior, and language switching match the handout | User reported all six passed | User confirmation in this task conversation; commits `aeefbf5` and `66857d4` |
| B: revised phone-width layout | Controls remain usable, action buttons stack, no sideways scrolling | User confirmed the revised layout was working | User confirmation in this task conversation; commit `66857d4` |

## One revision / 一次修改

Before / 原來的情況：Buttons and selects had a 42px minimum height; on phone-width screens the action buttons could sit side by side.

Request / 我提出的修改：Improve phone usability with larger touch targets and stacked actions.

After and retest / 修改後與重測結果：Minimum height is 48px; at widths up to 600px the action buttons stack and fill the available width. User checked the phone-width layout and reported it working.

New requirement or defect? / 新需求還是原規格未做到？A usability improvement, not a failure in the original six checks.

## One rejection / 一次退回

Which action I reject and why / 退回哪個動作、為什麼：Rejected expanding the task to Downloads, deleting duplicates, deciding `final2` is approved based on its filename, guessing missing values, and publishing automatically. These actions exceed scope, risk data loss or misrepresentation, and publish without review.

An acceptable alternative / 可以怎麼改：Stay inside the task folder, preserve originals and all versions, flag unknowns, and ask before any publication.

## Still unverified / 還沒驗證

What I cannot claim is complete / 哪些事不能說已完成：The online text submission destination was not provided. No commit-history screenshot has been saved yet. Group code was not provided. The six B results and phone-width result are based on the user's report rather than my own browser observation.

