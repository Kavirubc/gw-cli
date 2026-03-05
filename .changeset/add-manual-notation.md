---
"@googleworkspace/cli": minor
---

feat: add [MANUAL] notation for human-interaction steps (#66)

Added `[MANUAL]` prefix to help text and stderr hints for commands that
require human interaction (browser open, UI clicks). Also adds two new
`script` helpers: `+open` (open Apps Script editor in browser) and
`+run` (execute a function via the Apps Script Execution API).
