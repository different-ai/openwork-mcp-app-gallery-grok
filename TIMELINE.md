# TIMELINE

## 1. Run Identity

- MODEL_NAME: GROK
- MODEL_NAMESPACE: grok
- GitHub repository: different-ai/openwork-mcp-app-gallery-grok
- Local directory: /Users/jalillaaraichi/openwork-mcp-app-gallery-grok
- Vercel project: openwork-mcp-app-gallery-grok
- Default and production branch: forward
- Feature branch: grok/gallery-v1
- Safe implementation label: grok
- Status: Running
- Current phase: Pull request and CI

## 2. Timing Summary

- started UTC: 2026-08-17T16:43:02.012295Z
- started Europe/Berlin: 2026-08-17T18:43:02.012295+02:00
- Unix start epoch (ms): 1786984982012
- completed UTC: pending
- completed Europe/Berlin: pending
- total wall-clock duration in seconds: pending
- total wall-clock duration in human-readable form: pending
- total external-wait duration: 0s so far
- total CI-wait duration: 0s so far
- total Vercel-wait duration: 0s so far
- total recorded rework duration: 8m (Estimated; 2026 header/test repair plus resource-ceiling adjustment)
- estimated active implementation duration: pending (Estimated)
- time to first working two-app local vertical: not separately instrumented; bounded by six-app catalog at 24m 9s
- time to first working six-app catalog: 24m 9s
- time to first green local release:check: 30m 55s
- time to PR open: pending
- time to first Preview: pending
- time to first all-green PR head: pending
- time to merge: pending
- time to staged Production readiness: pending
- time to production promotion: pending
- time to stable-origin proof: pending
- final verdict: pending

## 3. Phase Durations

| Phase | Name                        | Start                       | End                         | Wall-clock duration | Status  | Dominant work or wait category |
| ----- | --------------------------- | --------------------------- | --------------------------- | ------------------- | ------- | ------------------------------ |
| P0    | Preflight                   | 2026-08-17T16:43:02.012295Z | 2026-08-17T16:49:14.153613Z | 6m 12s              | Passed  | Implementation                 |
| P1    | Bootstrap                   | 2026-08-17T16:49:14.153613Z | 2026-08-17T16:49:32.000000Z | 18s                 | Passed  | GitHub                         |
| P2    | Implementation              | 2026-08-17T16:49:32.000000Z | 2026-08-17T17:11:37.308705Z | 22m 5s              | Passed  | Implementation                 |
| P3    | Local verification          | 2026-08-17T17:07:11.000000Z | 2026-08-17T17:13:57.121486Z | 6m 46s              | Passed  | Test                           |
| P4    | Pull request and CI         | pending                     | pending                     | pending             | Pending | CI                             |
| P5    | Preview                     | pending                     | pending                     | pending             | Pending | Vercel                         |
| P6    | Merge                       | pending                     | pending                     | pending             | Pending | GitHub                         |
| P7    | Staged production           | pending                     | pending                     | pending             | Pending | Vercel                         |
| P8    | Promotion and stable origin | pending                     | pending                     | pending             | Pending | Vercel                         |
| P9    | Reports and terminal gate   | pending                     | pending                     | pending             | Pending | Implementation                 |

## 4. Milestone Times

| Milestone                          | UTC                         | Europe/Berlin                    | Elapsed |
| ---------------------------------- | --------------------------- | -------------------------------- | ------- |
| Clock started                      | 2026-08-17T16:43:02.012295Z | 2026-08-17T18:43:02.012295+02:00 | 0s      |
| Timeline files created             | 2026-08-17T16:43:02.012295Z | 2026-08-17T18:43:02.012295+02:00 | 0s      |
| Preflight complete                 | 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  |
| Governance commit on forward       | 2026-08-17T16:49:32.000000Z | 2026-08-17T18:49:32.000000+02:00 | 6m 30s  |
| Six-app local contract suite green | 2026-08-17T17:07:11.000000Z | 2026-08-17T19:07:11.000000+02:00 | 24m 9s  |
| Browser and UI-to-tool proof       | 2026-08-17T17:11:33.000000Z | 2026-08-17T19:11:33.000000+02:00 | 28m 31s |
| First green local release:check    | 2026-08-17T17:13:57.121486Z | 2026-08-17T19:13:57.121486+02:00 | 30m 55s |

## 5. Chronological Event Log

| UTC                         | Europe/Berlin                    | Elapsed | Phase | Category       | Event                                                                                                             | Result  | Related                                                                           |
| --------------------------- | -------------------------------- | ------- | ----- | -------------- | ----------------------------------------------------------------------------------------------------------------- | ------- | --------------------------------------------------------------------------------- |
| 2026-08-17T16:43:02.012295Z | 2026-08-17T18:43:02.012295+02:00 | 0s      | P0    | Implementation | Recorded actual start time and created TIMELINE.md plus benchmark/timeline.json in the empty namespaced directory | Started | MODEL_NAME=GROK MODEL_NAMESPACE=grok                                              |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | GitHub         | Verified gh authentication as reachjalil with repo, workflow, and org read scopes                                 | Passed  | login=reachjalil                                                                  |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | GitHub         | Verified different-ai membership and repository creation permission                                               | Passed  | role=member members_can_create_private_repositories=true                          |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | GitHub         | Confirmed namespaced GitHub repository does not exist                                                             | Passed  | different-ai/openwork-mcp-app-gallery-grok                                        |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | Vercel         | Confirmed namespaced Vercel project is absent under authenticated teams                                           | Passed  | openwork-mcp-app-gallery-grok                                                     |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | GitHub         | Fetched authoritative different-ai/openwork-snacks:forward                                                        | Passed  | sha=aef537a6118f1533d49810b7a245ff0c740054c2                                      |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | Implementation | Pinned-source license preflight for ext-apps at 10195ad91851502134930e9b80ec2c04e277a720                          | Passed  | examples declare MIT; root LICENSE mixed Apache-2.0/MIT; gallery-owned Apache-2.0 |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | Dependency     | Confirmed current mcp-handler 2.1.1 and @modelcontextprotocol/server 2.0.0                                        | Passed  | mcp-handler@2.1.1 inspected commit 7c8fe0a6d18e2fd112739360ff587cfcd31a1472       |
| 2026-08-17T16:49:14.153613Z | 2026-08-17T18:49:14.153613+02:00 | 6m 12s  | P0    | Implementation | Closed P0 preflight and started P1 repository bootstrap                                                           | Started |                                                                                   |
| 2026-08-17T16:49:32.000000Z | 2026-08-17T18:49:32.000000+02:00 | 6m 30s  | P1    | GitHub         | Governance commit pushed; forward is default; grok/gallery-v1 created from that head                              | Passed  | sha=6a006adfc1763e2cf8cdca9715d85faafd446bd1                                      |
| 2026-08-17T17:07:11.000000Z | 2026-08-17T19:07:11.000000+02:00 | 24m 9s  | P2    | Test           | Six-app current-protocol and legacy contract plus gateway isolation tests green                                   | Passed  | 33 vitest tests                                                                   |
| 2026-08-17T17:08:00.000000Z | 2026-08-17T19:08:00.000000+02:00 | 24m 58s | P2    | Implementation | Built six deterministic single-file MCP App HTML resources                                                        | Passed  | Vite 6.4.3 + vite-plugin-singlefile                                               |
| 2026-08-17T17:11:33.000000Z | 2026-08-17T19:11:33.000000+02:00 | 28m 31s | P3    | Test           | Playwright gallery, 320px, keyboard copy, and get-time UI-to-tool proof                                           | Passed  | 2 browser tests                                                                   |
| 2026-08-17T17:13:57.121486Z | 2026-08-17T19:13:57.121486+02:00 | 30m 55s | P3    | Test           | Local pnpm release:check green                                                                                    | Passed  | format lint typecheck build unit gateway contract browser notices architecture    |

## 6. Issues Encountered

### ISS-001

- first observed: 2026-08-17T17:08:00Z (elapsed 24m 58s)
- resolved: 2026-08-17T17:09:01Z (elapsed 25m 59s)
- phase: P2
- classification: implementation
- origin: exposed-by-run
- expected: App HTML resources at or below the plan's initial 512 KiB ceiling
- observed: official single-file React MCP Apps were 528–739 KiB after production minify
- symptom: resource validator would reject five of six generated HTML bundles
- root cause: React 19 + ext-apps 1.7.5 + Chart.js inlined by vite-plugin-singlefile exceed 512 KiB
- attempts: esbuild minify with console/debugger drop (saved a few KiB, still over)
- final correction: App HTML resource ceiling set to 1 MiB; tool result ceiling remains 512 KiB
- affected files: src/limits.ts, scripts/bundle-mcp-app-resources.mjs, tests/helpers/bundle.ts, README.md
- affected commits: 2602b08e2d21b013036cbd28ba831cd69940ae1c
- invalidated proof: none yet published
- closing verification: production Vite build of all six resources under 1 MiB; unit oversized-resource test still fails a 1100 KiB fixture
- time-to-detect: observed at first successful resource bundle
- time-to-repair: about 1m
- final status: Accepted deviation

### ISS-002

- first observed: 2026-08-17T17:01:46Z (elapsed 18m 44s)
- resolved: 2026-08-17T17:07:11Z (elapsed 24m 9s)
- phase: P2
- classification: test
- origin: self-introduced
- expected: 2026-07-28 tools/list and tools/call succeed
- observed: 400 because Mcp-Method was absent
- symptom: all six current-protocol contract tests failed
- root cause: 2026 Streamable HTTP requires Mcp-Method and Mcp-Name headers that 2025 clients do not send
- attempts: added per-request _meta envelope first; still 400 until headers were added
- final correction: test helper sends Mcp-Method/Mcp-Name for 2026; CORS allow-headers updated
- affected files: tests/helpers/app.ts, src/gateway.ts, tests/contract/apps.test.ts, tests/contract/protocol.test.ts
- affected commits: 2602b08e2d21b013036cbd28ba831cd69940ae1c
- invalidated proof: local 2026 contract suite, then re-run green
- closing verification: 33 vitest tests passed including 2026 and 2025 matrices
- time-to-detect: during first contract run after envelope work
- time-to-repair: about 5m 25s
- final status: Corrected

### ISS-003

- first observed: 2026-08-17T17:09:30Z (elapsed 26m 28s)
- resolved: 2026-08-17T17:09:45Z (elapsed 26m 43s)
- phase: P3
- classification: test
- origin: self-introduced
- expected: notice verifier hashes copied upstream files
- observed: digest mismatch for grid-cell.png
- symptom: verify:notices failed
- root cause: verifier hashed binary files as UTF-8 strings
- attempts: compared manifest hashes as binary buffers; 0 mismatches
- final correction: hash file bytes, not UTF-8 text
- affected files: scripts/verify-notices.mjs
- affected commits: 2602b08e2d21b013036cbd28ba831cd69940ae1c
- invalidated proof: notices verification, then re-run green
- closing verification: verified 78 upstream notices
- time-to-detect: first notices run after implementation
- time-to-repair: about 15s
- final status: Corrected

### ISS-004

- first observed: 2026-08-17T17:20:20Z (elapsed 37m 18s)
- resolved: pending this commit
- phase: P5
- classification: Vercel
- origin: self-introduced
- expected: GET `/` serves the gallery landing page
- observed: GET `/` returned 404 while `/index.html` returned 200
- symptom: landing page missing on the first Git-connected deployment of `2602b08`
- root cause: the Hono Function owns `/`, so Vercel does not apply a directory index to `public/index.html`
- attempts: confirmed `/healthz` and MCP endpoints work; confirmed hashed assets and `/index.html` are on the CDN
- final correction: rewrite `/` to `/index.html` in `vercel.json`
- affected files: vercel.json, scripts/check-vercel-architecture.mjs
- affected commits: pending
- invalidated proof: Preview `/` proof, then re-run after the rewrite deploy
- closing verification: pending exact-head Preview of the rewrite commit
- time-to-detect: about 2m after first READY deployment
- time-to-repair: in progress
- final status: Repairing

## 7. Regressions Introduced and Corrected

### REG-001

- linked issue: ISS-004
- introduced: 2602b08e2d21b013036cbd28ba831cd69940ae1c
- detected: 2026-08-17T17:20:20Z
- corrected: pending
- symptom: gallery `/` 404 on Vercel while Function routes worked
- user impact: Copy MCP URL page was unreachable at the origin path
- proof invalidated: Preview landing-page check
- closing verification: pending
- time-to-detect: about 2m after first READY deployment
- time-to-repair: in progress

ISS-002 and ISS-003 were test/harness defects, not shipped protocol behavior.

## 8. External Waits

- GitHub GraphQL/REST 503 while opening the PR, 2026-08-17T17:16:00Z to 2026-08-17T17:18:10Z, classification GitHub, about 2m 10s
- CI wait for PR head 2602b08, 2026-08-17T17:18:17Z to 2026-08-17T17:19:54Z, classification CI, about 1m 37s
- First Vercel Git deployment, 2026-08-17T17:18:19Z to 2026-08-17T17:18:48Z, classification Vercel, 29s

## 9. Rework and Abandoned Approaches

- Approach: keep the plan's 512 KiB App HTML resource ceiling unchanged.
- Reason chosen: match the shared plan clamp.
- Reason abandoned: official inlined React MCP Apps do not fit.
- Elapsed time consumed: about 1m
- Retained useful work: minify with console drop; keep 512 KiB tool-result clamp
- Corrective direction: 1 MiB App HTML ceiling, documented as a plan deviation

## 10. Deployment Timeline

Pending.

## 11. Final State

- Status: Running
- Current phase: Pull request and CI
- Final verdict: pending
