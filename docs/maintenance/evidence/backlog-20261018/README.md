# PR backlog review — 2026-10-18 MDT / 2026-10-19 UTC

Base reviewed: `095b4869b5fe386e2f3a273cc5b60ec3853c8659` (`main`, 1.83.1).
This is a review and correction batch, not release authorization. The owner's
original checkout (`main` at `446a0f163`) and its desktop edits were preserved.
Contributor fixes stay on their own PR branches; this maintainer evidence PR
contains review records and proof only.

## Coverage and order

Paginated GitHub discovery refreshed the authenticated owner's repositories and
accessible organizations (`Centeva`, `pylon-code`, `kraken-crm`), including private
and archived candidates and the plugin links. Six managed repositories matched:
Meridian, OpenCode/Pi/Hermes/OpenClaw scrub, and HUDScrub. No additional managed
scrub candidate or inaccessible candidate was found.

Initial queue: **29 Meridian PRs, two scrub release PRs**. All five scrub
repositories have zero open issues and zero contributor PRs. Meridian's open
issues were inventoried; this batch prioritizes PRs and their linked reports,
without claiming unrelated issues resolved. Drafts, explicit no-review requests
and prior owner holds remain in force.

## Concrete review results

| PR | Disposition | Work or remaining gate |
| --- | --- | --- |
| [#1409](https://github.com/rynfar/meridian/pull/1409) | Accept test infrastructure change, pending final validation disposition | Independent safety review, focused tests and exact before/after leak probe pass; typecheck/build pass. Local full-suite failures under investigation. See below. |
| [#1411](https://github.com/rynfar/meridian/pull/1411) | Accept with correction | Reproduced all-hidden URL state becoming visible after reload. Correction, regression tests and actual browser verification underway on contributor branch. |
| [#1410](https://github.com/rynfar/meridian/pull/1410) | Accept with correction | Real SDK tools/list confirms canonical cache digest merges schemas whose advertised property order differs. Insertion-sensitive schema identity correction underway. Real OpenCode/plugin and cache/heap acceptance remain separate gates. |
| [#1396](https://github.com/rynfar/meridian/pull/1396) | Fix before merge | P1: truncating all post-cache-breakpoint blocks hides durable instruction edits. Exact-reminder-only correction and negative controls underway. Actual Fable/client acceptance and forwarded-source attribution remain open. |
| [#1398](https://github.com/rynfar/meridian/pull/1398) | Validate warning change | Actual Bun/Node startup verification and local gates underway. This warns; it does not fix underlying Bun disconnect handling. Forwarded-source attribution remains open. |
| [#1407](https://github.com/rynfar/meridian/pull/1407) | Accept code scope; hold acceptance evidence | No surviving source defect; actual AgentLink source consumes error after length finish. Need actual affected-client/model before/after error propagation and ordinary truncation control, plus local final gates. |
| [#1403](https://github.com/rynfar/meridian/pull/1403) | Accept code scope; hold acceptance evidence | No surviving source defect; downstream nested documents/replay supported. Need a complete PDF receipt through real message/tool-output JSON/SSE flows and actual affected client/model (unspecified by contributor), plus local gates. Header-only mapping fixture is not model PDF proof. |
| [#1406](https://github.com/rynfar/meridian/pull/1406) | Accept with corrections | Make passthrough CLAUDE.md Project/Full limitations truthful in UI/type/Crush docs. Prove fresh and previously contaminated resume isolation through actual plugin-qualified OpenCode. Does not resolve agent-switch issue #1404. |
| [#1394](https://github.com/rynfar/meridian/pull/1394), [#1395](https://github.com/rynfar/meridian/pull/1395), [#1397](https://github.com/rynfar/meridian/pull/1397) | Strong candidates after live gates | No surviving implementation defect in async process identity, client cwd, or abort-link ownership. Missing exact-head affected-client/model/platform proof; forwarded-source attribution hold. |
| [#1399](https://github.com/rynfar/meridian/pull/1399) | Fix before merge | An idle close joins a previously started 64-deletion sweep; new drain cap is bypassed. Add active-sweep/close control and reduce remaining work cooperatively; keep deletion join. |
| [#1400](https://github.com/rynfar/meridian/pull/1400) | Fix before merge | Reproduced 10-minute advertised pool wait when effective account/model benches require at least three hours. Calculate from effective marks, add repeated-shorter/overlap controls; natural actual-account live gate remains. |
| [#1401](https://github.com/rynfar/meridian/pull/1401) | Partial fix, scope/evidence hold | Useful stale-copy guard; newer-map eviction/read failure still loses assistant answers. Need explicit accepted limited scope or own-copy gap backstop and real A→B→A/rewind controls. |
| [#1220](https://github.com/rynfar/meridian/pull/1220) | Accept direction, corrections required | Three known snapshot/revocation/cache-epoch fixes remain absent after rebase; original residual E41 cache failure unexplained. #1244 contract already approved. |
| [#1243](https://github.com/rynfar/meridian/pull/1243) | Defer submitted SQL implementation | Mutable authority, legacy retirement race and live-lease overwrite persist; automatic default migration conflicts with already approved opt-in/offline #1277. Depends on #1220. |
| [#1219](https://github.com/rynfar/meridian/pull/1219) | Defer corrected implementation | Approved opt-in SQL contract exists; immutable custody/admission/native recovery/shutdown and source/installed acceptance still incomplete. |
| [#1261](https://github.com/rynfar/meridian/pull/1261) | Defer unsafe sweep | Rebased core sweep/retention blobs remain identical to previously rejected ownership/deletion implementation; actual native-history and joined lifecycle proof missing. |
| [#1314](https://github.com/rynfar/meridian/pull/1314), [#1340](https://github.com/rynfar/meridian/pull/1340) | Defer demonstrated evidence gaps | Existing duplicate-write proof still fails or submitted gate passes unchanged baseline. Require discriminating actual-model proof and legitimate repeated-read control. |
| [#1317](https://github.com/rynfar/meridian/pull/1317), [#1322](https://github.com/rynfar/meridian/pull/1322) | Obsolete integration drafts; never squash | Carry source contributions under withdrawn process; attribution checks fail. Preserve useful evidence, move necessary changes onto original source PRs. No silent closures. |
| [#1266](https://github.com/rynfar/meridian/pull/1266), [#1347](https://github.com/rynfar/meridian/pull/1347), [#1359](https://github.com/rynfar/meridian/pull/1359) | Retain existing draft/environment holds | Exact macOS/nono diagnostics, qualified account-routing, or native Windows installed lifecycle evidence respectively. No account/paid-usage changes inferred. |
| [#1193](https://github.com/rynfar/meridian/pull/1193) | Retain owner hold | Prompt warming/background-call contract and real benefit/foreground priority/cancellation proof needed; no warming started. |
| [#1402](https://github.com/rynfar/meridian/pull/1402) | Respect explicit no-review request | Contributor wants to test/review privately first. No code review started; wait for ready/review request. |
| [#1408](https://github.com/rynfar/meridian/pull/1408) | Retain draft/contract/live holds | New Pi attestation/health/environment contract needs tracked approval; no successful live generation/tool/cache/priority failback proof. |
| [#1050](https://github.com/rynfar/meridian/pull/1050) | Historical research draft | Antigravity production work has advanced independently; no review-ready request and no reason to land research draft. |
| [OpenCode scrub #20](https://github.com/rynfar/meridian-plugin-opencode-scrub/pull/20), [Pi scrub #15](https://github.com/rynfar/meridian-plugin-pi-scrub/pull/15) | Defer releases | No release authorization; both candidate heads have no checks/statuses. Fresh release/installed-package gates remain, despite historical main evidence. |

Exact original heads, individual findings and revisit conditions are in
[older PRs](older-prs.md), [storage](storage.md), [session/routing](session-routing.md),
[passthrough](passthrough.md), [stream/PDF](stream-and-pdf.md), and
[scrub queues](scrub-queues.md). These record the review-stage heads; completed
correction/verification results below supersede their initial status.

## #1409 — independent proof and review

Source head `9ff41a427da3a67e207e3d83121cefa552b659a0`, Nowaker
(`spam@nowaker.net`), signed; base exactly the reviewed main. Eight applicable
CI checks succeeded, including [test](https://github.com/rynfar/meridian/actions/runs/39180208214/job/117831154161),
Windows smoke, desktop macOS/Linux, Nix and Docker; changelog duplication skipped.
Recheck head/base/checks before any merge.

Product fit: contains disposable test fixtures and explicitly inherited child
environments under an owned process temp directory. No runtime behavior or model
call changes. Independent full-diff review found no material safety issue:
ESRCH-only stale-owner detection, current/live-owner exclusion, foreign names,
symlinks and invalid PIDs remain protected. Every query/test process retains its
own directory, and existing once-per-run afterAll cleanup remains authoritative.
Windows TMP/TEMP and path joins are preserved. A Bun child with omitted env may
inherit startup env rather than the updated process.env on old Bun; the PR
discloses this limitation. No new production/public contract/dependency change.

Local platform: Darwin arm64, Node 22.22.3, Bun 1.3.14, frozen lockfile SDK 0.2.141
and Claude Code 2.1.296. Focused command:

```sh
bun test src/__tests__/preload-tmp-cleanup.test.ts src/__tests__/quiet-telemetry-banner.test.ts src/__tests__/polytoken-feature-defaults.test.ts
```

Result: **21 pass / 0 fail**, including passing/failing/timed-out/killed runs,
live owner preservation, child fixture cleanup and malformed-path safety.
Standalone `npm run typecheck` and `npm run build` both exit 0.

A single identical generated Bun fixture ran with a copy of unchanged main's
preload/helper and then with the candidate preload. It creates a fixture and an
explicit-env child fixture, asserts tmpdir is the process-owned directory, then
checks leftovers after process exit:

```json
{"label":"before","exit":1,"leftovers":["leaked-child-<id>","leaked-fixture-<id>"]}
{"label":"after","exit":0,"leftovers":[]}
```

The committed regression test above independently retains this assertion.
This is test-infrastructure E2E, not a claim of model/client behavior proof.

**Full local gate remains under investigation.** Initial npm test reached three
failures: a race fixture read an existing but not-yet-written result as empty;
a Node child close test timed out; an optional Git timing-budget assertion
failed under load. The race/Node files pass **8/8 with 2 platform skips** on both
unchanged main and candidate when isolated. Isolated success is not proof of
causality or a green full gate. The complete unchanged-main comparison is in
progress, and all failures are retained rather than dismissed by a green rerun.

## Forwarded-source attribution

PRs #1394–#1401 were opened by `passabilities` and include verified commits by
`eamonster27`, a different account, plus the opener's corrections. No original
source-author PR exists in Meridian. Squashing the forwarded PRs gives the
opener primary authorship, contrary to the current source-Author rule. The owner
has been asked whether to keep the rule/hold or explicitly permit verified source
coauthor credit for these forwarded PRs. No exception is inferred from silence.
Code review/correction can continue independently; no such PR merges meanwhile.

## Remaining operational gates

Actual OpenCode/Claude work always requires the matching Meridian client plugin,
mandatory E2E preflight, effective config and runtime load/route witnesses.
Mocks/loopback fixtures are distinguished from actual-model/client acceptance.
No paid Extra Usage, warmers, releases, external comments or destructive history
changes are authorized by this batch. Required exact-head CI is never bypassed
for code/evidence failures. The narrowly documented unsigned-commit exception
can only be considered after all other gates pass.
