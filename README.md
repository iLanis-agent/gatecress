# Gatecress 1.0 TEST
Native Android Slalom/Suraromu. Original generated small layouts. Android 8+ (min 26), target 35. Package com.gg007.gatecress.

## Rules
Slalom/Suraromu. Draw one closed noncrossing, unbranched orthogonal loop from the circled 3, through gates G1, G2, G3 in order, then back to the circle. Either direction may establish this order. Each dotted gate spans one or more cells: visit exactly one of those cells and go straight perpendicular to the dashes there. Do not run along a gate. Black X cells are blocked; other ordinary cells are optional. The circle counts the three gates, not steps. This edition puts G1-G3 beside the dashed gates instead of in black endpoint cells. Twelve original unique 4x4 courses, twelve distinct loops, and a multi-cell gate on every course. Tap gaps to toggle roads; undo/reset/next/levels and saved palette/cell numbers.

## Download and status
https://mega.co.nz/#!gY8RBACL!E8BGF7nIA6aLAABZbbw4pEhrzulFNAQ66G-603QYT7I
APK SHA256 a835b33bd8d0d685c72e42dbf3d75a5c27bdeb3c9994ce817fec43f89aa37784; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous bytes match.

## Checks
Portable generator enumerates all 213 simple cell-center loops on a 4x4 grid and builds twelve original uniquely constrained black-cell/start/gate courses. Independent Java ordered-cycle tracing agrees with production degree/BFS topology on ALL 16,777,216 edge masks. Gate crossing and order checks independently use signed coordinate displacement and cyclic distances versus production neighbor alignment and directional traversal. All 213 loops across twelve boards prove one solution each. Another 120,000 random/invalid gate, start, blocker and orientation cases, 288 single-edge mutations, bounds, solved lock and undo/replay/reset pass. Archived generator reproduces levels.json and all-cycles.json; archived Java rerun passes. Drawing adapter checks actual road taps, completion, undo/replay, next/levels/menu/settings/privacy and saved palette/cell numbers. Six drawing screens inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Functional review of all 168 prior studio cards and the 803-entry web registry found no Slalom match. Prism Relay routes a mirror beam through point relays; Entryfern counts room entries on an all-cell open path; Frostcross is an open directed ice/arrow route. Gatecress instead orders crossings of multi-cell gates on one optional-cell closed loop and permits exactly one crossing cell per gate. Known Nikoli Slalom/Suraromu, not a global invention. Original generated clues, no source puzzle/artwork/code copied. Gate labels beside dashes are a display adaptation. Recovered repository corpus remains partial.
Primary rules https://www.nikoli.co.jp/en/puzzles/suraromu/ . Independent English rules https://puzzles.paramesis.com/puzzle-descriptions/suraromu/ .

## Build
JDK 17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json and all-cycles.json. javac -d /tmp/pipe-test src/com/gg007/gatecress/Board.java BoardTest.java then java -cp /tmp/pipe-test com.gg007.gatecress.BoardTest. bash build.sh makes unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private signing inputs. No secrets in source. Release build settings; signed TEST artifact, not final store release.

## Privacy and branding
Gatecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, cell numbers and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation
Complete source/APK, exact cumulative 169-card studio and published catalog/studio sources/updater privately preserved at https://files.instinct.com/6var65qp3zg4-gatecress-source-archive . Repository https://github.com/iLanis-agent/gatecress holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
