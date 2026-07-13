Week 7 — Issue selection

Issue link: https://github.com/jamjamgobambam/pathreview/issues/117

Issue title: API docs don't include example curl commands

Tier: [x] Tier 1  [ ] Tier 2  [ ] Tier 3

Problem summary:
Issue #117 reports that pathreview's API documentation describes the available
endpoints but doesn't show any example curl commands for calling them. This
makes it harder for a new contributor or API consumer to test an endpoint
without first reverse-engineering the request format from the source code.
A successful fix adds a working curl example under each documented endpoint,
showing the correct method, headers, and a sample request body/response
where relevant. This affects the API reference docs [confirm exact file,
e.g. docs/API.md].

Selection notes ("Is this right for me?" checklist):
Confirmed this is Tier 1 and labeled "good first issue" — scoped to
documentation only, no application code changes required. Low risk of scope
creep since it doesn't touch shared logic, state, or other open issues.
Good first choice since it's self-contained and lets me focus on setup and
workflow (branching, PR process) without also debugging unfamiliar code.

Branch name: docs/117-api-curl-examples

Setup confirmation: [ ] App runs locally at localhost:5173

Cohort ledger: [ ] Issue added to cohort ledger
