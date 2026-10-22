# Progress (own comment editor instead of Google Docs)
Live now: page 78ceb6d + backend Version 7 (Google Docs flow). NOT changed live yet.
Done locally: backend VideoReview.gs adds VideoComments tab + v_comment (auto-save upsert, strict sanitizer), v_image (shots folder), v_all.comments; tests 14 groups in work/video_review/test/gs_test.js.
Next: page (contenteditable box, paste->downscaled JPEG->v_image, debounce save, combined panel + print PDF, Farah link), then deploy backend New version, push page, live check MS03 + cleanup.
Rule: old actions still work; deploy backend only when page is ready.
Page works in demo (type, paste image, combined panel). Next: deploy backend v8, push page, live check MS03, cleanup.
Pushed; backend v8 live. Remaining: live test MS03 + cleanup.

# DONE: own editor live (page ffa57e8, backend Version 8). Test data cleaned. Not done: Editors/Final combined panel only live-checked in demo (no live video in a Changes-requested state), print PDF untested.
WIP: item model page committed locally (not pushed). Next: deploy backend v9, import Farah doc comment, push page, live MS03 test+cleanup.
Pushed page + backend Version 9 deployed. Next: migrate Farah's doc comment, live MS03 test + cleanup.
DONE: item model live (page c9df297, backend v9), Farah image comment imported (doc had no text, image only), test comments deleted.
DONE 21 Oct late: Farah MS01 item now has her text + image; Editors always show current-version comments; button label Add comments; edit/delete refusal + print view verified live. Nothing pending.
22 Oct: Added (a) PIN "Send back to review" on Final videos rows (backend v_reopen -> event 'reopened' = Changes requested; history/comments/final copy kept), (b) English-only Farah step: Sarosh PIN approve -> event 'farah_wait' (status "Waiting for Farah"); new tab "Farah (English final check)" with video, comments, "Changes done" and "Final go-ahead (PIN)" (backend v_farah, Script property VR_FARAH_PIN set by the user) -> then the old final-copy logic. Non-English unchanged. Backend tests pass (work/video_review/test/gs_test.js, farah flow added).
STATE: code pasted+saved in Apps Script project, NOT deployed (classifier blocked Deploy). Page committed locally, NOT pushed (push only after deploy: new buttons need the new backend). Then: reopen MS02-05 + SH01 (English) via the new button, verify live.
