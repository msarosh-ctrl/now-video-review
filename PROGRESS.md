# Progress (own comment editor instead of Google Docs)
Live now: page 78ceb6d + backend Version 7 (Google Docs flow). NOT changed live yet.
Done locally: backend VideoReview.gs adds VideoComments tab + v_comment (auto-save upsert, strict sanitizer), v_image (shots folder), v_all.comments; tests 14 groups in work/video_review/test/gs_test.js.
Next: page (contenteditable box, paste->downscaled JPEG->v_image, debounce save, combined panel + print PDF, Farah link), then deploy backend New version, push page, live check MS03 + cleanup.
Rule: old actions still work; deploy backend only when page is ready.
Page works in demo (type, paste image, combined panel). Next: deploy backend v8, push page, live check MS03, cleanup.
Pushed; backend v8 live. Remaining: live test MS03 + cleanup.

# DONE: own editor live (page ffa57e8, backend Version 8). Test data cleaned. Not done: Editors/Final combined panel only live-checked in demo (no live video in a Changes-requested state), print PDF untested.
WIP: item model page committed locally (not pushed). Next: deploy backend v9, import Farah doc comment, push page, live MS03 test+cleanup.
